# What we will learn

- REST

The source of this summary [The first link](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

______________________________________

## REST

**What does REST stand for?**

representational state transfer

**REST APIs are designed around a resources.**

**What is an identifer of a resource? Give an example.**

A resource has an identifier, which is a URI that uniquely identifies that resource.

**What are the most common HTTP verbs?**

The most common operations are GET, POST, PUT, PATCH, and DELETE

**What should the URIs be based on?**

URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

**Give an example of a good URI.**

(https://adventure-works.com/orders) A Good URL

**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

It is a bad thing try to avoid "chatty" web APIs that expose a large number of small resources.

**What status code does a successful GET request return?**

A successful GET method typically returns HTTP status code 200 (OK)

**What status code does an unsuccessful GET request return?**

If the resource cannot be found, the method should return 404 (Not Found).

**What status code does a successful POST request return?**

If a POST method creates a new resource, it returns HTTP status code 201 (Created). The URI of the new resource is included in the Location header of the response. The response body contains a representation of the resource.

**What status code does a successful DELETE request return?**

If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content), indicating that the process has been successfully handled, but that the response body contains no further information.
