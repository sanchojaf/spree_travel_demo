SUMMARY
-------

Applications proyect that have base on spree_travel gem

Installation
------------

You can install these gems using this command:

```shell
bundle install
```

Use the install generator to set up Spree:

```shell
rails g spree:install --sample=false --seed=false
```

At this point, if you are using spree_auth_devise you will need to change this
line in `config/initializers/spree.rb`:

```ruby
Spree.user_class = "Spree::LegacyUser"
```

To this:

```ruby
Spree.user_class = "Spree::User"
```

You can avoid running migrations or generating seed and sample data by passing
in these flags:

```shell
rails g spree:install --migrate=false --sample=false --seed=false
```

You can always perform the steps later by using these commands.

```shell
bundle exec rake railties:install:migrations
bundle exec rake db:migrate
bundle exec rake db:seed
bundle exec rake spree_sample:load
```

Browse Store
------------

http://localhost:nnnn

Browse Admin Interface
----------------------

http://localhost:nnnn/admin


Contributing
------------

Spree is an open source project and we encourage contributions. Please see the
[contributors guidelines](http://spreecommerce.com/documentation/contributing_to_spree.html)
before contributing.


