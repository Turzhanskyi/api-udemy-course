# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'active_model_serializers', '~> 0.10.12'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 6.1.3', '>= 6.1.3.2'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails', '~> 6.2'
  gem 'rspec-rails', '~> 5.0', '>= 5.0.1'
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'rubocop-rails', '~> 2.10', '>= 2.10.1', require: false
  gem 'spring'
end

group :test do
  gem 'test-prof', '~> 1.0', '>= 1.0.2'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
