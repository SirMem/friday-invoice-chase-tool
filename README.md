# Friday Invoice Chase Ranker

**Local-first, single-purpose** browser tool that answers: *who should I chase for overdue freelance invoices this Friday?*

Type rows (client, amount, days overdue) → click **Rank Friday chase** → get a sorted table with **Top 3**, biased toward **60+ days overdue** first.

## Criteria (Tool Commons)

| Requirement | Met |
|-------------|-----|
| Open source (OSI) | MIT |
| No login | Yes |
| Local-first | Yes — data never leaves the page |
| No ads / no tracking | Yes |
| Static hostable | GitHub Pages |
| Single purpose | Rank who to chase by overdue days |

**Strict:** no `fetch()`, no `localStorage`, no `sessionStorage`, no cookies, no analytics scripts.

## Live

- **Tool:** https://sirmem.github.io/friday-invoice-chase-tool/
- **Source:** https://github.com/SirMem/friday-invoice-chase-tool
- **Share Your Startup (queued):** https://shareyourstartup.com/s/friday-invoice-chase-ranker (badge on tool page)

## How ranking works

1. Sort primarily by **days overdue** descending.
2. Within the same overdue band, larger amount first.
3. **60+ day** invoices are called out and preferred in the Top 3 explanation (cash-risk bias freelancers already use informally).

EXAMPLE rows are fictional and pre-filled so the tool works on first open.

## Not advice

Not tax, legal, or debt-collection advice. EXAMPLE data is fictional. You decide whom to contact and how.

## Related (optional)

- Free Excel aging sample: https://github.com/SirMem/freelancer-invoice-aging-sample
- Hub / CN bridge: https://sirmem.github.io/freelancer-money-sheets/zh-xuesheng-sihuo-zhuizhang.html
- Optional paid Friday tracker ($6, Gumroad): exists separately; **this web tool stays permanently free**.

## License

MIT — see [LICENSE](LICENSE).
