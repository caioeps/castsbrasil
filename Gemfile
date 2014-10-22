source 'http://rubygems.org'

ruby "2.1.2"

gem 'rails', '4.1.6'

gem 'cancancan'
gem 'cocoon'
gem 'devise'
gem 'omniauth-github'
gem 'responders'
gem 'rolify'
gem 'sass-rails', '5.0.0.beta1'
gem 'simple_form', '>= 3.1.0.rc1'
gem 'therubyracer'
gem 'uglifier', '>= 1.3.0'
gem 'statesman', '~> 0.8.3'

group :test do
  gem 'capybara'
  gem 'coveralls', require: false
  gem 'database_cleaner'
  gem 'jazz_hands', github: 'nixme/jazz_hands', branch: 'bring-your-own-debugger'
  gem 'nyan-cat-formatter'
  gem 'rspec-rails'
  gem 'poltergeist'
  gem 'shoulda-matchers', require: false
  gem 'spring-commands-rspec'
end

group :development do
  gem 'letter_opener'
  gem 'brakeman', require: false
  gem 'bullet'
  gem 'better_errors'
end

group :development, :test do
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'factory_girl_rails'
  gem 'guard-rspec'
  gem 'sqlite3'
  gem 'dotenv-rails'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
