source 'http://rubygems.org'
ruby '2.4.0'

gem 'sinatra'
gem 'activerecord', :require => 'active_record'
gem 'sinatra-activerecord', :require => 'sinatra/activerecord'
gem 'rake'
gem 'require_all'
gem 'thin'
gem 'shotgun'
gem 'puma'
gem 'pry', :group => 'development'
gem 'rack-flash3'
gem 'sinatra-redirect-with-flash'
gem 'bcrypt'
gem "tux"
gem 'figaro'

group :development do
  gem 'sqlite3'
end

group :production do
  gem 'pg'
  gem "activerecord-postgresql-adapter"
end

group :test do
  gem 'rspec'
  gem 'capybara'
  gem 'rack-test'
  gem 'database_cleaner', git: 'https://github.com/bmabey/database_cleaner.git'
end
