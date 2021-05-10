source "https://rubygems.org"

gemspec

gem "rails", "~> 6.1.3"
gem "mongoid", git: "https://github.com/reidmorrison/mongoid", branch: "7.2-ruby_3"
gem "rocketjob", git: "https://github.com/rocketjob/rocketjob"
gem "rubyzip", platform: :ruby
gem "sprockets", "< 4.0"

group :test, :development do
  gem "amazing_print"
  gem "minitest"
end

group :test do
  gem "minispec-rails", require: false
  gem "rails-controller-testing"
end

group :development do
  gem 'rubocop', require: false
  gem 'rubocop-minitest', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
end
