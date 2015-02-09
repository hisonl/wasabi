source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end


# view
gem 'slim-rails'
gem 'active_link_to'
gem 'bootstrap-sass'
gem 'font-awesome-rails'

# CSS Support
# gem 'less-rails'

# form Builders
gem 'simple_form'

# turbolinks support
gem 'jquery-turbolinks'

# Pagenation
gem 'kaminari'

# HTML Parser
gem 'nokogiri'

# App Server
gem 'unicorn'

# settings
gem 'dotenv-rails'
gem 'settingslogic'

# DB
gem 'mysql2'
gem 'activerecord-mysql-unsigned'
gem 'pg'

# uploader
gem 'carrierwave'
gem 'fog'
gem 'aws-sdk'

# pagination
gem 'kaminari'

group :development, :test do
  # pry
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-stack_explorer'
  gem 'pry-coolline'
  gem 'pry-byebug'
  gem 'awesome_print'

  # hirb
  gem 'hirb'
  gem 'hirb-unicode'

  # rspec
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'rubocop'
  gem 'better_errors'
end

group :development do
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-bundler'
  gem 'guard-rubocop'
  gem 'guard-livereload', require: false
  gem 'terminal-notifier-guard'
  gem 'html2slim'
  gem 'bullet'
end

group :test do
  gem 'faker'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'selenium-webdriver'
  gem 'simplecov'
  gem 'webmock'
  gem 'simplecov-rcov'
  gem 'rspec-json_matcher'
end

group :production, :staging do
  # for Heroku
  gem 'rails_12factor'
end

gem 'devise'
gem 'cancancan'