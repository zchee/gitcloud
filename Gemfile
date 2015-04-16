source 'https://rubygems.org'
ruby '2.2.2'

gem 'rails'
gem 'responders'

# Server
gem 'unicorn-rails'

# Database
gem 'pg'

# KVS
gem 'hiredis'
gem 'moneta'
gem 'redis', require: %w(redis redis/connection/hiredis)
gem 'redis-namespace'
gem 'redis-objects', require: 'redis/objects'
gem 'redis-session-store'

# APIs
gem 'devise'
gem 'omniauth'
gem 'omniauth-github'
gem 'octokit'
gem 'github_api'
gem 'pusher'

# Assets
gem 'browserify-rails', '~> 0.5'
# gem 'coffee-rails'
gem 'hamlit'
gem 'jade-rails'
gem 'jbuilder'
gem 'react-rails', github: 'reactjs/react-rails'
gem 'sass-rails'
gem 'slim-rails'
gem 'therubyracer', platforms: :ruby
gem 'turbolinks'
gem 'uglifier'

# Models
gem 'active_hash'
gem 'paper_trail', '~> 4.0.0.beta2'

# Views
gem 'bootstrap-sass'
gem 'jquery-rails'
gem 'kaminari'
gem 'zocial-rails'

# Helpers
gem 'bcrypt'
gem 'friendly_id'
gem 'high_voltage'
gem 'parallel'

# Middleware
gem 'faraday-http-cache'
gem 'faraday-lazyable'
gem 'faraday_api_cache'
gem 'typhoeus', require: 'typhoeus/adapters/faraday'

# Data serialize
gem 'msgpack'

# Javascripts
gem 'nprogress-rails'

# Background
gem 'sidekiq'
gem 'sinatra', require: false
gem 'slim'

# Performance
# gem 'bugsnag'
# gem 'gctools'
# gem 'skylight'
gem 'newrelic-faraday'
gem 'newrelic-redis'
gem 'newrelic_rpm'
gem 'peek'
gem 'peek-faraday'
gem 'peek-gc'
gem 'peek-git'
gem 'peek-performance_bar'
gem 'peek-pg'
gem 'peek-rblineprof'
gem 'peek-redis'
gem 'peek-sidekiq'
gem 'pygments.rb', :require => false

group :development do
  gem 'activerecord-cause'
  gem 'annotate'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller', '>= 0.7.3.pre1'
  gem 'brakeman', :require => false
  gem 'bullet'
  gem 'capistrano'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano-rails-console'
  gem 'debase'
  gem 'did_you_mean'
  gem 'dotenv-rails'
  gem 'erb2haml'
  gem 'meta_request'
  gem 'pry-rails'
  gem 'quiet_assets'
  gem 'rack-mini-profiler'
  gem 'rails-footnotes'
  gem 'rails-perftest'
  gem 'rails_layout'
  gem 'rubocop', require: false
  gem 'ruby-debug-ide'
  gem 'ruby-prof'
  gem 'tapp'
  gem 'view_source_map'
end

group :development, :test do
  # gem 'web-console'
  gem 'byebug', require: !ENV['RM_INFO']
  gem 'byebug-color-printer'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'launchy'
  gem 'parallel_tests'
  gem 'pry-byebug'
  gem 'rspec-rails'
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :test do
  gem 'json_spec'
  gem 'rspec-sidekiq'
  gem 'fakeredis', require: 'fakeredis/rspec'
  gem 'selenium-webdriver'
end

group :production do

end
