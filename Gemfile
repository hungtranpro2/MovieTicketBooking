source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.6.3"

gem "rails", "~> 6.0.2", ">= 6.0.2.1"

gem "bcrypt", "3.1.12"

gem 'rails-i18n'

gem "sqlite3", "~> 1.4"

gem "puma", "~> 4.1"

gem "sass-rails", ">= 6"

gem "webpacker", "~> 4.0"

gem "turbolinks", "~> 5"

gem "jbuilder", "~> 2.7"

gem "bootsnap", ">= 1.4.2", require: false

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :development, :test do
  gem "rubocop", "~> 0.74.0", require: false
  gem "rubocop-rails", "~> 2.3.2", require: false
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
