# Run Nginx with Wasmer on Heroku

This example runs Nginx with [Wasmer](https://wasmer.io/) on Heroku.

## Running

```
heroku create APP_NAME
heroku buildpacks:set https://github.com/jingweno/heroku-buildpack-wasmer
git push heroku master
curl https://APP_NAME.herokuapp.com
```
