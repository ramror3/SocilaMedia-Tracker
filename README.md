Ruby 2.3.1

Rails 5.1.6

RVM 2.3.1

DB mysql2

gem 'devise'
gem 'twitter-bootstrap-rails', '~> 4.0'
gem 'devise-bootstrap-views', '~> 0.0.11'

rails g bootstrap:install static
rails g bootstrap:layout application
rails g devise:views:locale en
rails g devise:views:bootstrap_templates

*= require devise_bootstrap_views

