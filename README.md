# BasketBall Scoreboard
 
### Technologies
- RoR
- Angular 1.5

### Package Managers
- ruby gem
- bundler gem, you can install by running `gem install bundler`
- bower

### Directories
- angular code: app/assets/javascripts/angular
- bower library: vendor/assets/bower_components

### How to start?
##### prerequisite
- rbenv and ruby
- bower

##### setup project
- go to root directory
- run `bower install`

##### heroku
  since we are using bower and rails, we have to setup Heroku multiple build packs by using this command
```
heroku config:add BUILDPACK_URL=https://github.com/heroku/heroku-buildpack-nodejs
heroku config:add BUILDPACK_URL=https://github.com/heroku/heroku-buildpack-ruby
```

 
