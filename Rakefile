#!/usr/bin/env rake
# frozen_string_literal: true

require 'bundler/gem_tasks'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec)
task default: :spec

task :console do
  require 'irb'
  require 'irb/completion'
  require 'phony_rails'
  ARGV.clear
  IRB.start
end
