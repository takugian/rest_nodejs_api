# rest_api_nodejs

## How to deploy

### Local

```
npm install
npm start
```

#### How to test

- curl http://localhost:3070/
- curl http://localhost:3070/customers

### Docker

```
docker build -t rest_api_nodejs .
docker images
docker run -d -p 3070:3070 --name rest_api_nodejs rest_api_nodejs
```

#### How to test

- curl http://localhost:3070/
- curl http://localhost:3070/customers