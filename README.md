# Heroku Multi Slugcleanup buildpack

This adds support for multiple `.slugcleanup` files in one repo, based on the [multi-procfile buildpack](https://raw.githubusercontent.com/heroku/heroku-buildpack-multi-procfile).

Add this buildpack and set `SLUGCLEANUP=config/other.slugcleanup`.

Add the [cleanup buildpack](https://github.com/syginc/heroku-buildpack-cleanup) to do the actual cleaning.
