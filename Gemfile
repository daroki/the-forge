source 'http://rubygems.org'

gem 'rails', '3.2.0'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.0'
  gem 'coffee-rails', '~> 3.2.0'
  gem 'uglifier',     '>= 1.0.3'
end

gem 'coffee-filter'
gem 'haml_coffee_assets'
gem 'execjs'

gem 'jquery-rails'

gem 'mongoid', '3.0.0.rc'
gem 'moped', '1.0.0.rc'
gem 'rails3-generators'

gem 'haml'
gem 'haml-rails'
gem 'aws-s3'
gem 'mongoid-paperclip', require: 'mongoid_paperclip'
gem 'dynamic_form'

gem 'therubyracer'

gem 'omniauth' # It's a sane default these days
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-google-oauth2'
gem 'omniauth-dwolla'

gem 'braintree'

gem 'airbrake'

group :production do
  gem 'thin'
end

group :development do
  gem 'heroku'
  gem 'taps'
  gem 'thin'
end

group :test, :development do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'mongoid-rspec'
  gem 'timecop'
  gem 'vcr'
  gem 'fakeweb'
  gem 'email_spec' 
  gem 'rack_session_access'
  gem 'pry'
  gem 'pry-nav'

  # Pretty printed test output
  gem 'turn', require: false
end

