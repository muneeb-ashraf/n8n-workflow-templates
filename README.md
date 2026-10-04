# n8n workflow templates by Amplence

Production-minded n8n workflows we publish for free. Each one keeps the decisions that matter in code, puts AI behind a fixed answer format, and ships with sample data so you can run it end to end before it touches a real customer.

Built by [Amplence, an n8n automation agency](https://amplence.com/services/n8n-automation-services).

## Templates

| Workflow | What it does | n8n library |
|---|---|---|
| [Law firm intake triage](workflows/law-firm-intake-triage.json) | Conflict check and limitation screening in code, then a Claude agent writes a staff-only brief. Prospects only ever get a fixed acknowledgement. | [n8n.io/workflows/20282](https://n8n.io/workflows/20282) |
| [Shopify support email answering](workflows/shopify-support-email-answering.json) | Reads support emails in Gmail, pulls live Shopify order data, drafts a reply with Claude and sends it to Slack for review. | [n8n.io/workflows/20178](https://n8n.io/workflows/20178) |
| [Inbound lead scoring and routing](workflows/inbound-lead-scoring-and-routing.json) | Claude scores each inbound lead, then routes it through HubSpot, Slack and Gmail. | [n8n.io/workflows/19767](https://n8n.io/workflows/19767) |
| Shopify returns and refund desk (paid) | Return policy checked in code, Shopify's own refund calculation, and no refund until a manager approves it in Slack. | [Template or done-for-you setup](https://muneebai.gumroad.com/l/shopify-returns-refund-desk-n8n) |

## How to use

1. Download the JSON file.
2. In n8n, open **Workflows → Import from file**.
3. Follow the Overview sticky note on the canvas: it lists the credentials, settings and sheet columns each workflow needs.
4. Run the manual trigger first. Every template includes a sample input so you can test without touching real data.

## Need it built for your stack?

We build, migrate and maintain n8n workflows with error paths, alerts and handover documentation. See [our n8n automation services](https://amplence.com/services/n8n-automation-services) or estimate the payoff first with the [AI automation ROI calculator](https://amplence.com/ai-automation-roi-calculator).

## License

MIT. Use them, change them, ship them.
