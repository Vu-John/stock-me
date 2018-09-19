# Stock-Me

A multi-user stock tracking application that allows users to keep a list of their stocks. Users are also able to add friends and see what stocks they are keeping track of.

![stock-me](https://user-images.githubusercontent.com/15070059/45768320-93ca3e80-bc0a-11e8-9c1a-f0e258ef7415.png)

## Getting Started

### Installing

Make sure you have [Ruby](https://www.ruby-lang.org) and [Bundler](http://bundler.io) installed.

```sh
git@github.com:Vu-John/stock-me.git # or clone your own fork
cd stock-me
bundle install
rails db:migrate
rails s
```
Open up http://localhost:3000

### Deploying to Heroku

Make sure you have [Heroku Toolbelt](https://toolbelt.heroku.com/) installed

```sh
heroku create <name_of_application>
git push heroku master
heroku run rails db:migrate
heroku open
```

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Built With

* [Ruby 2.5.1](https://www.ruby-lang.org/en/news/2018/03/28/ruby-2-5-1-released/)
* [Rails 5.2.1](https://rubygems.org/gems/rails/versions/5.2.1)
