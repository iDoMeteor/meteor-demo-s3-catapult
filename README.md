# Demo App for idometeor:s3-catapult

## What it is

[@iDoMeteor's](http://twitter.com/iDoMeteor) [S3 Catapult](http://atmospherejs.com/idometeor/s3-catapult) is a Meteor JS package which provides Blaze templates and event handlers that allow a user to upload files to your S3 bucket via direct file input or a remote URL.  

## How it Works

Direct file input uses client-side resources, while URL transfers use server-side resources to prevent the need to enable global CORS policies which would open up your app to potential exploits.

## How to Use it

Simply clone this repo like so:

> git clone git@github.com/iDoMeteor/meteor-demo-s3-catapult

You now have the standard app created by ```meteor create app```, along with the [iDoMeteor S3-Catapult package](http://atmospherejs.com/idometeor/s3-catapult) and a settings-default.json file.

To run the demo app and upload files to your S3 bucket, do the following:
    
* ```cd meteor-demo-s3-catapult```
* ```cp settings-default.json settings.json```
* Edit settings.json and enter your Amazon S3 key, secret & bucket name.
* Lint that with ```jsonlint``` to make sure it is still properly formatted.
* Now you can run ```meteor --settings settings.json``` and test it out!

Read the documentation on the [Atmosphere package page](http://atmospherejs.com/idometeor/s3-catapult) for information on template names, methods names, and all that good stuff.
