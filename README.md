# Sea to Summit Promo Planner

Local-first promotion planning + stock-check tool for Sea to Summit (Thailand), built from the `Catalog update` sheet of the brand's product catalog. Two tabs in the sidebar:

## 🏷️ Promo Planner

- Pick **Offline** or **Online** pricing channel first (each channel has its own price basis and discount tier set: BAU/Warehouse-XC Mega/Season Sale/Special Day offline, BAU/FS/MEGA/DOUBLE/PAYDAY online).
- Select products (with Stock All *and* Stock FG/SDC1 shown per SKU), apply a Discount Tier, and stack up to 5 promo steps: On Top %, cumulative %, **One Price**, Cash Voucher, GWP (manual cost, or picked from a real Sea to Summit product's actual cost), **Bundle Deal** (search/pick up to 10 real catalog products into one set — or pull straight from your Step 1 selection — priced as a flat ฿ or a % off), and Redeem.
- Profit (฿) and GP% are computed from each SKU's **real Cost** (not estimated), with a loss warning when a promo prices below cost. Results table headers are in Thai with numbered (①-⑥) formulas explained below the table.
- **📝 Note** — snapshot the current selection as a human-readable line (`Article  Name (price Cost cost) + ... = mechanic (Disc X%)`) into a named campaign; add more promo lines to the same campaign, set KPI targets both per-campaign and per-promo-line, and copy the whole campaign as text to share with other teams.
- Export the plan to Excel (Summary + Products sheets).
- Re-upload a fresh `Catalog update` export (.xlsx) at any time to refresh the embedded product data — no rebuild needed.

## 📦 Merchandise Planner

Paste any text (a Note export, a raw SKU list, anything) and it detects only the tokens that exactly match a real catalog Article code — pick **Stock All**, **SDC1 (FG)**, or **Branch** as the stock source (Branch = Stock All − SDC1), see each matched SKU's stock, set an overall sales target to see how much stock is short, and copy the results (Article / Name+Color+Size / Stock) as a tab-separated list ready to paste into Excel.

Open `index.html` directly in a browser, or via GitHub Pages.

Data embedded at build time: 735 SKUs.
