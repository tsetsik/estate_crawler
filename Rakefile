require 'rspec/core/rake_task'
require 'rubocop/rake_task'

RuboCop::RakeTask.new(:rubocop)
RSpec::Core::RakeTask.new(:spec)

task default: %i(run_crawler)

task :run_crawler do
  ruby 'estate_crawler.rb'
end