source 'https://rubygems.org'

ruby '2.5.1'

gem 'rails', '~> 6.1', '>= 6.1.7.4'

gem 'mysql2', '~> 0.3.18'
gem 'unicorn'
gem 'jquery-rails', '>= 4.3.2'
gem 'omniauth-saml'
gem 'github-markdown', require: 'github/markdown'
gem 'protected_attributes'
gem 'sass-rails', '>= 5.0.8'
gem 'compass-rails', '>= 3.1.0'
gem 'coffee-rails', '>= 5.0.0'
gem 'uglifier'
gem 'bootstrap-sass', '~> 3.3.5.1'
gem 'font-awesome-sass-rails'
gem 'newrelic_rpm'
gem 'sentry-raven'
gem 'responders', '~> 3.0', '>= 3.0.0'
gem 'nokogiri', '1.8.2'
gem 'loofah', '2.2.2'
gem 'rails-html-sanitizer', '1.0.4'

group :development, :production do
  gem 'rails_12factor'
end

group :test, :development do
  gem 'minitest'
  gem 'rspec-rails', '~> 3.7', '>= 3.7.0'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'factory_girl_rails', '>= 4.9.0'
  gem 'faker'
  gem 'capybara'
  gem 'capybara-webkit', '1.14.0'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'letter_opener'
  gem 'timecop'
  gem 'foreman'
  gem 'fakefs', :require => 'fakefs/safe'
  gem 'dotenv-rails', '>= 2.7.6'
  gem 'pry-rails'
  gem 'byebug'
end

group :test do
  gem 'codeclimate-test-reporter', require: nil
  gem 'selenium-webdriver'
end

group :development do
  gem 'auto_tagger'
  gem 'better_errors'
  gem 'binding_of_caller'
end
