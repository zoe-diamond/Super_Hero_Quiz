source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '>= 3.2'

# --- Rails 8 ---------------------------------------------------------------
gem 'rails', '~> 8.0'

# --- Database --------------------------------------------------------------
gem 'sqlite3', '>= 2.1'

# --- App server / boot -----------------------------------------------------
gem 'puma', '>= 6.0'
gem 'bootsnap', require: false

# --- Asset pipeline (Sprockets + SCSS, matches the existing app layout) ----
gem 'sprockets-rails'
gem 'sassc-rails'

# --- App-specific gems -----------------------------------------------------
gem 'bootstrap', '~> 5.3'
gem 'jbuilder'
gem 'faker'

# --- Windows zoneinfo ------------------------------------------------------
gem 'tzinfo-data', platforms: [:windows, :jruby]

group :development, :test do
  gem 'debug', platforms: [:mri, :windows]
end

group :development do
  gem 'web-console'
  gem 'listen'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
end
