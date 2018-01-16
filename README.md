Redmine Database Obfuscator
=====================

This tool performs obfuscating Redmine database.
All sensitive records will be depersonalized by Faker gem.

How to use
----------

- Clone project https://github.com/DmitryKa/redmine-db-obfuscator.git
- Run `bundle install`
- Copy config/database.yml.example to config/database.yml
- Clone database to another and set credentials to config/database.yml.
- __IMPORTANT: DO NOT RUN SCRIPT ON LIVE DATABASE! ALL DATA WILL BE LOST!__
- Run `bundle exec bin/obfuscate`
- Now you have depersonalized Redmine database
