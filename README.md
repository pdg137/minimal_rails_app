To create the app, install Ruby, then:

```
bundle
bundle exec rails new testapp
cd testapp/
bundle exec rake db:create
bundle exec rails generate model Article title:string text:text # or whatever
bundle exec rake db:migrate
```