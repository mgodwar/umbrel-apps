# Zeus Apps — private Umbrel community app store

Add to Umbrel: **App Store → ⋯ (top right) → Community App Stores → paste this repo's URL → Add**.

| App | What it is |
|---|---|
| `zeus-vpn-downloads` | Gluetun (ProtonVPN Plus, WireGuard, Phoenix + LA) with Decypharr and RDTClient routed through it |

Secrets are never committed. After installing `zeus-vpn-downloads`, the WireGuard private key goes in
`/Apps/zeus-vpn-downloads/data/secrets/wireguard_private_key` on the Umbrel, then restart the app.
