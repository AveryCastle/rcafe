source 'https://rubygems.org'

gem 'bootstrap-sass', '~> 3.3.4.1'
gem 'simple_form', '3.1.0'
gem 'carrierwave'
gem 'mini_magick'
gem "font-awesome-rails"
gem 'acts-as-taggable-on'

# Use unicorn as the app server
gem 'unicorn'

# Use Capistrano for deployment
gem 'capistrano-rails', group: :development

# 추가할 젬
gem 'capistrano-rbenv', group: :development
gem 'capistrano-rbenv-install', group: :development
gem 'capistrano-unicorn-nginx', group: :development
gem 'capistrano-rails-console'
gem 'capistrano-rails-collection'
gem 'capistrano-rails-tail-log'

group :production do
  gem 'rb-readline'
end

# 데이터베이스 젬 그룹변경 및 추가
gem 'sqlite3', group: :development
gem 'mysql2', group: :production


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use sqlite3 as the database for Active Record
# gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

