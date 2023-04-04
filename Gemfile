source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.5'

group :development, :test do
  gem "heroku_hatchet"
  gem "rspec-core"
  gem "rspec-expectations"
  gem "excon", ">= 0.71.0"
  gem "rake", ">= 12.3.3"
  gem "parallel_tests"
  gem 'rspec-retry'
  gem "netrc"
  gem "git", github: "hone/ruby-git", branch: "master"
  gem 'json', '~> 2.3.0'
  gem 'ci-queue'
  gem 'redis'
end
