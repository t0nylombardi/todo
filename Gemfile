source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

gem 'rails', '~> 6.0', '>= 6.0.3.1'
gem 'sqlite3'
gem 'puma', '~> 4.3', '>= 4.3.5'
gem 'sassc-rails', '~> 2.1', '>= 2.1.2'
gem 'uglifier', '~> 4.2'
gem 'coffee-rails', '~> 5.0'
gem 'turbolinks', '~> 5.2', '>= 5.2.1'
gem 'jbuilder', '~> 2.10'
gem 'haml-rails'
gem 'bootsnap', '~> 1.4', '>= 1.4.6'
gem 'devise', '~> 4.7', '>= 4.7.3'
gem 'sass-rails'
gem 'bulma-rails', '~> 0.9.1'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'listen', '~> 3.2', '>= 3.2.1'
  gem 'web-console', '~> 4.0', '>= 4.0.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0', '>= 2.0.1'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 3.32', '>= 3.32.2'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
  gem 'database_cleaner'
  gem 'factory_bot_rails'
end


gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
