# heroku-buildpack-load-test
Heroku buildpack for running JMeter on a dyno

## Usage

Add the buildpack:

`$ heroku buildpacks:add https://github.com/apdarr/heroku-buildpack-load-test/`

Start a one-off dyno:

`$ heroku run bash -a app_name`

Run the test, in this case using the [ruby-jmeter gem](https://github.com/flood-io/ruby-jmeter):

```
~ $ ruby test_plan.rb
W, [2017-04-07T18:40:20.151431 #6]  WARN -- : Test executing locally ...
```
