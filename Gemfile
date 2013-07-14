source 'https://rubygems.org'
ruby '2.0.0'
gem 'rails', '3.2.13'

group :development do 
  gem 'sqlite3'
end

group :production do 
  gem 'pg'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end
gem 'koala'
gem 'jquery-rails'
gem 'haml-rails'
gem 'omniauth', '~> 1.1.1'
gem 'omniauth-facebook', '~> 1.4.1'
group :development do
  gem 'better_errors'
  gem 'binding_of_caller'#, #:platforms=>[:mri_19, :rbx]
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'html2haml'
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rb-fchange', :require=>false
  gem 'rb-fsevent', :require=>false
  gem 'rb-inotify', :require=>false
end
group :development, :test do
  gem 'rspec-rails'
end
group :test do
  gem 'database_cleaner'
  gem 'email_spec'
end

