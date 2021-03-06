## The world wide web is a network of information resources


## The web relies on 3 mechanisms 

- single naming schema (URL)
  To give access to any resources on the web in a uniform way.

- Protocols (HTTP)
  To enable the exchange of named resources over the web.

- Hypertext (HTML)
  For easy navigation among resources.

### Universal Resource Locators (URLs) :
- Every resource available on the web "HTML document, image, video clip, program, etc.." has an address 
  that may be encoded by a universal resource locator, or 'URL'.

### URL consistes of 3 pieces
- The name of the protocol used to transfer the resource over the web.
- The name of the machine hosting the resource.
- The name of the resource itself given as a path.

For Example 'http://www.mdn.org/main-letters/first-letter.html'
This URL may be read as follows
-  Use the HTTP protocol to transfer the data
-  residing on the machine (www.mdn.org)
-  in the file (main-letters/first-letter.html)

## HTTP 
  It's an application-layer protocol for transmiting documents
  Designed for communication between web browsers and servers
  with a client opening a connection to make a request Then waitting
  until it receives a response 

  HTTP is a stateless protocol means that the server does not keep any Data ( state ) between two requestes.
  Though often based on a TCP/IP layer, it can be used on any reliable transport layer.

Typical HTTP session 
in client-server protocols, like HTTP, sessions consists of three phases:
  1. The client establish a TCP connection 
  ( or appropriate connection if the transport layer is not TCP )
  2. The client sends it's request, and waits for the answer.
  3. The server processes the request, sending back its answer
  ( providing a status code and appropriate data )


## TCP ( Transmission Control Protocol )
  is a Transport Layer host-to-host protocol for connection-oriented communication between two computers on an IP network
  TCP uses virtual ports to create virtual end-to-end connection that can reuse the physical connection between two computers 

## IP ( Internet Protocol )
  Usually used along with TCP protocol and it is used to locat a specific device
