source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use sqlite3 as the database for Active Record
# >>> midified Ruby-0.9.1.pdf P29-P30
#gem 'sqlite3'
group :development do
  gem 'sqlite3', '1.3.8'
end

# >>> added:1 start (http://qiita.com/Wmrfreew/items/80b4355868461a5b3e34)
group :assets do
gem 'sprockets-rails', :git => 'https://github.com/rails/sprockets-rails.git'

# Use SCSS for stylesheets
# >>> midified Ruby-0.9.1.pdf P29-P30
#gem 'sass-rails', '~> 4.0.0'
gem 'sass-rails', '~> 4.0.0', :git => 'https://github.com/rails/sass-rails.git'

# Use Uglifier as compressor for JavaScript assets
# >>> midified Ruby-0.9.1.pdf P29-P30
#gem 'uglifier', '>= 1.3.0'
gem 'uglifier', '2.1.1'

# Use CoffeeScript for .js.coffee assets and views
# >>> midified Ruby-0.9.1.pdf P29-P30
#gem 'coffee-rails', '~> 4.0.0'
gem 'coffee-rails', '~> 4.0.0', :git => 'https://github.com/rails/coffee-rails.git'

# >>> added:1 end
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
# >>> midified Ruby-0.9.1.pdf P29-P30
#gem 'jquery-rails'
gem 'jquery-rails', '3.0.4'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
