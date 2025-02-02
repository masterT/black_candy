source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.1.0'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1.3'
# Use Puma as the app server
gem 'puma', '~> 4.3.1'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.1.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.9.1'
# Get meta data from audio file
gem 'wahwah', '~> 1.1.1'
# Use sidekiq for backgroud job
gem 'sidekiq', '~> 6.1.2'
# Install turbo on rails
gem 'turbo-rails'
# Pagination
gem 'pagy', '~> 3.5.0'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
# For image attachment
gem 'carrierwave', '~> 2.0'
# For API request
gem 'httparty', '~> 0.17.0'
# For browser detection
gem 'browser', '~> 2.6.1', require: 'browser/browser'
# For PostgreSQL's full text search
gem 'pg_search', '~> 2.3.2'
# For sortable list
gem 'acts_as_list', '~> 1.0.2'
# For authentication
gem 'authlogic', '~> 6.4.1'
gem 'bcrypt', '~> 3.1.11'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rubocop', '~> 1.3.0', require: false
  gem 'rubocop-rails', '~> 2.8.0', require: false
  gem 'rubocop-performance', '~> 1.8.0', require: false
  gem 'rubocop-minitest', '~> 0.10.0', require: false
  # Security vulnerability scanner
  gem 'brakeman', '~> 4.7.2', require: false
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Memory profiler for ruby
  gem 'memory_profiler', '~> 0.9.13', require: false
  # Help to kill N+1 queries and unused eager loading
  gem 'bullet', '~> 6.1.2'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 3.35.0'
  gem 'selenium-webdriver', '~> 3.142.6'
  gem 'webdrivers', '~> 4.6.0'
  gem 'webmock', '~> 3.13.0', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
