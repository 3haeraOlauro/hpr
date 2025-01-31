# frozen_string_literal: true

source 'https://rubygems.org'
# source 'https://gems.ruby-china.com'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# Web Services
gem 'puma', '~> 6.2.0'
gem 'sinatra', '~> 3.0.5'
gem 'sinatra-contrib', '~> 3.0.5'

# Background Job Service
gem 'sidekiq', '~> 7.0.8'
gem 'sidekiq-failures', '~> 1.0.4'

# Database
gem 'activerecord', '~> 7.0.4'
gem 'sqlite3', '~> 1.6.2'

# Tools
gem 'chronic_duration', '~> 0.10.6'
gem 'commander', '~> 4.6.0'
gem 'git', '~> 1.18.0'
gem 'gitlab', '~> 4.19.0'
gem 'rake'
gem 'sentry-ruby'
gem 'sentry-sidekiq'
gem 'settingslogic', '~> 2.0.9'

group :development, :test do
  # Test
  gem 'rack-test'
  gem 'rspec'
  gem 'rubocop'

  # Debug
  gem 'awesome_print'

  gem 'guard'
  gem 'guard-puma'
  gem 'guard-sidekiq'
end
