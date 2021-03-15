# Ruby on Rails Tutorial toy application

This is the toy application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
(6th Edition)
by [Michael Hartl](https://www.michaelhartl.com/).

To view on Heroku: [Click here](https://gentle-tundra-81900.herokuapp.com/)
#### Quick routes
* ```/``` or ```/users``` -> view all users
* ```/users/new``` -> create new user
* ```/users/:id``` -> view user with id
* ```/users/:id``` -> edit user with id
* ```/microposts``` -> view all microposts
* ```/microposts/new``` -> create new micropost
* ```/microposts/:id``` -> view micropost with id
* ```/microposts/:id/edit``` -> edit micropost with id

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ gem install bundler -v 2.2.13
$ bundle _2.2.13_ config set --local without 'production'
$ bundle _2.2.13_ install
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).
