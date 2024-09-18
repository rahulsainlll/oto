# RESTful microservices 

### API Gateway Design

Root Name
**product**

Under this name, we have the following methods:

- **GET** `/product`
- **POST** `/product`

For a single product with ID parameters:

```markdown
product.addResource('{id}');
```

- **GET** `/product/{id}`
- **PUT** `/product/{id}`
- **DELETE** `/product/{id}`
