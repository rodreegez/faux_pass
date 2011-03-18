require 'rake'

task :test => ['test:fail'] # <-- change this


namespace :test do
  task :pass do
    ruby 'test_pass.rb'
  end
  task :fail do
    ruby 'test_fail.rb'
  end
  task :error do
    ruby 'test_error.rb'
  end
end
