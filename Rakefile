require 'bundler/gem_tasks'
require 'rake/testtask'
require 'rake/notes/rake_task'

Rake::TestTask.new(:test) do |t|
  t.libs << 'spec'
  t.libs << 'lib'
  t.test_files = FileList['spec/**/*_spec.rb']
end

task default: :test
