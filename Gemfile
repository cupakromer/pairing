source 'https://rubygems.org'

gem 'rails', '3.2.8'

gem 'rake', '~> 0.9.2'
gem 'thin', '~> 1.4.0'
gem 'mongoid', '~> 3.0.4'
gem 'bson_ext', '~> 1.6.4'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'therubyracer', '~> 0.10.2', platforms: :ruby
  gem 'uglifier', '~> 1.2.0'
  gem 'bootstrap-sass', '~> 2.0.4'
  gem 'simple_form', '~> 2.0.2'
end

group :development, :test do
  gem 'rspec-rails', '~> 2.11.0'
  gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i
  gem 'guard-rspec', '~> 1.2.1'
  gem 'spork'
  gem 'guard-spork'
end

group :test do
  gem 'database_cleaner', '~> 0.8.0'
  gem 'mongoid-rspec', '~> 1.5.4'
end

group :development do
  gem 'reek', '~> 1.2.12'
  gem 'cane', '~> 2.2.0'
  gem 'travis-lint', '~> 1.4.0'
end

gem 'jquery-rails', '~> 2.1.0'
gem 'haml-rails', '~> 0.3.4'

# gem 'bcrypt-ruby', '~> 3.0.0'
