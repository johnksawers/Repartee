source 'https://rubygems.org'
ruby '2.0.0'
gem 'rails', '~>4.0'
gem 'mysql2'

gem 'bluecloth'
gem 'haml'
gem 'hominid'
gem 'devise'
gem 'cancan'
gem 'rolify'
gem 'bcrypt-ruby'
gem 'turbolinks'
gem 'responders',          github: 'plataformatec/responders'
gem 'inherited_resources', github: 'josevalim/inherited_resources'
gem 'ransack',             github: 'ernie/ransack', branch: 'rails-4'
gem 'activeadmin',         github: 'gregbell/active_admin', branch: 'rails4'
gem 'formtastic',          github: 'justinfrench/formtastic' #for adviceadmin

#assets
gem 'sass-rails'
gem 'uglifier'
gem 'jquery-rails'
gem 'bootstrap-sass'
gem 'haml-rails'
gem 'coffee-rails', '~> 4.0.0'
gem 'quiet_assets'
gem 'letter_opener'

group :development do
  gem 'powder'
end

group :test, :development do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
end

group :test do
  gem 'email_spec'
  gem 'cucumber-rails', :require => false
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'simplecov'
end

group :production do
  gem 'pg'
  gem 'thin'
end