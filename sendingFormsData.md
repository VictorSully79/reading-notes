# Sending Forms Data
notes taken from: https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data

## Client/server architecture
### Client/Server architecture can be summerized as " a client (usually a web browser) sends a request to a server (most of the time a web server) using the HTTP Protocol.  The server answers the request using the same protocol."

### The `<form>` element is used to define the data that will be sent. This happens when a user hits a submit button.  This has two attributes: action and method. 

## The Action Attribute
### This defines where the data gets sent. Example:
- Absolute URL: `<form action="https://example.com">`
- relative URL: `<form action="/somewhere_else">`
### When not specified the data will be sent to the same page the form is on.

## The Method Attribute
### This defines how data is sent. The most common are `GET` and `POST`

## The GET Method
### This will ask the browser to ask the server to send something back. Example of HTTP request:
`GET /?say=Hi&to=Mom HTTP/2.0
Host: foo.com`

## The POST Method
### This method will ask the browser to look over a result and back an appropriate result. Request will look like this: 
```POST / HTTP/2.0
Host: foo.com
Content-Type: application/x-www-form-urlencoded
Content-Length: 13

say=Hi&to=Mom
```
## Viewing HTTP requests
### These are never dispayed to the user but can be found in the developer toos.

