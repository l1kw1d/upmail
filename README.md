# upmail

[![Travis CI](https://travis-ci.org/jessfraz/upmail.svg?branch=master)](https://travis-ci.org/jessfraz/upmail)

Provides email notifications for [sourcegraph/checkup](https://github.com/sourcegraph/checkup).

## Usage

```console
$ upmail -h
upmail - v0.1.0
  -appengine
    	enable the server for running in Google App Engine
  -config string
    	config file location (default "checkup.json")
  -d	run in debug mode
  -interval string
    	check interval (ex. 5ms, 10s, 1m, 3h) (default "10m")
  -mandrill string
    	Mandrill API Key to use for sending email (optional)
  -password string
    	SMTP server password
  -recipient string
    	recipient for email notifications
  -sender string
    	SMTP default sender email address for email notifications
  -server string
    	SMTP server for email notifications
  -username string
    	SMTP server username
  -v	print version and exit (shorthand)
  -version
    	print version and exit
```
