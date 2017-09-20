# Example for pushing a static site to deis.
testing
deis create
deis config:set BUILDPACK_URL='https://github.com/ddollar/heroku-buildpack-multi.git'
