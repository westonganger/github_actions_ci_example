source "https://rubygems.org"

gemspec

gem "rake"
gem "minitest"
gem 'minitest-reporters'

if RUBY_VERSION.to_f >= 2.4
  gem 'warning'
end

if RUBY_VERSION.to_f < 2.5
  gem 'rails', "5.2"
  gem 'sqlite3', '~> 1.3.6'
else
  gem 'rails'
  gem 'sqlite3'
end
