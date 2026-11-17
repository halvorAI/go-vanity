# go.halvorai.com

> **The Go SDK is frozen as of 17 Nov 2026.** [halvorAI/ingest-go](https://github.com/halvorAI/ingest-go) stays published but gets no new features and is no longer kept in step with the JavaScript SDK. For new integrations, use [ingest-js](https://github.com/halvorAI/ingest-js) or [ingest-python](https://github.com/halvorAI/ingest-python); if you need Go, contact us at hello@halvorai.com. **Keep this repo and its Pages site:** `go get go.halvorai.com/ingest` stops working without them.

Static pages that make `go get go.halvorai.com/ingest/...` resolve to [halvorAI/ingest-go](https://github.com/halvorAI/ingest-go). Served by GitHub Pages from `main`, folder `/`.

- Every package folder in the SDK needs its own `ingest/<path>/index.html`, a copy of `ingest/index.html`.
- Never change the `go-import` line except the repository URL at its end.
- Never delete this repo or its Pages site while the `go` DNS record points at `halvorai.github.io`.
