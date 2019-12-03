# project-whiskers

https://project-whiskers.jbinto.ca

DineSafe via Hasura GraphQL API. Current status: 0% to first milestone.

## To do

* Find some node/typescript boilerplate that is useable. Bikeshedding kills kittens!
* Download latest DineSafe data.
* Figure out the simplest table (RESTAURANT most likely), and get it into a local postgres instance.
  * Probably means setting up a quick docker-compose
  * Resist the urge to set up data via hasura, just use knex
* Then figure out how to get that on the remote postgres. Might be as simple as just cloning this repo and running it on ssh.

