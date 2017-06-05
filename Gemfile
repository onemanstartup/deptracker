# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'lograge' # Clean logs
gem 'logstash-event'

gem 'aasm' # State machine
gem 'bcrypt', '~> 3.1.7' # Use ActiveModel has_secure_password
gem 'devise', '~> 4.3.0' # User authentication
gem 'hiredis'
gem 'redis', '~> 3.0' # Dependency for ActionCable, Sidekiq

gem 'http_accept_language'
gem 'russian' # Russian localization

gem 'mailgun_rails'                          # Mailing
gem 'shrine'                                 # File Upload
gem 'simple_form', '~> 3.5.0'
# TODO: decide which store to use
# gem 'activerecord-session_store'
# gem 'redis-session-store'
# gem 'administrate', github: 'greetpoint/administrate', branch: 'rails5'
gem 'counter_culture', '~> 1.6.2'
gem 'datagrid'
# gem 'rein'

# Admin
gem 'logster' # Depends on redis

# Working without rails
# gem 'trailblazer', '~> 1.1.2'
gem 'trailblazer', '>= 2.0.4'

# gem 'reform', '~> 2.3.0.rc1'
gem 'cells-slim', require: false # TODO: research replacing actionview
gem 'reform'
gem 'reform-rails', '~> 0.1.7'
gem 'trailblazer-cells'

gem 'trailblazer-rails', '>= 1.0.0'
# gem 'trailblazer-rails', '~> 0.3.1'
gem 'trailblazer-endpoint', github: 'trailblazer/trailblazer-endpoint'
gem 'uber', '0.0.15'

# gem 'cells-rails'
gem 'dry-types'
gem 'dry-validation'
gem 'responders' # rails dependant
# Api
gem 'multi_json'
gem 'roar-rails'
# Sidekiq
gem 'sidekiq', '5.0.2'
gem 'sinatra', require: nil
# gem 'sidekiq'                                # ActiveJob backend
# gem 'sidekiq-failures'                       # Tracking failures
gem 'sidekiq-status' # Tracking status
# gem 'sinatra', '>= 2.0.0', require: nil      # Web version
gem 'sidekiq-cron'                           # Scheduling
gem 'sidekiq-limit_fetch'                    # Limiting queues
# Api
gem 'rack-cors'
# Server Needs
gem 'figaro' # ENV variables
# Bitcoin
gem 'addressable'
gem 'bitcoin-ruby', '~> 0.0.10', require: false
gem 'btcruby', require: false
gem 'dentaku'
gem 'money'
gem 'money-open-exchange-rates'
gem 'socksify'
# Bots
gem 'telegram-bot-ruby'
gem 'xmpp4r'

gem 'show_for'

gem 'faraday'
gem 'kaminari', '~> 1.0.1' # Pagination

gem 'browser', require: 'browser/browser'

# Internationalization
gem 'activemodel-serializers-xml' # needs for lasted rails 5
gem 'countries', '~> 2.0.0.pre.3'
gem 'devise-i18n'
gem 'geocoder', '~> 1.4.3'
gem 'i18n-country-translations'
gem 'i18n-js', '>= 3.0.0.rc12'
gem 'i18n-timezones'
gem 'rails-i18n', '~> 5.0.0'
# Frontend
gem 'active_link_to' # This at least updates
gem 'autoprefixer-rails' # done(automatic)
gem 'country_select' # For admin pages
gem 'meta-tags' # todo
gem 'slim-rails' # done(automatic)
gem 'sprockets'
gem 'webpack-rails'

group :development do
  gem 'i18n-tasks', '~> 0.9.15', require: false

  gem 'brakeman', require: false
  gem 'bundler-audit', require: false # Security
  gem 'foreman', require: false
  gem 'good_migrations' # Don't require AR models in migrations
  gem 'guard', require: false # Run commands on file change
  gem 'guard-brakeman', require: false
  gem 'guard-bundler', require: false
  gem 'guard-rspec', '~> 4.7'
  gem 'guard-rubocop', require: false
  gem 'letter_opener'
  gem 'rubocop', require: false
  gem 'rubocop-rspec', require: false
  gem 'rubycritic', require: false
  gem 'terminal-notifier-guard', require: false

  # Deploy
  gem 'airbrussh', require: false
  gem 'capistrano', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-db-tasks', require: false
  gem 'capistrano-npm',     require: false
  gem 'capistrano-nvm',     require: false
  gem 'capistrano-rails',   require: false
  gem 'capistrano-rvm',     require: false
  gem 'capistrano-sidekiq', '0.5.4', require: false
  gem 'capistrano3-puma',   '1.1.0', require: false
  gem 'derailed_benchmarks', require: false

  gem 'bumbler', require: false
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails',        '>= 3.6.0'
  gem 'spring-commands-rspec'

  # Favorite debugging gems
  gem 'pry'
  gem 'pry-byebug'
  # gem 'pry-coolline' # let's see if you notice :) It slows boot time

  # Color console output
  gem 'awesome_print'
  gem 'rainbow'
end

group :test do
  gem 'factory_girl_instruments'
  gem 'faker'

  gem 'json_schema'
  gem 'mutant-rspec', '~> 0.8.13'

  gem 'capybara'
  gem 'chromedriver-helper'
  gem 'selenium-webdriver'

  gem 'shoulda-matchers', '~> 3.1'
  gem 'simplecov', require: false
  gem 'timecop'
  gem 'vcr'
  gem 'webmock'
end
