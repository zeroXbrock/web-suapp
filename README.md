# SUAVE Web Demo

A web app that interacts with a SUAPP.

**System Dependencies:**

- [bun](https://bun.sh)
- [foundry](https://getfoundry.sh)
- [suave-geth devnet](https://github.com/flashbots/suave-geth/?tab=readme-ov-file#starting-a-local-devnet)

## Quickstart Example

1. Make sure you're running a suave-geth devnet on `http://localhost:8545`.

2. Build smart contracts & install dependencies from NPM:

    ```bash
    forge build
    bun install
    ```

3. Run the example:

    ```bash
    bun run dev
    ```

    This will launch a web demo hosted at [localhost:5173](http://localhost:5173), where you can get some testnet ether and send a "bid."
