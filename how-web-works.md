// HOW WEB WORKS EXERCISE

### What is HTTP?
Hypertext Transfer Protocol that provides an agreed upon set of rules and methods for how to communicate/transfer text.

### What is a URL?
A set of instructions regarding a request for html pages. These instructions include the protocol, the hostname that we want to get the files from, the port, the resources we want to get from that hostname and the query string that we want to pass.

### What is DNS?
Domain Name Server is like a translator that takes a hostname and resolves/converts it into an IP address. It'll start with the cache on your computer, then it goes to the router and then the ISP and finally the DNS servers to find the IP address.

### What is a query string?
A query is a group of one or more key-value pairs that we pass in the URL and are meant modify the resource that we are requesting.

### What are two HTTP verbs and how are they different?
GET and POST. GET is how we make a request without changing data on the server. POST is how we make a request with the intention of changing data on the server.

### What is an HTTP request?
An HTTP request is a request for an HTML file using the HTTP protocol. It includes the verb, the protocol (in this case HTTP), the resource and header.

### What is an HTTP response?
An HTTP response is the file that the server returns based on the respective HTTP request. It includes the protocol, the status code, the header, and the actual file/resource.


### What is an HTTP header? Give a couple examples of request and response headers you have seen.
HTTP header is the meta data that tells the most important pieces of information regarding the HTTP request/response, including the type of file (html, css, js), the date the request was made, the server information.

### What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
- First turns hostname `somesite.com` into IP address using DNS
- Connects to the IP address, through the port (Since the protocol is HTTP, the default port is = 80)
- Makes a request using the HTTP protocol for the specific resource `/some/page.html`.
- Issues an HTTP response, including the file requested.



