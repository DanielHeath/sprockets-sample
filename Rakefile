require './sprockets/environment'

env = SprocketsEnv.new
env.environment.css_compressor = :yui
env.environment.js_compressor = :uglifier
env.rake_task

task :server do
  Process.exec 'bundle exec rackup -p 11111 sprockets/config.ru'
end
