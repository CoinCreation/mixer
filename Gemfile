# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'sinatra'
gem 'sinatra-contrib'
gem 'data_mapper'
gem 'dm-sqlite-adapter'
gem 'dm-types'
gem 'sqlite3'
gem 'rest-client'
gem 'rake'

gem 'sidekiq'
gem 'sidekiq-cron'

group :development, :test do
  gem 'awesome_print'
end

group :development do
  gem 'pry'
end

group :test do
  gem 'rspec'
  gem 'rack-test'
  gem 'database_cleaner'
end
