require "bundler/gem_tasks"
require 'rake/testtask'

task default: %i[test]

Rake::TestTask.new do |t|
  t.libs << 'test/unit'
  t.test_files = FileList['test/test*.rb']
  t.verbose = true
end
