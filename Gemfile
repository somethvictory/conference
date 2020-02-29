source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.7'
gem 'sqlite3'
gem 'puma', '~> 3.12'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'active_model_serializers', '~> 0.10.7'
gem 'webpacker',                '~> 3.3.0'
gem 'react-rails',              '~> 2.4.4'

group :development, :test do
  gem 'pry',                    '~> 0.11.3'
  gem 'rspec-rails',            '~> 3.7'
  gem 'json_spec',              '~> 1.1.4'
  gem 'shoulda-matchers',       '~> 3.1'
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'selenium-webdriver'
  gem 'ffaker'
  gem 'phantomjs'
  gem 'capybara',               '~> 2.13'
  gem 'capybara-webkit'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
