source 'https://rubygems.org'
gem 'rails', '3.2.6'

gem 'heroku'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end
gem 'jquery-rails'
gem "rspec-rails", :group => [:development, :test]
gem "devise" 
gem 'omniauth'
gem 'omniauth-facebook'
gem 'oauth2'

group :production do
  gem 'pg'
	gem 'thin'
end

group :test do
	gem 'sqlite3'
	gem "email_spec"
	gem "cucumber-rails", :require => false
	gem "database_cleaner"
	gem "capybara"
	gem "factory_girl_rails"
	gem "launchy"
end