require 'rake/testtask'
require 'minitest'

$: << File.expand_path('../lib', __FILE__)

Rake::TestTask.new do |t|
  t.libs << %w(test lib)
  t.pattern = 'test/**/*_test.rb'
end

task :default => :test
