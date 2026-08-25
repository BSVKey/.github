# BSVKey

**Inscribe. Host. Register — permanently on the BSV blockchain, 100% in your browser.**

BSVKey is a serverless, client‑side tool for the Bitcoin SV chain. Your private key never
leaves your browser tab and there is no backend — everything is built, signed, and
broadcast locally.

🔑 **App:** [bsvkey.com](https://bsvkey.com)

## What it does
- **Inscribe** — write text or files on‑chain via `OP_RETURN`.
- **Host** — publish full HTML pages on‑chain (CHOST); one wallet can host multiple named sites, each resolving to its latest version.
- **Register names** — claim human‑readable names in an on‑chain, first‑claim‑wins registry; visit any site at `bsvkey.com/#site=name`.
- **Wallet** — single‑key or HD recovery‑phrase wallets, balance & fiat value, history, sweep, and stuck‑transaction fixes.
- **On‑chain feed** — scan, read, and post messages the world is inscribing.

## Trust & verifiability
- 100% client‑side; keys are never transmitted or stored on a server.
- The bundled library is pinned with **Subresource Integrity**, and the app's code hash is **inscribed on‑chain** so anyone can verify the page they're running is authentic.
- Open and inspectable — download the source right from the app.

## Repositories
- **[name-index](https://github.com/BSVKey/name-index)** — optional, free indexer (GitHub Actions + Pages) that publishes a static `names.json` snapshot of the on‑chain name registry for instant lookups. BSVKey falls back to a trustless on‑chain scan if it's unavailable.

## Disclaimer
BSVKey is provided **as is**, without warranty. On‑chain writes are **permanent and public**,
and you are solely responsible for your keys and funds. Nothing here is financial advice.
