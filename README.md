![code coverage badge](https://github.com/mikeklimanek/learn-cicd-starter/actions/workflows/go-tests.yml/badge.svg)

# Notely

## Local Development

Make sure you're on Go version 1.20+.

Create a `.env` file in the root of the project with the following contents:

```bash
PORT="8080"
```

Run the server:

```bash
go build -o notely && ./notely
```

*This starts the server in non-database mode.* It will serve a simple webpage at `http://localhost:8080`.


