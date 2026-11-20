# Local SEO by Ryze AI — Cursor Plugin

Run local SEO from Cursor: your Google Business Profile, Google Maps rankings and local competitors, Google Analytics and Google Ads.

## Install

**In Cursor:**

[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20Local%20SEO%20by%20Ryze%20AI-000000?logo=cursor&logoColor=white)](cursor://anysphere.cursor-deeplink/mcp/install?name=local-seo-by-ryze-ai&config=eyJ1cmwiOiAiaHR0cHM6Ly9sb2NhbHNlby5nZXQtcnl6ZS5haS9tY3AifQ==)

Or by hand: **Cursor › Settings › MCP › Add new MCP server**, type `http`, URL:

```
https://localseo.get-ryze.ai/mcp
```

Or drop this into `.cursor/mcp.json` in your project (same content as [mcp.json](mcp.json)):

```json
{ "mcpServers": { "local-seo-by-ryze-ai": { "url": "https://localseo.get-ryze.ai/mcp" } } }
```

Cursor opens a browser tab: sign in to Ryze and allow access. No API keys. Also works in Claude Code: `claude mcp add local-seo --transport http https://localseo.get-ryze.ai/mcp`.

## What you can do

- **Google Business Profile**: read the listing, reviews and replies, posts, photos, attributes, daily Search and Maps performance and the search terms that showed it; reply to reviews, publish or delete posts, add photos, update hours, categories, description and attributes.
- **Local search research (DataForSEO)**: Google Maps rankings for any keyword in a city or at an exact point, the results page with the local pack, nearby competitors by category, keyword volume and ideas, ranked keywords, organic competitors and backlinks. No account connection needed.
- **Google Analytics**: GA4 reports, traffic by channel, landing pages and key events.
- **Google Ads**: account summaries, GAQL reports, keyword ideas, recommendations and campaign changes.

Account tools appear after you connect that platform in Ryze.

## Safety

Read tools are read-only. Tools that change an account are marked as writes, and delete tools are marked destructive. Every action runs under the permissions of the accounts you connected.

## Requirements

A Ryze AI account. Connecting accounts works before you start a plan. The tools need an active Ryze plan, which starts with a 7-day trial; the assistant gives you the link the first time a tool needs it.

## Links

- [Website](https://www.get-ryze.ai?utm_source=github&utm_content=local-seo-cursor-plugin)
- [Privacy policy](https://www.get-ryze.ai/privacy?utm_source=github&utm_content=local-seo-cursor-plugin)
- Support: hello@get-ryze.ai

Local SEO by Ryze AI is an independent product. It is not affiliated with or endorsed by Google.
