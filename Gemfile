source "http://rubygems.org"

platform :jruby do
  gem 'jruby-openssl'
end

platform :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'rubinius-developer_tools'
end

group :development do
  gem 'rake', :require => false
  gem 'rdoc'
  gem 'simplecov', :platforms => [:ruby_19, :ruby_20]
  # For Jenkins
  gem 'test-unit'
  gem 'ci_reporter'
  gem 'ci_reporter_test_unit'
  gem 'simplecov-rcov', :platforms => [:ruby_19, :ruby_20]
  gem 'pry'
  gem 'rack'
  gem 'rubysspi'
  gem 'rubyntlm'
  gem 'rack-ntlm-test-service'
end

gemspec
