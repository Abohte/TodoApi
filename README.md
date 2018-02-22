# To Do App

Rails app made during week 2 of the 9-week Codaisseur Academy.

This app was an exercise to learn about AJAX calls and using Rails as a JSON API. The app consists of a list of to-do items, which can be appended, crossed off and removed after completion.

## Steps

While working on this app I followed these steps:

1. Setting up project with Rails and PostgreSQL.
2. Adding Bootstrap, jQuery.
3. Updating controllers and views.
4. Adding AJAX calls.

## Running Locally

Make sure you have [Ruby](https://www.ruby-lang.org/en/) and [Bundler](http://bundler.io/) installed.

```bash
git clone git@github.com:Abohte/to-do-api.git
cd to-do-api
bundle install
rails db:create db:migrate db:seed
rails server
```
