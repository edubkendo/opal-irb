require 'bundler/setup'
require 'opal/rake_task'

Opal::RakeTask.new do |t|
  t.name = 'opal_repl.rb'
  t.parser = true
  t.files = '.'
  # t.dependencies = ['opal-jquery']
end

task :default => [:opal]
