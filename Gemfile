source 'https://rubygems.org'

ruby '1.9.3', engine: 'jruby', engine_version: '1.7.4'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'activerecord-jdbcsqlite3-adapter', require: false
gem 'activerecord-jdbcmysql-adapter', require: false
gem 'activerecord-jdbcpostgresql-adapter', require: false
gem 'devise', require: false
gem 'cancan', require: false
gem 'kaminari', require: false

gem 'jruby-openssl', require: false

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3', require: false
  gem 'coffee-rails', '~> 3.2.1', require: false

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyrhino' , '~> 2.0.2', require: false
  gem 'bootstrap-sass', '~> 2.3.2.0', require: false
  gem 'uglifier', '>= 1.0.3', require: false
end

gem 'jquery-rails', require: false
gem 'jquery-ui-rails', '~> 4.0.3', require: false

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

# the javascript engine for execjs gem
platforms :jruby do
  group :assets do
    gem 'therubyrhino' , '~> 2.0.2', require: false
  end
end
