source 'https://rubygems.org'
gemspec

gem 'jruby-openssl', :platforms => :jruby

group :test, :remote_test do
  # gateway-specific dependencies, keeping these gems out of the gemspec
  gem 'braintree', '>= 2.50.0'
  gem 'pry'
  gem 'pry-rails'
  gem "pry-byebug"
  gem "pry-stack_explorer"
  gem "pry-doc"
  gem 'awesome_print'
end
