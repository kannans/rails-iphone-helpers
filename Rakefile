#!/usr/bin/env rake

require 'bundler/gem_tasks'
require 'rake/testtask'

task :default => :test

Rake::TestTask.new(:test) do |t|
  t.libs << 'test'
  t.test_files = FileList['test/**/*_test.rb']
  t.name = :test
  t.ruby_opts = ['-r test_helper']
  t.verbose = true
end
