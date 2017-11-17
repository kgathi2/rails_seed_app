source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.4'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rack-attack'
gem 'figaro'
gem 'sidekiq'
gem 'sidekiq-cron'
gem 'sidekiq-failures'
gem 'sidekiq-unique-jobs'
gem 'sidekiq-throttler'
gem 'sinatra', require: false, git: 'https://github.com/sinatra/sinatra.git'
gem 'pry-rails'
gem 'carrierwave'
gem 'mini_magick'
gem 'ransack'
gem 'kaminari'
gem 'httparty'
gem 'dalli'
gem 'hashie'
group :development, :test do
  gem 'awesome_print'
  gem 'bullet'
  gem 'faker'
  gem 'brakeman', require: false
  gem 'rubocop', require: false
  gem 'letter_opener'
  gem 'guard-rails'
  gem 'guard-redis'
  gem 'guard-minitest', require: false
  gem 'guard-brakeman'
  gem 'guard-rubocop'
end

group :development do
  gem 'capistrano'
  gem 'capistrano-rails'
  gem 'capistrano-bundler', require: false
  gem 'rvm1-capistrano3', require: false
  gem 'capistrano-postgresql', require: false
  gem 'capistrano3-puma', require: false
  gem 'capistrano-sidekiq', require: false
end

group :test do
  gem 'minitest-reporters'
  gem 'factory_girl_rails'
  gem 'webmock'
  gem 'timecop'
  gem 'database_cleaner'
  gem 'simplecov', require: false
  gem 'shoulda'
  gem 'shoulda-matchers'
end
