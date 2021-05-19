source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Adding a comment

gem 'rails', '~> 5.1.3'
gem 'puma', '~> 4.3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootstrap', '~> 4.3', '>= 4.3.1'
gem 'jquery-rails'

group :development, :test do
 
	 gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
	 gem 'capybara', '~> 2.13'
	 gem 'selenium-webdriver'
	 gem 'sqlite3', '< 1.4'
end

group :production do 
	gem 'pg', '~> 1.0'
	gem 'rails_12factor'
end


group :development do
 
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
