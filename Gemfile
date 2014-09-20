source "https://rubygems.org"

# Specify your gem's dependencies in ..gemspec
gemspec

gem 'adapter_extensions', :git => 'git://github.com/activewarehouse/adapter_extensions.git'
gem 'activewarehouse-etl', :git => 'git://github.com/activewarehouse/activewarehouse-etl.git'

gem 'SystemTimer',  :platform => :mri_18

group :development do
  gem 'sqlite3'
end

group :production do
  gem 'mysql2'
end
