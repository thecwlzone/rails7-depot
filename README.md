# README

README last updated on Apr 1, 2022

My version of the Depot code used in Sam Ruby's book Agile Web Development with Rails 7,
published by The Pragmatic Programmers

* Ruby version - 3.1.1

* Rails version - 7.0.2.3

* The database was converted from the default SQLite3 to PostgreSQL in order to support a Heroku deployment at

  [https://enigmatic-escarpment-36823.herokuapp.com/](https://enigmatic-escarpment-36823.herokuapp.com/)

* Unit tests - `bin/rails test` - Pass

* System tests - Uses the Safari browser

  `bin/rails test test/system/orders_test.rb` - All tests pass

  `bin/rails test test/system/users_test.rb` - Tests fail, they have not been updated from the original scaffold creation

## Additional Notes

* The code is being updated based upon Rubocop 1.26.1 - see .rubocop.yml - this is a work in progress

[![Ruby Style Guide](https://img.shields.io/badge/code_style-rubocop-brightgreen.svg)](https://github.com/rubocop/rubocop)

* Task I - Logging In - system tests have not been updated from the original scaffold creation

* Task J: Internationalization - Not added

* Task K: Receive Emails and Respond with Rich Text - Not added

* Ruby and Rails versions will be updated as new versions are released

