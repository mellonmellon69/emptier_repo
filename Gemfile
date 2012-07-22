source 'http://rubygems.org'

gem 'rails', '3.2.6'

gem 'pg'
gem 'jquery-rails'
gem 'haml'
gem 'therubyracer'

# payments
gem 'stripe'

# helpers for adding FKs in migrations
gem 'foreigner'

# error messages when not using formtastic
gem 'dynamic_form'

# updates notifications and mailing in the backgroundo
# Using this because on the main branch, resque-retry will enqueue jobs twice, See #6149 (our redmine)
gem "resque", :github => 'defunkt/resque'
gem 'resque-scheduler', :require => 'resque_scheduler'
gem 'resque-retry', :github => 'lantins/resque-retry'
gem "resque_mailer"

gem "formtastic"
gem "inherited_resources"
gem 'activeadmin'
gem 'paperclip'

gem 'yajl-ruby' # JSON handling
gem 'rack-ssl'
gem 'validate_url'
gem 'email_validator'
gem 'devise'

# user password encryption
gem "bcrypt-ruby", :require => "bcrypt"

# natural language date/time parser
gem 'chronic'

# Unicorn server
gem 'unicorn'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'immigrant' # find out relations without FKs
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'faker'

  # deoploying
  gem 'capistrano-helpers'
  gem 'rvm-capistrano'

  gem 'annotator' # rake annotate
  gem 'thin'  # use thin instead of webrick in development (webrick throws some warnings on 1.9.3)
end

group :test do
  gem 'database_cleaner'
  gem 'delorean'
  gem 'shoulda'
  gem 'launchy'
  gem 'steak'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'selenium-client'
  gem 'selenium-webdriver'
  gem 'autotest'
  gem 'autotest-growl'
  gem 'fuubar'
  gem 'watchr'
  gem 'rspec-set'
end
