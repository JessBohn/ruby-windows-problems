**Postgresql Authentcation Error**

**Problem**

Recently my Windows 10 machine has been erroring out when trying to run database commands for Rails apps configured with postgresql. When the commands are run an error message is presented that says a password was not
provided for authentication with postgresql, therefore it won't perform the commands. This means that I cannot test any of my models and virtually makes my Rails app useless. I could configure some of these apps with sqlite3, which is more Windows friendly, instead of postgresql but some of my apps are deployed to Heroku which only works with postgresql.

**Error Message**

bohn1@DESKTOP-G7A4H9D /c/GoalMate-API (master)
$ rails db:create
fe_sendauth: no password supplied
Couldn't create database for {"adapter"=>"postgresql", "encoding"=>"unicode", "pool"=>5, "database"=>"GoalMate_development"}
rails aborted!
PG::ConnectionBad: fe_sendauth: no password supplied
bin/rails:9:in `require'
bin/rails:9:in `<main>'
Tasks: TOP => db:create
(See full trace by running task with --trace)

The error message always contains the 'no password supplied' and hash along with the rails (or rake) aborted!
