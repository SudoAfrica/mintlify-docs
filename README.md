# Cloudcard Developer Docs

Mintlify documentation for the Cardcore API.

## Local preview

Mintlify does not support Node 25.x for local preview in this environment. Use the installed Node 22 runtime instead:

```bash
export PATH="$HOME/.nvm/versions/node/v22.22.1/bin:$PATH"
mintlify dev
```

The default preview URL is `http://localhost:3000`.

## Project structure

- `api-reference/openapi.json`: the OpenAPI file used by Mintlify endpoint pages.
- `docs.json`: site navigation and top-level configuration.

## Known API coverage gaps

These flows still need confirmed route details:

- `List Institution Transactions`
- `List Institution Users`
- `Generate RSA Key`

Those operations are noted in the guides, but they are not exposed as live API playground pages until their routes are confirmed.
