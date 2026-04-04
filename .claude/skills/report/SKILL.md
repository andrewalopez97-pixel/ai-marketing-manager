---
name: report
description: Pull ad performance and analytics report for any client
user-invocable: true
argument-hint: [client-name] [time-period]
---

# Performance Report Generator

Pull a performance report. Follow this workflow:

1. **Ask which client** (if not in $ARGUMENTS, or "all" for all clients)
2. **Ask the time period**: Today, Last 7 days, Last 30 days, This month, Custom range
3. **Ask what to focus on**: Ads, Organic posts, Both

Then use available MCP tools to pull data:

- Use **meta-ads** MCP to pull ad performance (spend, reach, impressions, clicks, conversions, cost per result)
- Use **brave-search** to check current Google ranking for the client's local SEO keywords

Generate a report with:

- **Summary** (1-2 sentence overview — up or down vs previous period)
- **Key metrics** (formatted as a clean table)
- **Top performing content** (what worked best)
- **Underperforming content** (what to cut or change)
- **Recommendations** (3-5 specific actions to take this week)
- **Budget check** (on track, overspending, or underspending)

Keep it concise and actionable — no fluff.
