# ⚽ sportOracle

**Consumer MCP Server** — 12 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-12-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/sport/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "sportoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/sport/mcp/"]
    }
  }
}
```

## Tools (12)

| Tool | Description |
|------|-------------|
| `sport_scores` | Live and today's scores for any sport/league. Returns live, final and upcoming g |
| `sport_standings` | Current league table / standings with points, wins, losses, goal difference. |
| `sport_team` | Team profile: stadium, capacity, founded year, manager/coach, country, league. |
| `sport_player` | Player profile: nationality, position, team, height, weight, date of birth. |
| `sport_fixtures` | Next upcoming fixtures for a team. |
| `sport_results` | Last 10 results for a team with scores. |
| `sport_leagues` | Browse all supported leagues. Filter by sport: soccer, football, basketball, bas |
| `sport_search_team` | Search for teams by name. Returns team ID, sport, league, country, stadium. |
| `sport_search_player` | Search for players by name. Returns nationality, position, team, birth date. |
| `sport_top_scorers` | Top scorers / statistical leaders for a league. |
| `sport_news` | Latest sports news headlines from ESPN. |
| `health_check` | SportOracle server status and backend connectivity. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

sportOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/sport/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
