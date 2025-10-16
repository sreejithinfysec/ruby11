source 'https://rubygems.org'

gem 'rails', '5.0.0'

gem 'coffee-rails', '~> 4.1.1'
gem 'devise', '>= 4.0.0'
gem 'jquery-rails', '>= 4.0.5'
gem 'nokogiri'
gem 'sass-rails', '~> 5.0', '>= 5.0.5'
gem 'sqlite3'
gem 'turbolinks', '>= 2.5.4'
gem 'uglifier', '>= 1.3.0'
gem 'symmetric-encryption', '~> 3.8.1'

gem 'quiet_assets', group: :development

group :development, :test do
  gem 'byebug' # Call 'byebug' in code to stop execution and get a debugger console
  gem 'capybara', '>= 2.5.0'
  # gem 'chromedriver-helper' # helps with using Chrome in feature specs
  gem 'factory_girl_rails', '~> 4.6', '>= 4.6.0'
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-rescue'
  gem 'pry-stack_explorer'
  gem 'puffing-billy'
  gem 'rspec-rails', '~> 3.5', '>= 3.5.0'
  gem 'selenium-webdriver' # used by JavaScript-dependent feature specs (`js: true`)
  gem 'spring' # Spring background-runs app in dev for speed
  gem 'spring-commands-rspec' # Enable Spring for RSpec
end

group :development do
  gem 'web-console', '~> 2.3', '>= 2.3.0' # Access IRB on error pages or by <%= console %> in views
end

group :test do
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'poltergeist' , '>= 1.7.0' # helps with using PhantomJS headless browser in feature specs
  gem 'shoulda-matchers', '3.0.1'
  gem 'vcr'
  gem 'webmock'
end
