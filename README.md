# Awesome Go code formatters

A curated list of [Go](https://golang.org/) code formatters.

## Code formatters

* [gofmt](https://golang.org/cmd/gofmt/) -- the default built-in formatter.
* [go-parsefix](https://github.com/quasilyte/go-parsefix) -- fixes simple parse errors.
* [go-ruleguard](https://github.com/quasilyte/go-ruleguard) -- analysis-based formatter based on custom rules.
* [gofumpt](https://github.com/mvdan/gofumpt) -- a stricter gofmt.
* [golines](https://github.com/segmentio/golines) -- fixes long lines.
* [goreturns](https://github.com/sqs/goreturns) -- fills in return statements with zero values to match the func return types.
* [keyify](https://github.com/dominikh/go-tools/tree/master/cmd/keyify) -- turns unkeyed struct literals into keyed ones.
* [unconvert](https://github.com/mdempsky/unconvert) -- removes unnecessary type conversions.

## Imports formatters

* [dedupimport](https://github.com/nishanths/dedupimport) -- fixes duplicate named/unnamed imports that have the same import path
* [gci](https://github.com/daixiang0/gci) -- controls package import order and make it always deterministic.
* [goimports-reviser](https://github.com/incu6us/goimports-reviser) -- goimports alternative.
* [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) -- adds missing imports and removes unused ones.

## Code generators

* [stringer](https://godoc.org/golang.org/x/tools/cmd/stringer) -- generates string representation for integer constants.

## See also

* [awesome-go-linters](https://github.com/golangci/awesome-go-linters)
* [awesome-python-code-formatters](https://github.com/life4/awesome-python-code-formatters)
* [awesome-go](https://github.com/avelino/awesome-go)
