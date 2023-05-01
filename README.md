# scoreboard

A board maintaining highscores of players with a graphql API

Step 1

1. create dir `graph`
2. create files `schema.graphql`
3. create file `gqlgen.yml `
4. Setup gqlgen

> > `go get github.com/99designs/gqlgen`
> > `go install github.com/99designs/gqlgen`
> > `printf '// +build tools\npackage tools\nimport _ "github.com/99designs/gqlgen"' | gofmt > tools.go`
> > `go mod tidy`

---
