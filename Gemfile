source "https://rubygems.org"


gem "rails", "~> 7.2.1"
gem "sprockets-rails"
gem "sqlite3", ">= 1.4"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "mysql2"
gem "cssbundling-rails"

gem "tzinfo-data", platforms: %i[ windows jruby ]

gem "bootsnap", require: false

gem "whenever"

# UI/UX
gem "rails-i18n"
gem "meta-tags"
gem "slim-rails"
gem "html2slim"
gem "bootstrap", "~> 5.3.3"
gem "dartsass-sprockets"
gem "jquery-rails"

# Authentication
gem "sorcery"

# Decorator
gem "active_decorator"

# Pagination
gem "kaminari"
gem "kaminari-i18n"

group :production do
  gem "pg"
end

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "brakeman", require: false

  # Omakase Ruby styling [https://github.com/rails/rubocop-rails-omakase/]
  gem "rubocop-rails-omakase", require: false
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
end
