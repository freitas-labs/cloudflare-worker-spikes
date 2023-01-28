# worker-with-dependencies

Cloudflare workers support all Node.js packages that are bundled with webpack or any other polyfill bundler (https://blog.cloudflare.com/node-js-support-cloudflare-workers/)

## Notes:

1. Installing a package is as normal as using the common npm syntax (`npm install <dep>`)
2. If the dependency depends on Node.js native builtins, the `node_compat = true` config needs to be included in `wrangler.toml`
3. Importing a package is done using the ESM syntax (`import {...} from '<dep>'`) 
