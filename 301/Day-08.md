# Day 08

## APIs

### 1. What does REST stand for?

---
representational state transfer.

### 2. REST APIs are designed around a.

---
resources.

### 3. What is an identifier of a resource? Give an example.

---
A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

`https://adventure-works.com/orders/1`

### 4. What are the most common HTTP verbs?

---
The most common operations are GET, POST, PUT, PATCH, and DELETE.

### 5. What should the URIs be based on?

---
URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

### 6. Give an example of a good URI.

---
`https://adventure-works.com/orders`

### 7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

---
it's means that API requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. Its a bad thing

### 8. What status code does a successful `GET` request return?

---
A successful GET method typically returns HTTP status code 200 (OK).

### 9. What status code does an unsuccessful `GET` request return?

---
returns HTTP status code 404 (Not Found).

### 10. What status code does a successful `POST` request return?

---
returns HTTP status code 201 (Created).

### 11. What status code does a successful `DELETE` request return?

---
returns HTTP response code 200 (OK).

---
