# grpc
Framework gRPC's complex use of HTTP/2 makes it impossible to implement a gRPC client in the browser, instead requiring a proxy, gRPC supports the usage of TLS and token based authentication. Connection to Google services must use TLS. There are two types of credentials: channel credentials and call credentials.

<img src="https://i.imgur.com/elkuFat.png">

### gRPC When use
* microservices;
* Mobile, Backend;
* Generation of libraries automatically;
* Bidirectional streaming using HTTP / 2;
