# Serverless stack in Go

using these technologies:

- API Gateway in Golang
- AWS Lambda
- DynamoDB

## Quickstart

- after cloning repo, run the following command

```sh
go mod tidy
```

- set the environment variables
- then build main.go

```sh
go build -o build/main cmd/main.go
```

- zip the build to the build dir

```sh
zip -jrm build/main.zip build/main
```
