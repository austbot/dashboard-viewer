# The Ygrene Dashboard Viewer
This [resin.io](https://resin.io/) based application runs on a raspberry pi to
display our [grafana](http://grafana.org/) dashboards.

It's running firefox with the [R-kiosk](https://addons.mozilla.org/en-us/firefox/addon/r-kiosk/)
extensions. Optionally it runs an openvpn client in case your dashboards are
not accessible from the public internet.

![dashboard](dashboard.jpg)

## Use it
Add your resin git remote and push the project. For details see
[resin.io's getting started documentation](http://docs.resin.io/#/pages/installing/gettingStarted.md).

Just clone this repo instead of the example.
After that, you need to set some [environment variables](http://docs.resin.io/#/pages/management/env-vars.md):

- `URL`: Dashboard URL to open
- `USR`: HTTP basic user
- `PASS`: HTTP basic pass


