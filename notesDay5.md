# How To Node
Notes taken from above article

### Node.jx is an open source, cross-polatform runtime enviroment.

### Allows for the building of server-side and networking applications.

## Simple Server

```var http = require("http");

http.createServer(function(request, response) {
  response.writeHead(200, {"Content-Type": "text/plain"});
  response.write("It's alive!");
  response.end();
}).listen(3000);
```
To Run the server

`node server.js`

### You can use Heroku as a cloud platform server allowing you to deploy your server to the WWW.