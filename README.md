# Yew - Wasm - Tailwind

## Development

-   Install rust

-   Install dependencies

```bash
cargo install trunk wasm-bindgen-cli && rustup target add wasm32-unknown-unknown
```

-   Serve on `localhost:8080`

```bash
trunk serve
```

- Update Tailwind configurations

```bash
(cd ./tailwind-yew-builder && docker-compose up dev)
```
