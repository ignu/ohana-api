source 'https://rubygems.org'

ruby '2.0.0'
gem 'rails', '~> 4.0'

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier', '>= 1.0.3'
end

gem 'protected_attributes'

# Front end
gem 'jquery-rails'
gem "bootstrap-sass", "~> 2.3.2.2"
#gem 'bootstrap-sass'
gem "haml-rails", ">= 0.4"

# Server for deployment
gem "passenger"

group :production, :staging do
  gem 'rails_12factor' # Heroku recommended
end

# Analytics
gem "sentry-raven", :git => "https://github.com/getsentry/raven-ruby.git"

# Test coverage
gem 'coveralls', require: false

# MongoDB ORM
gem "mongoid", ">= 4.0.0.alpha2"

group :test, :development do
  # Testing with Rspec
  gem "rspec-rails", ">= 2.12.2"
  gem "factory_girl_rails", ">= 4.2.0"
end

group :test do
  # Testing with Rspec and Mongoid
  gem "database_cleaner", ">= 1.0.0.RC1"
  gem "mongoid-rspec", ">= 1.7.0"
  gem "capybara"
end

group :development do
  # Debugging
  #gem "bullet"
  gem "quiet_assets", ">= 1.0.2"
  gem "better_errors", ">= 0.7.2"
  gem "binding_of_caller", ">= 0.7.1", :platforms => [:mri_19, :rbx]
  #gem "debugger"

  # Code quality and style
  gem "metric_fu"
end

# Geocoding
gem "geocoder", :git => "git://github.com/alexreisner/geocoder.git", :ref => "3568e5e8e6"
gem "redis"

# Format validation for URLs, phone numbers, zipcodes
gem "area"
gem "validates_formatting_of"

# CORS support
gem 'rack-cors', :require => 'rack/cors'

# API Design
gem "grape"
gem 'grape-entity'
gem "kaminari"

# Caching
#gem "garner"
gem 'dalli'
gem 'kgio'
gem 'memcachier'

# API Documentation
gem "grape-swagger", :git => "git://github.com/monfresh/grape-swagger.git", :ref => "557d38e151"
gem 'swagger-ui_rails'

# Production Monitoring
gem 'newrelic_rpm'
gem 'newrelic-grape'
gem "rack-timeout"

# Rate Limiting
gem 'rack-throttle'

# Authentication & Administration
gem 'devise'
gem 'rails_admin'
gem "cancan"
gem "attribute_normalizer"
gem "enumerize"

# App config and ENV variables for heroku
gem "figaro"

# Search
gem "tire"

# Nested categories for OpenEligibility
gem "glebtv-mongoid_nested_set"

gem 'mongoid_time_field'

gem 'mongoid_slug'
