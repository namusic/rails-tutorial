# Sample application made by RoR tutorial

This is sample application made by below material.

[Ruby on rails tutorial](https://railstutorial.jp/)
Author : [Michael Hartl](http://www.michaekhartl.com/)

## Licence

Source code in [Ruby on rails tutorial](https://railstutorial.jp/) is opened based on MIT license anns Beerware license.
For details, see [LICENSE.md](LICENSE.md)

## How to use
To use this application, clone your local machine this repositry.
And instaii RubyGems(this command needs to use this)

```
$ bundle install --without production
```

Next, execute migration to database.

```
$ rails db:migrate
```

Last, check whether work this application well to execute test.

```
$ rails test
```

If this test passed well, you should boot rails server.

```
$ rails server
```

For details, see [Ruby on Rails tutorial](https://railstutorial.jp/)
