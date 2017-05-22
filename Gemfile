source "https://rubygems.org"
gem 'pry-byebug'

git 'https://github.com/rails/rails.git',
  # ref: '40ba03ada' do # WORKS
  ref: 'e4108fc61' do
  # ref: '5ac89b168b049' do FAILS
  #ref: 'd046390c32' do WORKS

  gem 'activerecord'
end

group :development, :test do
  gem 'spec'
  gem 'rspec', '>= 1.2.9'
  gem 'rake'
end

group :development do
  gem 'appraisal'
  gem 'simplecov', :require => false
end
