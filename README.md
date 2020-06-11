# csivitreplica

Recreating the frontend for [csivit.com](https://csivit.com)

# Usage
You need to serve the root directory of this project statically from a web server. One way to do this,
is to serve the directory using python's simple HTTP server.

with python2:

```bash
cd <inside project>
python -m SimpleHTTPServer
```

with python3:

```bash
cd <inside project>
python -m http.server 
```

This should prompt that a local server has been started on `http://0.0.0.0:8000`. Navigate to that
URL on a browser to view the html page
