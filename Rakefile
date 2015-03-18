require 'rubocop/rake_task'
require 'rspec/core/rake_task'

Rubocop::RakeTask.new(:cop)
RSpec::Core::RakeTask.new(:spec)

test(default: [:cop,:spec])