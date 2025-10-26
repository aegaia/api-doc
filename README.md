# Aegaia Risk API Docs Bundle

This bundle contains:
- `openapi.yaml` — OpenAPI 3.1 spec
- `index.html` — Swagger UI viewer
- `redoc.html` — ReDoc viewer
- `Aegaia_Risk_API.postman_collection.json` — Postman collection
- `assets/aegaia-logo.svg` — placeholder logo (replace with your official file)

## How to use
- Open `index.html` or `redoc.html` in a browser to explore the API.
- Import the Postman collection, set `AEGAIA_API_KEY`, and send.

## CORS hints (if you host behind API Gateway/CloudFront)
Allow **POST, OPTIONS**; headers `content-type, x-api-key, idempotency-key`; return `Access-Control-Allow-Origin` on success and error paths.
