# service-twitch-live-results
A simple tool for grabbing search results for search queries.

## Functionality

- Accept a single autorization phase.
- Store access/refresh/revoke tokens.
- Refresh 1 day before expire. (safety net)
- Refresh 2 day before expire on any request to tool. (most likely)
- Store last update time.
- Twitch search results cached.
- JSON output, so caching on client also possible.
