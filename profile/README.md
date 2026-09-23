<p align="center">
  <img src="https://raw.githubusercontent.com/POSplugin/.github/main/assets/banner-posplugin.png" alt="PosPlugin. Any POS. One API. Live in 30 minutes." width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-EARLY%20ACCESS-FF4F12?style=for-the-badge&labelColor=141412" alt="Status: early access">
  <img src="https://img.shields.io/badge/VERTICAL%2001-RESTAURANTS-D6D5CF?style=for-the-badge&labelColor=141412" alt="Vertical 01: restaurants">
  <img src="https://img.shields.io/badge/API-REST%20%2B%20WEBHOOKS-D6D5CF?style=for-the-badge&labelColor=141412" alt="API: REST and webhooks">
</p>

<p align="center">
  <a href="https://posplug.in"><b>site</b></a> ·
  <a href="https://posplug.in/#access">early access</a> ·
  <a href="https://posplug.in/llms.txt">llms.txt</a>
</p>

---

**Connecting to a merchant's point-of-sale system is a custom integration every time.** There are
hundreds of POS systems, each with its own API, and the work breaks whenever a vendor changes theirs.

**PosPlugin is one integration instead of hundreds.** It connects to the POS, its AI maps the POS's fields
to one clean data model, and your app reads every merchant through one REST API and one webhook stream.

- **Connect** with OAuth or an API key. Discovery is read-only; nothing is written to the POS.
- **Map** with AI: a confidence score on every field. Low-confidence mappings wait for a person to confirm them.
- **Build once** against `orders`, `payments`, `items` and `locations`, whichever POS is behind them. The original payload stays on every record.

The target is a new merchant live in under 30 minutes, with a free sandbox to build against first.

## Where it stands

| | What it is | Status |
| :--- | :--- | :--- |
| **Site** | [posplug.in](https://posplug.in): the product, the six-step setup, the planned API | **Live** |
| **Early access** | Tell us which POS systems you need. Access opens in waves, restaurants first | **Open** (live signup) |
| **Connectors, AI mapping, unified API** | The product itself | **In development** |
| **Sandbox** | Test POS data, the full API and webhooks. Free | **Planned** |
| **Live** | Priced per connected location, set with early customers | **Planned** |

## Security, by design

Designed in, not yet audited (early access): no full card numbers, only brand and last four as the POS
returns them · encrypted in transit and at rest · POS credentials sealed per merchant · per-tenant
isolation · an audit log of every mapping change and every AI decision · built for GDPR (export,
deletion, regional storage, a DPA listing every sub-processor).

## Repositories

| Repo | What |
| :--- | :--- |
| [`website`](https://github.com/POSplugin/website) | The landing site. Static HTML, one CSS, one JS, Cloudflare Pages |
| `waitlist-backend` | The early-access list at api.posplug.in, on the Cratefield harness. Private |
| `backend` | The product: connectors, Jev-driven mapping, unified API and webhooks. Private; the plan is written, the code is not |

Questions or a POS you need covered: **contact@posplug.in**

PosPlugin is a venture of [Factory Zero](https://factory0.ventures/ventures/posplugin/) (Factory Zero Pte. Ltd.).
