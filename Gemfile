source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.4'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.6'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 3.2.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'duktape'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'jquery-rails', '4.3.1'
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7.0'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
gem 'devise', '~> 4.4.3'
gem 'bootstrap-sass', '~>3.3.7'
gem 'acts_as_votable', '~> 0.11.1'
gem 'simple_form', '~> 4.0.1'
gem 'record_tag_helper', '~> 1.0'
gem 'punching_bag', '~> 0.6.0'
gem 'omniauth-google-oauth2', '~> 0.5.3'
gem 'activerecord-session_store', '~> 1.1', '>= 1.1.1'

group :development, :test do
  gem 'sqlite3','~>1.3.13'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.5.1'
  gem 'listen','~>3.1.5'
  gem 'spring','~>2.0.2'
  gem 'spring-watcher-listen','~>2.0.1'
  gem 'dotenv', '~> 2.5'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15', '< 4.0'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
  gem 'rails-controller-testing','~>1.0.2'
  gem 'minitest','~>5.10.3'
  gem 'minitest-reporters','~>1.1.14'
  gem 'guard','~>2.13.0'
  gem 'guard-minitest','~>2.4.4'
end

group :production do
  gem 'rails_12factor', '~> 0.0.3'
  gem 'pg', '0.18.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]