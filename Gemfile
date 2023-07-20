source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 7.0.6'

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem 'sprockets-rails', '~> 3.4.2'

# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma', '~> 5.0'

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem 'importmap-rails', '~> 1.2.1'

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem 'turbo-rails', '~> 1.4'

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem 'stimulus-rails', '~> 1.2'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'jbuilder', '~> 2.11'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem 'kredis'

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem 'bcrypt', '~> 3.1.7'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '~> 1.16', require: false

# Use Sass to process CSS
# gem 'sassc-rails'

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem 'image_processing', '~> 1.2'

group :development, :test do
  # Query performance
  gem 'bullet', '~> 7.0.7'

  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', '~> 1.8', platforms: %i[mri mingw x64_mingw]

  # Metrics
  gem 'execution_time', '~> 0.1.4'

  # Entity creation
  gem 'factory_bot_rails', '~> 6.2'

  # Fake data generation
  gem 'faker', '~> 3.2.0'

  # Debugging
  gem 'pry-byebug', '~> 3.10.1'

  # Testing framework
  gem 'rspec-rails', '~> 6.0.0'
end

group :development do
  # Model annotations
  gem 'annotate', '~> 3.2.0', require: false

  # Controller annotations
  gem 'chusaku', '~> 0.6.1', require: false

  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'web-console', '~> 4.2'

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem 'rack-mini-profiler'

  # Performance extension for Rubocop
  gem 'rubocop-performance', '~> 1.18.0', require: false

  # Rails extension for Rubocop
  gem 'rubocop-rails', '~> 2.20.2', require: false

  # Rake extension for Rubocop
  gem 'rubocop-rake', '~> 0.6.0', require: false

  # RSpec extension for Rubocop
  gem 'rubocop-rspec', '~> 2.22.0', require: false

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem 'spring'
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem 'capybara', '3.39.2'

  # Clean database after tests
  gem 'database_cleaner', '~> 2.0'

  # Brings back assigns and assert_template
  gem 'rails-controller-testing', '~> 1.0.5'

  # Ruby bindings for Selenium
  gem 'selenium-webdriver', '~> 4.9'

  # Code coverage
  gem 'simplecov', '~> 0.22'

  # Downloads drivers and directs Selenium to use them
  gem 'webdrivers', '~> 5.2'
end
