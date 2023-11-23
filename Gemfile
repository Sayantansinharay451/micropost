# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.1'
gem 'bcrypt', '~> 3.1.7'
gem 'bootsnap', require: false
gem 'jbuilder'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rack-cors'
gem 'rails', '~> 7.0.8'
gem 'rubocop', require: false
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker'
end

group :test do
  gem 'rails-controller-testing'
  gem 'rspec-rails'
end

group :development do
  gem 'better_errors', '~> 2.10', '>= 2.10.1'
  gem 'pry'
end

gem 'rubocop-factory_bot', '~> 2.24'
gem 'rubocop-rails', '~> 2.22'
gem 'rubocop-rspec', '~> 2.25'
