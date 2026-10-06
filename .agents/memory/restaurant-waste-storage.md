---
name: Browser-local storage
description: The restaurant food-waste app's storage boundary.
---

Keep this app frontend-only with browser-local persistence. Do not migrate waste records to a shared database or add a server API unless the user explicitly asks.

**Why:** The user chose to preserve the existing localStorage-backed records and keep this app frontend-only.

**How to apply:** Continue reading and writing the existing browser-local record store for this product. Treat any move to shared or server-side persistence as a scope change requiring an explicit request.
