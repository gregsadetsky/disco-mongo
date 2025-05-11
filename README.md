# Example Disco Mongo

This is an example of how to deploy a Mongo service to your Disco instance.

Deploy this as a separate project, and then other projects can connect to it using the internal `mongo-mongo` domain name ie the full URL would be `mongodb://mongo-mongo:27017`

See [this repo](https://github.com/letsdiscodev/example-flask-mongo-site) for an example Flask server that connects to this Mongo instance.
