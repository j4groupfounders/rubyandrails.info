source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "bcrypt", "~> 3.1.7"
gem "bootsnap", require: false
gem "cssbundling-rails"
gem "image_processing", "~> 1.2"
gem "jbuilder"
gem "jsbundling-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.6"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "view_component", "~> 3.0"
gem 'acts-as-taggable-on', '~> 11.0'
gem 'devise', '~> 4.9', '>= 4.9.4'
gem 'friendly_id', '~> 5.4.0'
gem 'meta-tags'
gem 'pagy'
gem 'rack-canonical-host'
gem 'rails', '~> 7.2.0'
gem 'sd_notify', '~> 0.1.1'
gem 'sitemap_generator'
gem 'pundit'
gem 'phlex-rails', '~> 1.2'
gem 'rorvswild'

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem 'faker'
  # gem "rails_live_reload"
  gem "dotenv-rails", "~> 2.7"

  gem "lookbook", ">= 2.0.5"
end

group :development do
  gem "web-console"
  gem 'annotate'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end

# Admin
gem "avo", "~> 2.53"

# Search
gem "ransack", "~> 4.2"
