# README

This Rails 7 app was generated with the following options: 

```
rails new rails_api_demo --database=postgresql --skip-action-mailbox --skip-action-text --skip-action-cable --asset-pipeline=propshaft --skip-hotwire --skip-test --skip-system-test --javascript=esbuild --css=tailwind
```

## Try it out

Install PostgreSQL and start the database service:

```
brew install postgresql
brew services run postgresql
```

Install Ruby 3.1.2:

```
rbenv install 3.1.2
```

Run `bin/setup` once.
Start the dev server (Rails server + esbuild watcher + tailwindcss watcher) with `bin/dev`.

Visit `localhost:3000`.

--- 

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
