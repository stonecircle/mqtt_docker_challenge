# Proposal

Create an mqtt-backed chat application in a client/server Docker environment.

## Technologies
  - node.js
  - docker
  - mocha/chai for testing
  - your choice of MQTT broker
  - your choice of MQTT JS client
  - frontend framework optional

## Acceptance Criteria
  - the aplication can be start with a `docker-compose up`
  - the chat application can be started by visiting http://localhost:<port>
  - the chat app can have multiple channels
  - users can create channels
  - users can join channels
  - users can leave channels
  - user can talk to eachother in a channel
  - all features must be tested

## strech features
  - users can create accounts
  - users can login/out
  - messages persist between sessions ( requires database )

## Looking for
  - test coverage
  - creation and orchestration of a platform with docker
  - understanding of backend/front end decoupling and communication
