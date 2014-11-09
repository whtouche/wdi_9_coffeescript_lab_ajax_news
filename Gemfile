source 'https://rubygems.org'

# Base gems added by `rails new`

gem 'rails', '4.1.4'

gem 'pg'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'spring', group: :development

# Additional gems for this project

gem 'devise'
gem 'validate_url'

group :development do
  # Generates source mapped files
  # Tells browser "here is original coffeescript that JS was compiled from"
  # Shows line-by-line coffee to js
  # Lets you line by line debug coffeescript instead of writing coffee and debugging js
  gem 'coffee-rails-source-maps'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'rspec-rails'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'faker'
  gem 'launchy'
  gem 'poltergeist'
  gem 'shoulda-matchers'
end

group :production do
  gem 'rails_12factor'
end
