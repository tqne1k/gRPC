# Overview
> - Client application can directly call a method on a server application on a different machine as if it were on a local object.
> - Based around the idea of defining a service, specifying the methods can be called remotely with their parameters and return types.
> - On the server side, server implements interface and run gRPC server to handle client call. On the client side, client has a stub that provides the same methods as the server.

<img src="https://grpc.io/img/landing-2.svg">

