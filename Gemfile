# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.5.0"

gem "rails", "~> 5.2.2", ">= 5.2.2.1"
gem "puma", "~> 3.11"
gem "sassc-rails"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.2"
gem "jbuilder", "~> 2.5"
gem "bootsnap", ">= 1.1.0", require: false
gem "config"
gem "twilio-ruby"
gem "slack-notifier"

group :development, :test do
  gem "pry-rails"
  gem "pry-byebug"
  gem "dotenv-rails"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  gem "rubocop", "~> 0.65.0", require: false
  gem "rubocop-rails_config"
  gem "rubocop-checkstyle_formatter", require: false
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
