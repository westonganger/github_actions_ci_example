source "https://rubygems.org"

gem "rake"
gem "minitest"
gem 'minitest-reporters'

if RUBY_VERSION.to_f >= 2.4
  gem 'warning'
end

if (RUBY_VERSION.to_f < 2.5 || false) ### set to true if locally testing old Rails version
  #gem 'rails', '~> 5.0.7'
  #gem 'rails', '~> 5.1.7'
  gem 'rails', "~> 5.2.4"
  gem 'sqlite3', '~> 1.3.6'
else
  #gem 'rails', '~> 6.0.3'
  #gem 'rails', '~> 6.1.1'
  gem 'rails'
  gem 'sqlite3'
end
