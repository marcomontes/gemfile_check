ruby '2.3.1'

source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7.1'
# Use PostgreSQL as the database for Active Record
gem 'pg', '0.19.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'haml-rails', '~> 0.9'

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery-ui-rails', '5.0.5'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Active admin
gem 'activeadmin', '~> 1.0.0.pre2'

# Devise
gem 'devise', '4.2.0'

# Mail
gem 'mail'

# Upload image
gem 'paperclip', '5.1.0'
gem 'aws-sdk', '2.7.10'

# QR Code
gem 'rqrcode'

# Social Authentication
gem 'omniauth-oauth2', '~> 1.4.0'
gem 'omniauth-facebook', '~> 4.0.0'
# gem 'omniauth-google-oauth2', '~> 0.3.1'

# Twitter gem
# gem 'twitter'

# Facebook gem
gem "koala", "~> 2.0"

# Google+ gem
gem 'google-api-client', '0.9.9'

gem "fog-aws"
gem "fog"

# tinymce editor
gem 'tinymce-rails'
gem 'tinymce-rails-langs'
gem 'tinymce-rails-imageupload', '~> 4.0.17.beta'

# Stripe
gem 'stripe'

# Translate rails
gem 'rails-i18n', '~> 4.0.0' # For 4.0.x

# Session Store (fix error: ActionDispatch::Cookies::CookieOverflow)
gem 'activerecord-session_store', github: 'rails/activerecord-session_store'

# Bootstrap Calendar
gem 'momentjs-rails', '>= 2.9.0'
gem 'bootstrap3-datetimepicker-rails', '~> 4.17.43'

# Validation date
gem 'date_validator'

# Pagination
gem 'will_paginate', '~> 3.0.6'

# Countries
gem 'country_select'

# CSS in Mailer
gem 'premailer-rails'
gem 'nokogiri'

# Geocoder
gem 'geocoder'

# Country iso codes
gem 'iso_country_codes'

# logging
gem 'airbrake', '~> 5.4'

gem "getresponse", :require => "get_response"

# Any of
gem 'activerecord_any_of'

# Alternative to ActiveRecord to connect to Radius database
gem 'sequel'

gem "facets", require: false
gem 'newrelic_rpm'
gem 'resque', require: 'resque/server'
gem 'useragent'
gem 'excelinator'
gem "paranoia", "~> 2.2"
gem "http"
gem 'countries'
gem 'fedex', git: 'https://github.com/rubyco/fedex'
gem 'slack-notifier'
gem 'stripe-i18n'
gem 'friendly_id', '~> 5.2.1'

group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.1.2'
  gem 'rspec-rails', '~> 3.5'
  gem 'factory_girl_rails'
end

group :development do
  gem 'quiet_assets'
  gem 'pry-rails'
  gem 'guard-rspec', require: false
  gem 'letter_opener'
end

group :test do
  gem "database_cleaner"
  gem "launchy"
  gem 'faker'
end

group :production do
  # For Heroku
  gem 'rails_12factor'
  gem 'rails_log_stdout',           github: 'heroku/rails_log_stdout'
  gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
end
