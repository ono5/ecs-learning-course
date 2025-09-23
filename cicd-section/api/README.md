## Local

```bash
http://localhost:8080/api/hello
```

```bash
docker image build -t hello-world-api .
docker container run --rm -p 8080:8080 -t hello-world-api

docker image build -t hello-world-api-2 .
docker container run --rm -p 8080:8080 -t hello-world-api-2
```

## Github OIDC
https://token.actions.githubusercontent.com
sts.amazons.com