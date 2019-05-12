source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end



gem 'carrierwave', '~> 1.1'
gem 'devise'
gem 'fog'
gem 'rails', '~> 5.1.1'
gem 'puma', '~> 3.7'
gem 'uglifier', '>= 1.3.0'
gem 'pg', '~> 0.18'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'materialize-sass', '~> 0.96.1'

gem 'foundation-rails'
gem 'sprockets-rails'
gem 'sass-rails', '~> 5.0.0' 


gem 'active_model_serializers'
gem 'dotenv'
gem 'dotenv-rails'
gem 'jquery-rails'
gem 'rest-client'
gem 'sendgrid-ruby'
gem 'simplecov'

group :production do
  gem 'rails_12factor'
end

group :test do
  gem 'coveralls', require: false
end

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'valid_attribute'
  gem 'shoulda-matchers', require: false
end


group :development do

  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
