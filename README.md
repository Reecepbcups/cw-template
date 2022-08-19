# Reece's CosmWasm Template
```bash
# cargo install cargo-generate --features vendored-openssl
# cargo install cargo-run-script
cargo generate --git https://github.com/Reecepbcups/cw-template.git --branch main --name PROJECT_NAME
```

Differences:
```
- execute, queries, test <- in their own contracts
- test.sh, build.sh, clippy.sh
- implemented base test
```

**Older Versions / Original:**
```sh
cargo generate --git https://github.com/CosmWasm/cw-template.git --branch <version> --name PROJECT_NAME
````