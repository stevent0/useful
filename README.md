# useful

## Start sidekiq
```
export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES
TZ=America/Los_Angeles SIDEKIQ_COUNT=2 bundle exec sidekiqswarm
```

## Clear sidekiq job queue
Run in rails console:
`Sidekiq.redis { |conn| conn.flushdb }`

## Kill rails server
`kill -9 $(lsof -i tcp:3000 -t)`

# api

## Crontab
[https://crontab.guru/](https://crontab.guru/)

## Receive webhooks on localhost
[https://www.ultrahook.com/](https://www.ultrahook.com/)

## Ember computed properties
[https://api.emberjs.com/ember/4.7/modules/@ember%2Fobject](https://api.emberjs.com/ember/4.7/modules/@ember%2Fobject)

## Ember template helpers
[https://api.emberjs.com/ember/4.9/classes/Ember.Templates.helpers/methods/get?anchor=get](https://api.emberjs.com/ember/4.9/classes/Ember.Templates.helpers/methods/get?anchor=get)

## qunit DOM assertions
[https://github.com/mainmatter/qunit-dom/blob/master/API.md](https://github.com/mainmatter/qunit-dom/blob/master/API.md)

## ember test helpers
[https://github.com/emberjs/ember-test-helpers/blob/master/API.md](https://github.com/emberjs/ember-test-helpers/blob/master/API.md)

## ember route lifecycle
[https://gist.github.com/Andrew-Max/305483febc3c367dbf57](https://gist.github.com/Andrew-Max/305483febc3c367dbf57)
