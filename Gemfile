source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# Split into groups
	group :development do
	  gem 'better_errors' # Better error page
	  gem 'binding_of_caller' # Adds functionality to better_errors
	  gem 'meta_request'  # Works with RailsPanel in Chrome (Add RailsPanel from google store)
	end

	group :development, :test do
	  gem 'sqlite3'
	  gem 'rspec-rails', '2.13.1'  #access to RSpec generators
	end

	group :test do
		gem 'selenium-webdriver', '2.35.1'  # capybara dependency
		gem 'capybara', '2.1.0' #Simulate users BEHAVIOR.
		gem 'spork-rails', '4.0.0'  # To Speed up RSpec
		gem 'factory_girl_rails', '4.2.0'  #Factory to generate data
	end

	group :production do
		# gem 'pg', '0.15.1'             # This is for postGres
		# gem 'rails_12factor', '0.0.2'  # ?dependency for postGres
	end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# Mobile First Responsive Design
gem 'foundation-rails'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end


# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

