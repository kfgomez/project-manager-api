source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.1'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'bcrypt'
gem 'rack-cors', :require => 'rack/cors'
gem 'active_model_serializers', '~> 0.10.0'
gem 'will_paginate', '~> 3.1.0'
gem 'faker'

group :development, :test do
  gem 'rspec-rails'
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'shoulda-matchers', '~> 3.1'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'pry-byebug'
  gem 'byebug'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]