source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.3'
gem 'sqlite3'
gem 'puma', '~> 3.0'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'rspec', '~> 2.14', '>= 2.14.1'
end

group :test do
	gem 'factory_girl_rails', '~> 4.0'
	gem 'shoulda-matchers', '~> 3.1'
	gem 'faker'
	gem 'database_cleaner'
end

group :development do
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
