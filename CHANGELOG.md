## v2.8.0
- Bumped sidekiq dependancy to version 3.0.0

## v2.7.0
- Use mock_redis when testing in fake mode
- Replace minitest with rspec
- Add codeclimate badge
- Update travis with redis-server

## v2.6.5
- via @sax - possibility to set which arguments should be counted as unique - https://github.com/form26/sidekiq-unique-jobs/pull/12
- via @eduardosasso - possibility to set which arguments should be counted as unique - https://github.com/form26/sidekiq-unique-jobs/pull/11
- via @KensoDev - configuration of default expiration - https://github.com/form26/sidekiq-unique-jobs/pull/9

## v2.1.0

Extracted the unique jobs portion from sidekiq main repo since @mperham dropped support for it.