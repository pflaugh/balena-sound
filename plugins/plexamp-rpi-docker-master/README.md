Based on <https://forums.plex.tv/t/suggestions-for-the-future-headless-rpi-support/218187/161>.

Get a server.json file from existing Plexamp on desktop install and place it at the root of this repo.

```
docker build -t plexamp:2.0.0-b2 .
docker-compose up -d
```

PS: Sign out and back into your existing install to get a new identifier/token for Plexamp desktop.
