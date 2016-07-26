## Heroku Buildpack for Veritrans configuration file on Rails

### Usage
- add this buildpack. `heroku buildpacks:add https://github.com/okame/heroku-buildpack-veritrans-rails.git`
- put `tg_mdk.heroku.ini` for production.
- when deploying, copy `tg_mdk.heroku.ini` to `tg_mdk.ini`
