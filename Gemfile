source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

ruby '2.7.6'

gem 'rails', '~> 6.0.3', '>= 6.0.3.3'

gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.7'
gem 'responders', '~> 3.0'

# Auth
gem 'devise_token_auth', '~> 1.2.0'

# Cors
gem 'rack-cors', '~> 1.1.1'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
