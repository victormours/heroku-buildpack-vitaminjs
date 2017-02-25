# Heroku Buildpack for vitaminjs

[vitaminjs](https://github.com/Evaneos/vitaminjs) is an awesome build framework for creating and maintaining React apps easily.

This buildpack allows you to deploy vitaminjs projects to heroku.

## Usage

From your heroku project (after running `heroku create`), run
```
$ heroku buildpacks:set https://github.com/victormours/heroku-buildpack-vitaminjs
```

And then
```
$ git push heroku master
```

And you're good to go!


Read more about vitaminjs [here](https://medium.com/@victormours/building-static-websites-happily-with-vitaminjs-8b996fa6fd37#.tpllhhtsh)
