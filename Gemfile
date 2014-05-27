source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.0'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt-ruby'
# Use sqlite3 as the database for Active Record
# gem 'sqlite3'

group :development, :test do
	gem 'sqlite3'
	gem 'rspec-rails'
	gem 'guard-rspec'

	gem 'spork-rails'
  	gem 'guard-spork'
  	gem 'childprocess'
end

gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'


gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'


gem 'spring',        group: :development

group :test do
	gem 'selenium-webdriver'
	gem 'capybara'
	gem 'libnotify'
end

group :production do
  gem 'rails_12factor'
  gem 'pg'
end

group :doc do
  gem 'sdoc', '~> 0.4.0', require: false
end