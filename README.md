# cf-locust

This is a Cloud Foundry pushable [locust.io](http://locust.io/) instance with an example locustfile. It can be used for stress testing, load testing and to verify autoscaling functionality.

## How To:

You can specify the _HOST_ you want to *stress* in the manifest as an environment variable.

Modify the `locustfile.py` to touch your endpoints.

Todo:

Make it master slave enabled - It's been stubbed out in the subdirectories.  Needs [tcp-routing](https://github.com/cloudfoundry-incubator/cf-tcp-router) enabled to verify it will run correctly.

Verify it works with Heroku.

Usage documents.
