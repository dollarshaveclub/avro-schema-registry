# frozen_string_literal: true

ruby '2.6.3'

source 'https://rubygems.org'

gem 'avro-patches'

gem 'avro-resolution_canonical_form', '>= 0.2.0'
gem 'bootsnap', require: false
gem 'grape'
gem 'ice_nine', require: 'ice_nine/core_ext/object'
gem 'pg'
gem 'private_attr', require: 'private_attr/everywhere'
gem 'procto'
gem 'puma'
gem 'rails', '~> 5.2.2'
gem 'avro_turf', '>= 0.8.0', require: false

group :test do
  gem 'json_spec'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
  gem 'simplecov'
end

group :production do
  gem 'bugsnag'
  gem 'ddtrace'
end

group :development do
  gem 'annotate'
  gem 'heroku_rails_deploy', '>= 0.4.1', require: false
  gem 'overcommit'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'spring-commands-rubocop'
  gem 'spring-watcher-listen'
end

group :development, :production do
  gem 'newrelic_rpm'
end

group :development, :test do
  gem 'dotenv-rails'
  gem 'factory_bot_rails'
  gem 'salsify_rubocop', require: false
end
