source "https://rubygems.org"

group :test, optional: true do
    gem 'rake', '~> 10.1.1'
    gem 'rspec'
    gem 'rdoc'
    gem 'pry'
    gem 'addressable', '~> 2.3.8'
    gem 'webmock', RUBY_VERSION <= '1.9.3' ? '2.3.2': '>2.3.2'
end

group :coverage, optional: true do
    gem 'simplecov'
    gem 'coveralls'
end

group :sidekiq, optional: true do
    gem 'sidekiq', '~> 5.0.4'
end

gemspec
