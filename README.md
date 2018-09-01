# Frontend for SPA «ПомойАвто»

It is a frontend for single page application. Reach JavaScript is present.

# Deploy on localhost

Example of frontend launch on Linux, Python 3.5:

```bash
cd static/
python3 -m http.server 9000
```

Open page [localhost:9000](http://localhost:9000) in browser.

# Deploy on production server

Because is being used the [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) mechanism, make sure that your host is included in the `Access-Control-Allowed-Origins` header of the API server response.

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
