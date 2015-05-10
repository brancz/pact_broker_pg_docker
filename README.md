Pact Broker with Postgres and Docker
====================================

Easily setup your own [Pact Broker](https://github.com/bethesque/pact_broker)
instance with docker-compose.

Simply download the docker-compose.yml to your machine and run

	docker-compose pull
	docker-compose up -d db
	docker-compose up

Done! You can configure your Pact Broker and Postgres with the environment
variables inside the docker-compose.yml file.
