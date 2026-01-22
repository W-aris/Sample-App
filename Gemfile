source "https://rubygems.org"

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# ----------------------------
# Core framework
# ----------------------------
gem "rails", "~> 7.0.3"
gem "bcrypt", "~> 3.1.7"

# ----------------------------
# Asset pipeline + Sass
# ----------------------------
gem "sprockets-rails", "~> 3.5"
gem "sassc-rails"
gem "bootstrap-sass", "3.4.1"

# Pagination
gem "will_paginate", "3.3.1"
gem "bootstrap-will_paginate", "1.0.0"

# ----------------------------
# Database
# ----------------------------
gem "sqlite3", "~> 1.4"

# ----------------------------
# Web server
# ----------------------------
gem "puma", "~> 5.0"

# ----------------------------
# JavaScript (Rails 7 defaults)
# ----------------------------
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"

# ----------------------------
# JSON APIs
# ----------------------------
gem "jbuilder"

# ----------------------------
# Performance
# ----------------------------
gem "bootsnap", require: false

# ----------------------------
# Timezone support (Windows)
# ----------------------------
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

# ----------------------------
# Development & Test
# ----------------------------
group :development, :test do
  gem "faker", "2.21.0"
  gem "debug", platforms: %i[mri mingw x64_mingw]
end

# ----------------------------
# Development only
# ----------------------------
group :development do
  gem "web-console"
end

# ----------------------------
# Test only
# ----------------------------
group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
