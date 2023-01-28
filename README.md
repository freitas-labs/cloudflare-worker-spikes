# cloudflare-worker-spikes

Spikes for development of cloudflare workers

## Quick start

Quick scripts/functions can be shipped as a worker using `wrangler` CLI (see [quick-start/README](quick-start/README.md)

## Project workers

More complex workers can be developed as a Node package and generated using `wrangler` CLI (see [my-worker-project/README](my-worker-project/README.md)

## Dependencies

It's possible to depend on Node packages as long as they are bundled with a polyfill bundler, such as `webpack` (see [worker-with-dependencies/README](worker-with-dependencies/README.md)
