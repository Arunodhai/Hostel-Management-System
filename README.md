# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Try these lines in the console in the project folder:

gem install bundler
bundle
rake db:create && rake db:migrate
rails s

These commands will start Rails server at localhost:3000. This project requires DB to be installed. (DB type depends on Gemfile content). Also you should check if config/database.yml file is present.
