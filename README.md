# go.halvorai.com

Static pages that make `go get go.halvorai.com/ingest/...` resolve to [halvorAI/ingest-go](https://github.com/halvorAI/ingest-go). Served by GitHub Pages from `main`, folder `/`.

- Every package folder in the SDK needs its own `ingest/<path>/index.html`, a copy of `ingest/index.html`.
- Never change the `go-import` line except the repository URL at its end.
- Never delete this repo or its Pages site while the `go` DNS record points at `halvorai.github.io`.
