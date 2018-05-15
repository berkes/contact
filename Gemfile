# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem 'pony'
gem 'sinatra'

group :development do
  gem 'capistrano'
end

group :development, :test do
  gem 'minitest'
  gem 'minitest-assert_changes'
  gem 'rack-test'

  gem 'rubocop'

  gem 'awesome_print'
  gem 'byebug'

  gem 'foreman'
  gem 'rerun'
end
