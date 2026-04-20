# tower-guard

Application-layer security middleware for [tower](https://github.com/tower-rs/tower)-based services. Part of the [guard ecosystem](https://github.com/rennf93).

Works with any framework built on `tower::Service` — including [axum](https://github.com/tokio-rs/axum), [hyper](https://github.com/hyperium/hyper), and [warp](https://github.com/seanmonstar/warp).

**Status:** Reserved namespace. Implementation pending — see [guard-core-rs](https://github.com/rennf93/guard-core-rs) for the reference engine and roadmap.

## About

The guard ecosystem provides application-layer API security middleware across multiple languages and frameworks:

- **Python**: [fastapi-guard](https://github.com/rennf93/fastapi-guard), [flaskapi-guard](https://github.com/rennf93/flaskapi-guard), [dj-api-guard](https://github.com/rennf93/dj-api-guard), [tornado-api-guard](https://github.com/rennf93/tornado-api-guard)
- **TypeScript**: guard-core-ts with adapters for Express, Fastify, Hono, NestJS
- **Rust**: guard-core-rs (in development) with adapters for tower, axum, actix-web, rocket

## License

MIT