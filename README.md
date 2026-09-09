# Sea to Summit Promo Planner

Local-first promotion planning tool for Sea to Summit (Thailand), built from the `Catalog update` sheet of the brand's product catalog.

- Pick **Offline** or **Online** pricing channel first (each channel has its own price basis and discount tier set).
- Select products, apply a Discount Tier, and stack up to 5 promo steps (On Top %, One Price, Cash Voucher, GWP — including GWP priced from real Sea to Summit product cost, Bundle, Redeem).
- Profit (฿) and GP% are computed from each SKU's **real Cost** (not estimated), with a loss warning when a promo prices below cost.
- Export the plan to Excel (Summary + Products sheets) or save a campaign to a local KPI tracker.
- Re-upload a fresh `Catalog update` export (.xlsx) at any time to refresh the embedded product data — no rebuild needed.

Open `index.html` directly in a browser, or via GitHub Pages.

Data embedded at build time: 735 SKUs.
