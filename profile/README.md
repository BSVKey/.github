# BSVKey

**Payments, names and proofs on Bitcoin BSV, built so you keep your own keys.**

BSVKey makes small tools that use Bitcoin BSV for the things it does well: tiny payments,
permanent public records, and signatures anyone can check. Wallet keys stay in your browser
or on your machine. Payments and receipts can be checked by anyone, without trusting us.

Start at **[bsvkey.com](https://bsvkey.com)**, or see the on-chain transactions behind each
product at **[proof.bsvkey.com](https://proof.bsvkey.com)**.

## Hosted apps

| App | What it does |
|---|---|
| [BSVKey Live](https://live.bsvkey.com) | Live and recorded video carried on Bitcoin BSV: go live from your browser or OBS, get paid by the minute |
| [Gatherings](https://bsvkey.com/gather) | Paid gatherings: limited seats on a price ladder, a stage you can bid for, live audio |
| [Paid DMs](https://bsvkey.com/dm) | Strangers pay your price in Bitcoin BSV to reach your `.key` name; messages are encrypted to you, highest paid on top |
| [Governor](https://governor.bsvkey.com) | A budget for every AI agent: caps per agent, approvals for big jobs, a kill switch and a signed spend record |
| [Contact Gauge](https://gauge.bsvkey.com) | Pay-per-call API for AI agents: should you talk with this person? $0.02 per call in Bitcoin BSV over x402 |
| [Proof Detectives](https://kids.bsvkey.com) | A kids' game about checking receipts |

## Pay per call: x402 on Bitcoin BSV

| Repository | What it does |
|---|---|
| [inference-mcp](https://github.com/BSVKey/inference-mcp) | MCP server: buy Claude and Grok inference by the token, settled in BSV. `npx @bsvkey/inference-mcp` |
| [bsvkey-grok-plugin](https://github.com/BSVKey/bsvkey-grok-plugin) | The same pay-per-token inference as a Grok plugin, paid in BSV or XRP |
| [x402-paywall](https://github.com/BSVKey/x402-paywall) | Put an HTTP 402 paywall in front of any API, as middleware or a reverse proxy |
| [x402-bsv-client](https://github.com/BSVKey/x402-bsv-client) | Pay an x402 quote in BSV: the `bsv-p2pkh` payment builder and receipt checks |

Hosted: [inference.bsvkey.com](https://inference.bsvkey.com) and
[paywall.bsvkey.com](https://paywall.bsvkey.com).

## Names and sign-in

| Repository | What it does |
|---|---|
| [bsvkey-names-extension](https://github.com/BSVKey/bsvkey-names-extension) | Open `.key` names in Chrome, Edge and Brave ([Chrome Web Store](https://chromewebstore.google.com/detail/jlcjljbhljhkfllaedejoalonobjoocd), [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/nmeeppefbhcadepjblmbajoibambbhhn)) |
| [keyauth](https://github.com/BSVKey/keyauth) | Sign in with `.key`: verify a name owner's BSV signature, zero dependencies |
| [name-index](https://github.com/BSVKey/name-index) | Free static snapshot of the on-chain name registry for fast lookups |

Try it: [bsvkey.com/market](https://bsvkey.com/market) and [bsvkey.com/signin](https://bsvkey.com/signin).

## Custody receipts

Each party that holds something signs what it received, when, and in what condition, and
the records chain one after another, so anyone can check the whole history without
trusting any single party. Each repository runs offline with `npm test`.

| Repository | What it covers |
|---|---|
| [custody-kits](https://github.com/BSVKey/custody-kits) | Describe a handoff process as a small spec, get signed and chained receipts |
| [pharma-custody](https://github.com/BSVKey/pharma-custody) | Temperature-sensitive pharmaceutical shipments |
| [aviation-custody](https://github.com/BSVKey/aviation-custody) | Aircraft parts history, back to birth |
| [maritime-custody](https://github.com/BSVKey/maritime-custody) | Shipping containers, port to port |
| [vehicle-custody](https://github.com/BSVKey/vehicle-custody) | Vehicle software updates, incident logs and battery data |
| [robotics-custody](https://github.com/BSVKey/robotics-custody) | Robot-to-robot handoffs and payments bound to them |
| [finance-custody](https://github.com/BSVKey/finance-custody) | Holdings attestations and reserve reports |
| [needs-custody](https://github.com/BSVKey/needs-custody) | Basic needs: water delivered, food aid, drought payouts |
| [climate-custody](https://github.com/BSVKey/climate-custody) | Proof of measurement for carbon credits and other climate claims: signed meter readings, calibration, claims re-derived from the readings, double-counting checks |

More at [custody.bsvkey.com](https://custody.bsvkey.com).

## Space, weather and delay-tolerant networks

| Repository | What it does |
|---|---|
| [dtn-custody-demo](https://github.com/BSVKey/dtn-custody-demo) | Data custody and relay payments for delay-tolerant networking (Bundle Protocol) |
| [open-downlink-custody](https://github.com/BSVKey/open-downlink-custody) | Signed receipts and cross-station checks for real satellite downlinks (SatNOGS) |
| [wx-custody](https://github.com/BSVKey/wx-custody) | Custody receipts for NOAA weather-satellite data, checked byte for byte |
| [elf-link](https://github.com/BSVKey/elf-link) | BSV payment signals over ELF and through-the-earth links (simulation) |

Live: [dtn.bsvkey.com](https://dtn.bsvkey.com) and [weather.bsvkey.com](https://weather.bsvkey.com).

## Machine-checked proofs

| Repository | What it does |
|---|---|
| [bsvkey-axiom-proofs](https://github.com/BSVKey/bsvkey-axiom-proofs) | 15 BSVKey rules (payments, spend caps, names, receipts, custody) proven in Lean (57 theorems), with proof receipts anchored on Bitcoin BSV. Checked by Axiom's AXLE and, independently, by Lean's own kernel in CI on every push. Includes a public [advisory](https://github.com/BSVKey/bsvkey-axiom-proofs/blob/main/ADVISORY.md) on a proof of `False` that AXLE accepts |

Check a receipt in your browser: [bsvkey.github.io/bsvkey-axiom-proofs](https://bsvkey.github.io/bsvkey-axiom-proofs/).

## Contact and security

Questions or partnership: **embryospace@gmail.com**. Please report security issues
privately to the same address, see [SECURITY.md](https://github.com/BSVKey/.github/blob/main/SECURITY.md).

BSVKey software is provided as is, without warranty. On-chain writes are permanent and
public, and you are responsible for your own keys and funds. Nothing here is financial advice.
