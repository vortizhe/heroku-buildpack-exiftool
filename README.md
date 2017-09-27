heroku-buildpack-exiftool
=========================

A Heroku buildpack that installs the latest production version of Phil Harvey's [ExifTool](http://www.sno.phy.queensu.ca/~phil/exiftool/).

Usage
-----

Simply add this Git repo to your `.buildpacks` file and set your Heroku config var `BUILDPACK_URL` to `https://github.com/giddyio/heroku-buildpack-multi.git#build-env`.
