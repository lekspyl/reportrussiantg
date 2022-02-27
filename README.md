### Installation

1. Install [Docker](https://docs.docker.com/get-docker/) and [docker-compose](https://docs.docker.com/compose/install/)
2. Run `docker-compose build && docker-compose run app`

### Notes

Container doesn't save your telegram session, so on restart you will need to relogin.

You cannot use bots for reporting users, so you need to provide your TG phone number to authenticate, otherwise you'll get this error:

```
The API access for bot users is restricted. The method you tried to invoke cannot be executed as a bot (caused by ReportPeerRequest)
```
