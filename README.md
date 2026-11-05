# Amazon via Bifröst

**App name:** Amazon via Bifrost
**Publisher:** Origo — **Version:** 28.0.0.0 — **Target:** Cloud (BC 28, runtime 17.0)
**App ID:** `4869aee6-da16-4bd0-9fb5-61aaebbc7210` — **Test app ID:** `995fdc2f-1cf0-497a-8c24-73c090da8cfb`
**Object ID range:** 10034985–10035034 (tests 97800–97899) — **Namespace:** `Origo.Bifrost.Amazon`

Amazon via Bifrost will make Amazon callable from Business Central through Bifröst message types, so an agent can
operate it end to end. It is built on the same basis as
[Bifrost Subscription Billing](https://github.com/businesscentralal/bc-origo-bifrost-subscription-billing).

**Status:** planning, no message types yet.

---

## Object ranges

| Object | Range |
| --- | --- |
| App (`app/`) | 10034985-10035034 |
| Test app (`test/`) | 97800-97899 |

---

## Documentation

All public documentation lives in the [businesscentralal/bifrost](https://github.com/businesscentralal/bifrost)
site repository and is published at <https://docs.bifrost.origo.is>.

| What | Where |
| --- | --- |
| Product documentation | <https://docs.bifrost.origo.is/en-us/amazon/> |
| Bifröst documentation home | <https://docs.bifrost.origo.is> |
| Release notes | [CHANGELOG.md](CHANGELOG.md) |

---

## Dependencies

| App | ID | Publisher | Version |
| --- | --- | --- | --- |
| Bifrost Foundation | `7505e808-6e52-4b96-a328-82573391297a` | Origo | 28.0.8.617 |

---

## Repository layout

| Folder | Content |
| --- | --- |
| `app/` | The AppSource app (`Amazon via Bifrost`), no AL code yet |
| `test/` | Test app (`Amazon via Bifrost - Tests`) |
| `tools/` | Pipeline guard scripts |
| `.AL-Go/`, `.github/`, `.alpaca/` | AL-Go for GitHub / COSMO Alpaca pipeline configuration |
