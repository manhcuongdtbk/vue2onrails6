source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.6.1"

gem "bootsnap", ">= 1.4.2", require: false
gem "image_processing", "~> 1.2"
gem "jbuilder", "~> 2.7"
gem "mysql2", ">= 0.4.4"
gem "puma", "~> 3.11"
gem "rails", "~> 6.0.0"
gem "sass-rails", "~> 5"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 4.0"

group :development, :test do
  gem "awesome_print"
  gem "pry-coolline"
  gem "pry-rails"
  gem "rubocop", require: false
  gem "rubocop-performance"
  gem "rubocop-rails"
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

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
