source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

group :production do
  gem 'heroku'
  gem 'pg'
  # gem 'dalli'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :development, :test do
  gem 'pry'
  gem 'factory_girl_rails'
  gem 'cucumber-rails'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'jasmine'
  gem 'sqlite3'
  
  #   gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i   # Mac OS X only
  #   gem 'guard-rspec'
  #   gem 'guard-livereload'
  #   gem 'spork'
  #   gem 'guard-spork'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end
