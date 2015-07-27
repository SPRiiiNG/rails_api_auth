source 'https://rubygems.org'

gemspec

platforms :ruby, :mswin, :mingw do
  gem 'sqlite3'
end
platforms :jruby do
  gem 'jdbc-sqlite3'
  gem 'activerecord-jdbc-adapter'
end

group :development do
  gem 'guard-rubocop'
  gem 'guard-rspec', require: false
  gem 'guard-bundler', require: false
  gem 'factory_girl_rails'
end

group :test do
  gem 'appraisal'
  gem 'rspec-rails'
  gem 'shoulda'
  gem 'webmock', require: 'webmock/rspec'
  gem 'timecop'
  gem 'json_spec'
  gem 'test-unit'
end
