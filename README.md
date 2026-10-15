# Sea to Summit Promo Planner

Local-first promotion planning + stock-check tool for Sea to Summit (Thailand), built from the `Catalog update` sheet of the brand's product catalog. Two tabs in the sidebar:

## 🏷️ Promo Planner

- Pick **Offline** or **Online** pricing channel first (each channel has its own price basis and discount tier set: BAU/Warehouse-XC Mega/Season Sale/Special Day offline, BAU/FS/MEGA/DOUBLE/PAYDAY online).
- Select products (Stock All and Stock FG/SDC1 shown per SKU) — or paste many article codes at once (any text; only real catalog codes are picked, unknown/no-price codes are reported).
- Apply a Discount Tier, then stack up to 5 promo steps: On Top %, cumulative %, **One Price**, Cash Voucher, GWP (manual cost, or a real Sea to Summit product at its catalog cost), **Bundle Deal** (search/pick up to 10 catalog products, or pull straight from Step 1; priced as a flat ฿ or a % off the combined retail) and Redeem.
- **Fee %** = the commission a Platform / shopping mall charges on the net amount the customer pays; it is deducted from what the brand receives.
- Results use each SKU's **real Cost**. A Bundle Deal is priced as **one set** (combined retail & cost, one gift, one Fee). Margin% and a below-cost warning are shown; the formula for every column (①–⑥) is explained under the table.
- **📝 Note** — turns the current promo into one readable line per promo, grouped in numbered campaigns:
  `3.1 | Aeros UL Traveller Jet Black + Tek Towel M Sage | ปกติ 3,060 (Cost 739.12) → Bundle 1,960 | ฟรี Ultra-Sil Hanging Toiletry Bag S Blue Atoll (มูลค่า 2,970 / Cost 472.81) | Fee 25% | Disc 67.4%`
  Set KPI targets per campaign and per promo line, and copy a campaign as text to share with other teams.
- **Export Excel** — Summary + Products sheets with live **formulas** (change a tier %, cost, voucher, fee or a step value and everything recalculates).
- Re-upload a fresh `Catalog update` export (.xlsx) at any time to refresh the embedded product data.

## 📦 Merchandise Planner

Paste any text — a Note, a SKU list, or just product names. It finds real catalog **article codes and product names** (name + colour + size) in the text, so codes don't have to be removed. Pick the stock source: **Stock All**, **SDC1 (FG)**, **Branch** (Stock All − SDC1) or **FGOL (Online)**. Products can be linked by **name + colour + size** (stock summed across every article code of the same product, with per-code stock shown) or by the pasted article codes only. Set an overall sales target to see the shortfall, and copy the result (Article / Name+Colour+Size / Stock) as a tab-separated list for Excel.

Open `index.html` directly in a browser, or via GitHub Pages.

Data embedded at build time: 735 SKUs.
