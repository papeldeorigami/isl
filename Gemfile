source :rubygems
ruby "1.8.7"

gem 'rails','2.3.11'
gem 'i18n','0.4.2'
gem 'declarative_authorization','0.5.1'
gem 'searchlogic','2.4.27'
# gem 'mysql','2.8.1'
gem 'rake','0.8.7'

group :production do
  gem 'activerecord-postgresql-adapter'
end

group :development do
  gem 'taps', :require => false # has an sqlite dependency, which heroku hates
  gem 'test-unit', '1.2.3'
  gem 'rspec'
  gem 'sqlite3'
end

