**Postgresql Authentcation Error**

**Problem**

Recently my Windows 10 machine has been erroring out when trying to run database commands for Rails apps configured with postgresql. When the commands are run an error message is presented that says a password was not
provided for authentication with postgresql, therefore it won't perform the commands. This means that I cannot test any of my models and virtually makes my Rails app useless. I could configure some of these apps with sqlite3, which is more Windows friendly, instead of postgresql but some of my apps are deployed to Heroku which only works with postgresql.
