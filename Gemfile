source 'https://rubygems.org'

gem "app", path: "components/app"

#Ensuring correct version of transitive dependency
gem "trueskill", git: "https://github.com/benjaminleesmith/trueskill", ref: "e404f45af5b3fb86982881ce064a9c764cc6a901"

gem 'rails', '4.1.9'
gem 'sqlite3'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

group :development, :test do
  gem 'spring'
  gem 'rspec-rails'
  gem 'capybara'
end

group :production do
  gem 'pg'
end