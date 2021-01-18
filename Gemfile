source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.6'

gem 'devise', '~> 4.7', '>= 4.7.3'
gem 'rails', '~> 5.2.4', '>= 5.2.4.4'

gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'duktape'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'sqlite3'
end

group :production do
  gem 'pg', '~> 1.2', '>= 1.2.3'
end
group :test do
  
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  
  gem 'chromedriver-helper'
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
