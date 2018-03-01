Url Shortener Rspec Assessment
===============================


1) Bundle install all gems
```
$ bundle install
```


2) Create database
```
$ bundle exec rake db:create
$ bundle exec rake db:migrate
```


3) Open a new terminal and execute Guard:
```
$ bundle exec guard
```

## Guard
This project uses `guard` and `guard-rspec`. In your terminal, run:

    $ bundle exec guard

and it will show something like the following:

    21:23:55 - INFO - Guard::RSpec is running
    21:23:55 - INFO - Guard is now watching at 'xxx'
    [1] guard(main)>

Whenever you save a file, `guard` will automatically run your tests.
