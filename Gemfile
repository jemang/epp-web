source 'https://rubygems.org'

# core
gem 'rails', '~> 5.2.5'

# load env
gem 'figaro', '~> 1.1.1'

# style
gem 'sass-rails', '~> 5.0.4'       # sass style
gem 'bootstrap-sass', '~> 3.3.4.1' # bootstrap style

# js
gem 'uglifier',     '~> 2.7.2'     # minifies js
gem 'coffee-rails', '~> 4.2'     # coffeescript support
gem 'jquery-rails'     # jquery
gem 'turbolinks', '~> 5'
gem 'therubyracer', '~> 0.12.2', platforms: :ruby

gem 'epp', '1.5.0', git: 'https://github.com/localhostmy/epp'
gem 'epp-xml', git: 'https://github.com/localhostmy/epp-xml'
gem 'uuidtools', '~> 2.1.4' # For unique IDs (used by the epp gem)

gem 'nokogiri'

gem 'countries', '~> 1.2.5'

gem 'coderay', '~> 1.1.1'   # xml console visualize

gem 'kaminari',        '~> 0.16.3'  # pagination

gem 'slim-rails'
gem 'haml-rails'

group :development do
  # dev tools
  gem 'spring'
  gem 'unicorn'
  gem 'rubocop'
  gem 'guard-rubocop',         '~> 1.1.0'

  # better errors
  gem 'better_errors', '~> 2.1.1'
  #gem 'binding_of_caller', '~> 0.7.2'

  # fast sass development
  gem 'guard-livereload', '2.5.2', require: false
  gem 'rack-livereload', '0.3.16'
end

group :development, :test do
  gem 'pry',  '~> 0.10.1'
  gem 'sdoc', '~> 0.4.0'
end
