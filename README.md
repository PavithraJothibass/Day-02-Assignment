1.	Write a blog on difference between HTTP 1.1 vs HTTP 2.
HTTP/1.1	HTTP/2
It works on the textual format.	It works on the binary protocol.
There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.	It allows multiplexing so one TCP connection is required for multiple requests.
It uses requests resource Inlining for use getting multiple pages	It uses PUSH frame by server that collects all multiple pages 
It compresses data by itself.	It uses HPACK for data compression.

2.	Write a blog about object and its internal representation in Javascript.
Objects:
•	Objects are important data types in javascript. Objects are different than primitive datatypes.
•	Objects are more complex and each object may contain any combination of these primitive data-types.
Internal representation of objects:
•	Internally, javascript engines use various data structures to represent objects efficiently. 
•	One common approach  is using a hash table or a similar structure to store the objects properties and their corresponding values.
•	This allows for fast access and manipulation of properties.

Internal representation:
{
name: “Pavithra J”
age: 22,
email: “pavithrajothi2002@gmail.com
}
