source 'https://rubygems.org'
ruby '~> 2.7.3'

gem 'rake'
gem 'thor'
gem 'pry', '~> 0.14.0'
gem 'activesupport', '~> 5.2', require: false
gem 'yajl-ruby', require: false
gem 'html-pipeline', '>= 2.12.1'
gem 'typhoeus'
gem 'nokogiri', '>= 1.15.6'
gem 'terminal-table'

group :app do
  gem 'rack', '>= 2.2.8.1'
  gem 'sinatra', '>= 2.0.8'
  gem 'sinatra-contrib', '>= 2.0.8'
  gem 'rack-ssl-enforcer'
  gem 'thin', '>= 1.8.2'
  gem 'sprockets', '>= 3.7.3'
  gem 'sprockets-helpers', '>= 1.2.2'
  gem 'erubi'
  gem 'browser'
  gem 'sass'
  gem 'coffee-script'
  gem 'chunky_png'
  gem 'sprockets-sass'
  gem 'image_optim'
  gem 'image_optim_pack', platforms: :ruby
end

group :production do
  gem 'uglifier'
  gem 'newrelic_rpm'
end

group :development do
  gem 'better_errors', '>= 2.10.0'
end

group :docs do
  gem 'redcarpet'
  gem 'progress_bar', require: false
  gem 'unix_utils', require: false
  gem 'tty-pager', require: false
  gem 'net-sftp', '>= 2.1.3.rc2', require: false
end

group :test do
  gem 'minitest'
  gem 'rr', require: false
  gem 'rack-test', '>= 2.0.0', require: false
end

if ENV['SELENIUM'] == '1'
  gem 'capybara'
  gem 'selenium-webdriver'
end
