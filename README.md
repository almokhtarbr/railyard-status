# Railyard status

https://almokhtarbr.github.io/railyard-status/

A static page. It checks app.railyard.run/up and railyard.run live from the visitor's browser every minute, so it is never stale, and draws 90-day uptime from https://app.railyard.run/uptime, which Railyard records every 5 minutes (a missed check counts as downtime).

Source: status/live/index.html in almokhtarbr/railyard-app. Nothing here needs GitHub Actions.
