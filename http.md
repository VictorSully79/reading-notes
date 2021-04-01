# HTTP
notes taked from Things I Brushed Up On This Week
The HTTP Request Lifecycle by: Daniel Golant

## Local Processing

### Browser extracts the "schema"/protocol/port then resolves the IP adddress. It then checks available cache

## Resolve an IP

### If the cache lookup fails (we will assume it does), your browser fires off a DNS request using UDP3. The DNS request contains the preconfigured IP for your DNS server and your return IP in its header. The hostname for which you are trying to resolve an IP is in the request’s "Question" section.

## Establish a TCP Connection

### A requests is sent over TCP, the client must open a TCP connection. This ensures delivery and ordered data transmission. 

-  three-way handshake. The server must already be "listening" on a port, performing a passive open, after which the client can initiate an active open, and the handshake works as follows:

## Send an HTTP Request

### The request is made up of a "request line", request header, and a body. The "request line" is simply a line that indicates the HTTP method, the resource being requested, and the protocol version.

# Do a Simple HTTP Request in Java
notes taken from the above name article by baeldung

## HttpUrlConnection

### The HttpUrlConnection class allows us to perform basic HTTP requests without the use of any additional libraries. All the classes that we need are part of the java.net package.

- may be more cumbersome thatn other HTTP libraries and it does not provide more advanced functionalities.

## Creating a Request

### We can create an HttpUrlConnection instance using the openConnection() method of the URL class. Note that this method only creates a connection object but doesn't establish the connection yet.
``URL url = new URL("http://example.com");
HttpURLConnection con = (HttpURLConnection) url.openConnection();
con.setRequestMethod("GET");``

## Adding Request Parameters

### Set the doOutput to true then write a String of the form `form param1=value¶m2=value to the OutputStream of the HttpUrlConnection instance:`