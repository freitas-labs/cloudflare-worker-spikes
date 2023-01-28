# quick-start

The following code snippet creates a cloudflare worker that responds with "hello world" uppon request.

```bash
# Make a javascript file
echo "export default { fetch() { return new Response('hello world') } }" > index.js
# try it out
npx wrangler dev index.js
# and then publish it
npx wrangler publish index.js --name my-worker --latest
# visit https://my-worker.<your workers subdomain>.workers.dev
```
