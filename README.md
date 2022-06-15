Write a blog on Difference between HTTP1.1 vs HTTP2?

HTTP1.1:
loads a single request for every TCP connection
the usest works on the textual format.
There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
It uses requests resource Inlining for use getting multiple pages
HTTP2
It works on the binary protocol.
It allows multiplexing so one TCP connection is required for multiple requests.
It uses PUSH frame by server that collects all multiple pages 

Write a blog about objects and its internal representation in Javascript

Its unordered collection of related data of primitive or reference types in the form of key: value pairs. 
