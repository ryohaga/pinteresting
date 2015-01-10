source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.1.8'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0'          
gem 'bootstrap-sass'
gem 'devise', '~> 3.4.1' # ~> can accept upgraded version
gem 'paperclip'

group :development, :test do
	gem 'sqlite3'
end

group :production do
	gem 'pg'
	gem 'rails_12factor' # Need this to put it onto heroku
end

group :doc do

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
	gem 'tzinfo-data', platforms: [:mingw, :mswin]
end