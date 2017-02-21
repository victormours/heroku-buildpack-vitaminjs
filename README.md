# Heroku Buildpack for vitaminjs

You will need to add the following to your `.vitaminrc`
```
{
  "server": {
    "host": "0.0.0.0"
  }
}
```
Then run `heroku buildpacks:set https://github.com/victormours/heroku-buildpack-vitaminjs`

And you're good to go!
