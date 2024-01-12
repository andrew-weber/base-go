# Golang Base Template

## Setup

```
go install github.com/a-h/templ/cmd/templ@latest
go install github.com/cosmtrek/air@latest
```

## Run

1. Create `.env`, similar to `example.env`
2. `go mod tidy`
3. `air`
4. In another window: `curl localhost:3000`

## Considerations

- The database connector is currently libsql, if using a different db, you will need to replace the connector.
