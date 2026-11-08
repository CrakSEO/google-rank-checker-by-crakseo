# Google Rank Checker: Keyword Rankings & Rank Tracking by CrakSEO

Google rank checker for SEO: live keyword rankings and positions for any website, ranked keywords, ranking competitors and keyword gaps. On-demand rank tracking.

Check where any website ranks on Google for your keywords. The rank checker returns live Google positions for up to 10 keywords per call, every keyword a domain ranks for (ranked keywords), the competitors ranking for the same keywords, and keyword gaps between domains. Use it for on-demand rank tracking, competitor analysis, finding competitor keywords, and checking SEO progress after changes.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/rank-tracker` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits |
| Docs | https://docs.crakseo.com/mcp-servers/rank-tracker |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `check_google_rankings` | Check Google rankings for a domain | API credits |
| `get_ranked_keywords` | Ranked keywords for a domain | API credits |
| `find_competitor_keywords` | Find competitor keywords (keyword gap) | API credits |
| `find_competitor_domains` | Find competitor domains | API credits |
| `get_api_credit_balance` | API credit balance | Free |

## Questions it answers

- Where does my website rank on Google for these keywords?
- Which keywords does a website rank for?
- Who are my SEO competitors and which keywords am I missing?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-rank-tracker": {
      "url": "https://crakseo.com/mcp/rank-tracker"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/rank-tracker

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
