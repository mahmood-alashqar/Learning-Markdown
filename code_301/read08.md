# APIs

![](https://analyticsindiamag.com/wp-content/uploads/2020/05/APIs-Copyright.jpg)

---
## Introduction

**REST** stands for Representational State Transfer, which is an architectural approach to designing web services.  

**REST** IS independent and it's not tied to **HTTP**. **REST** uses open standard, like a **REST** web service and be written in a language, and client applications can use any language or toolkit that can generate HTTP requests and parse HTTP responses.  

---

## RESTful APIs

The following are design principles for RESTful APIs that use **HTTP** :  

- **REST** **API**s are designed around resources, which are any kind of object, data, or service that can be accessed by the client.  

- A resource has an _identifier_, which is a **URI** that uniquely identifies that resource.  
ex) `https://adventure-works.com/orders/1`

- Clients interact with a service by exchanging representations of resources. Many web APIs use JSON as the exchange format.  
ex) A response body represented in `JSON` `{"orderId":1,"orderValue":99.90,"productId":1,"quantity":1} `  

- **REST** **API**s use a uniform interface, which helps to decouple the client and service implementations.  
- ex)  the following are **HTTP** verbs to perform operations on resources:
    1. `GET`
    1. `POST`
    1. `PUT`
    1. `PATCH`
    1. `DELETE`  


- **REST** **API**s use a stateless request model.  

- **REST** **API**s are driven by hypermedia links that are contained in the representation.  

---

## URIs  

**URI**s should be based on _nouns_ (the resource) and not verbs (the operations on the resource).  

ex)  
```
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Bad

```  

- **URI**s are better be named using plural nouns.
- It is recommended to organize **URI**s resources into a hierarchy.  

ex)  
`/customers/5/orders`  

**"chatty" web APIs** are those that expose a large number of small resources. Such an **API** may require a client application to send multiple requests to find all of the data that it requires. This procedure will cause a load on the server and it is not something you want.  

---

## HTTP Verbs  

There are 4 major methods that we use to give semantic meaning to a request, and these are:  
- `GET` retrieves a representation of the resource at the specified **URI**. The body of the response message contains the details of the requested resource.

- `POST` creates a new resource at the specified **URI**. The body of the request message provides the details of the new resource. Note that `POST` can also be used to trigger operations that don't actually create resources.
- `PUT` either creates or replaces the resource at the specified **URI**. The body of the request message specifies the resource to be created or updated.
- `PATCH` performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.
- `DELETE` removes the resource at the specified **URI**.  

---

## Verbs Responses

**GET** :  
- A successful `GET` method typically returns `HTTP status code 200`(OK).
- An unsuccessful `GET` method returns `404 (Not Found)`.  

**POST** :  
- A successful `POST` method, that creates a new resource return `HTTP status code 201 `(Created).
- If no creation happens, but `POST` method does some processing, it returns `HTTP status code 200`.  
- If there is no result to return, the `POST` method returns `HTTP status code 204` (No Content).  
- If the client puts invalid data into the request, the server should return `HTTP status code 400` (Bad Request).  

**DELETE** : 
- A successful `DELETE` method return `HTTP status code 204`.  
- An unsuccessful `DELETE` method returns `HTTP 404` (Not Found).

---

### Resources:  
- [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)