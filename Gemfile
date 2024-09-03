# frozen_string_literal: true

source 'https://rubygems.org'
gemspec

group :development, :test do
  gem 'kramdown'
  gem 'yard'

  if RUBY_VERSION >= '2.7'
    gem 'rubocop', '1.66.0'
    gem 'rubocop-minitest', '0.36.0'
    gem 'rubocop-packaging', '0.5.2'
    gem 'rubocop-performance', '1.21.1'
  end
end

group :test do
  gem 'rake'
  gem 'simplecov'
  gem 'minitest'
  gem 'timecop'
  gem 'webmock'
end

group :profile do
  gem 'memory_profiler'
  gem 'ruby-prof', platforms: :ruby
end
