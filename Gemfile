source "https://rubygems.org"

gem "rails", "4.2.6"
gem "unicorn", "~> 5.1.0"
gem "logstasher", "0.6.2"
gem "database_cleaner"
gem "deprecated_columns"
group :development, :test do
  gem "sqlite3" # Remove this when you choose a production database
  gem "factory_girl_rails", "4.7.0"
  gem "timecop"
  gem "webmock", require: false
  gem "rspec-rails", "~> 3.4"
  gem "byebug" # Comes standard with Rails
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem "web-console", "~> 2.0"
end
