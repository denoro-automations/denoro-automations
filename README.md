![Denoro Automations](banner.png)

## Hi, I'm Manel — Denoro Automations 👋

I build automations for **online stores** (Shopify and WooCommerce) so the repetitive work stops being done by hand. Built on n8n (plus Python where it helps), running on your server or on mine.

### What's already built
| Automation | What it does | Repo |
|---|---|---|
| **Competitor price monitor** | Watches competitors' prices and stock and sends one summary by Telegram and email when something changes, with a CSV of prices. Includes a panel where each client pastes the links to watch. | [price-monitor](https://github.com/denoro-automations/price-monitor) |
| **Weekly store report** | Every Monday at 8:00: sales, orders and average order vs last week, best sellers and stock to reorder, as a PDF by email and Telegram. | [weekly-report](https://github.com/denoro-automations/weekly-report) |
| **Product copy in bulk** | SEO titles, meta descriptions and HTML descriptions for a whole catalogue, ready to import. Free template engine, or OpenAI with your own key; any figure not in the product data is flagged. | [ecommerce-automations](https://github.com/denoro-automations/ecommerce-automations/tree/main/fichas-producto) |
| **Supplier stock sync** | Reads the supplier's CSV or XML feed every 4 hours and updates stock, stopping itself if the feed looks broken. Never touches prices. | [ecommerce-automations](https://github.com/denoro-automations/ecommerce-automations/tree/main/stock-proveedor) |
| **Abandoned carts** | Reminder sequence signed by the store, only to shoppers who opted in, and a running count of what came back. | [ecommerce-automations](https://github.com/denoro-automations/ecommerce-automations/tree/main/carritos) |
| **Review monitoring** | Same-day alert on new negative reviews (WooCommerce reviews, or public pages whose robots.txt allows it) and a Monday digest. | [ecommerce-automations](https://github.com/denoro-automations/ecommerce-automations/tree/main/resenas) |
| **Invoices and delivery notes** | Numbered invoices with VAT by rate, a branded PDF to the customer and a CSV ledger. Not Verifactu-certified software. | [ecommerce-automations](https://github.com/denoro-automations/ecommerce-automations/tree/main/facturas) |

Each one has a demo mode, its own tests, and the n8n workflow generated from reviewable source code.

### How I work
1. You tell me what you want automated, in writing
2. Fixed price and delivery date before any work starts
3. Working automation, documentation and a step-by-step explanation of how to use it
4. Fixes are free for the first 2 weeks after delivery; monthly maintenance is optional

**Tech:** n8n · Python · Docker · Shopify and WooCommerce APIs · REST APIs

**Site, plans and quote request:** https://denoro-automations.github.io/

From other websites I only read public data (prices, product details, stock) and respect their robots.txt. Store data such as carts or invoices is handled only on the store's behalf, for the job agreed.
