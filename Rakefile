require 'bundler/setup'
require 'thread'
require 'launchy'
require 'hirohata/reporter'

desc 'preview する。 http://localhost:4000/'
task :preview do
  Thread.new do
    sleep 0.5
    Launchy.open 'http://localhost:4000/hirohata/'
  end

  sh 'bundle exec jekyll serve --watch'
end

desc 'reportの雛形を生成'
task :report do
  date = Date.today.last_week
  end_date = Hirohata::Reporter.end_date(date)
  reporter = Hirohata::Reporter.new(Hirohata::Reporter.config)
  body = reporter.report(end_date, :all)
  File.open("_posts/#{end_date}-report.markdown","w") do |io|
    io.puts body
  end
end

desc 'webサイトを開く'
task :open do
  Launchy.open 'http://great-h.github.io/hirohata/'
end
