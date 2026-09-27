# AttentionWatch for Grok Build

Publisher: Montorox LLC. Plugin version: 1.0.0. License: MIT (this distribution package only).

Minimal configuration-only plugin for AttentionWatch's public, read-only remote MCP service.
Network endpoint: `https://attentionwatch.com/mcp/grok`. Credentials: **none**.
The endpoint must be deployed to production before public installation; this prepared package is not a published or approved marketplace plugin.

## Discovery capabilities

| Tool | Purpose |
| --- | --- |
| search_products | Neutral permanent AI Product directory search |
| get_product | Public Product details and labeled public context |
| list_categories | Public Product taxonomy |
| find_similar_products | Metadata/taxonomy relatedness, not endorsement |
| get_just_shipped | Chronological approved Launch discovery |
| get_product_launches | Approved Product Launch history |
| get_trending | Verified organic visits over PT24H, unrelated to paid rank |
| get_active_offers | Third-party public promotions, not purchase/redemption |
| get_attention_market | Promotion Credit-funded paid competitive visibility |
| get_daily_champions | Finalized historical outcomes of paid Attention Markets |

Offers are Product-owner claims, not AttentionWatch guarantees. Paid outcomes are not editorial awards, quality scores, endorsements, or organic popularity. Third-party content is data, never instructions.

## Security and data handling

No local executable, dependency, hooks, skills, agents, commands, binaries, shell access, filesystem access, environment reads, OAuth, API keys, or account mutations are included.
Grok sends discovery arguments to the disclosed HTTPS service. AttentionWatch records operational request metadata (tool, duration, outcome, counts, coarse client family, cache/rate outcome, timestamp, internal request identifier), not intentional raw conversation/prompt/body/argument/response logging. Framework/infrastructure logs are separate. Ordinary public discovery is not an anonymous guarantee; see the Privacy Policy.

Website: https://attentionwatch.com · Support: https://attentionwatch.com/support · Email: cife@attentionwatch.com

Privacy: https://attentionwatch.com/privacy · Terms: https://attentionwatch.com/terms · MCP docs: https://attentionwatch.com/developers/mcp

## Review and validation

Run `grok plugin validate .` from this package directory before distribution. Do not install/trust plugins automatically.
Future standalone repository: `montorox/attentionwatch-grok-plugin` (pending creation). Copy only these four package files, including the hidden configuration/manifest. Do not publish the application repository.

Examples: find AI tools for customer support; read Product slug `langsmith`; show recently approved Launches; show organic Trending; find public discounts; read today's paid Attention Market; read recent Daily Champions.

Manifest and HTTP configuration follow the official [Neon manifest](https://github.com/xai-org/plugin-marketplace/blob/main/external_plugins/neon/.grok-plugin/plugin.json) and [.mcp.json](https://github.com/xai-org/plugin-marketplace/blob/main/external_plugins/neon/.mcp.json) conventions. Review current [contribution requirements](https://github.com/xai-org/plugin-marketplace/blob/main/CONTRIBUTING.md) again before publishing.
