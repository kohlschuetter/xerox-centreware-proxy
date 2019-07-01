# xerox-centreware-proxy

Xerox [released version 10.6](https://www.support.xerox.com/support/_all-products/file-download/enus.html?contentId=134232) of their firmware for the Phase 8560MFP printer with a bug, which prevents the navigation menu in the Webserver configuration to load in modern web browsers.

By running this proxy, we can rectify that:

```
# node xerox-proxy.js
Created proxy at http://localhost:8560/
Requests will be forwarded from and to http://xerox.:80/
```

Then simply point your browser to [http://localhost:8560/]().
