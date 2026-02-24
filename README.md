# Word Orb MCP Server

The language layer for AI agents. One call returns IPA, definitions, etymology, translations in 47 languages, gender equity guidance, and AI identity ethics — in 3ms from the edge.

50,000+ words. 47 languages. 60 teaching tones. Ethics built in. $0.00 cached.

## Quick Setup

Add to your MCP client config:
```json
{
  "mcpServers": {
    "word-orb": {
      "url": "https://mcp.wordorb.ai/mcp"
    }
  }
}
```

## Tools

### word_enrich
Look up any word. Returns IPA, part of speech, definition, etymology, teaching insight, semantic connections, translations in 47 languages with native script, and ethics guidance.

**Example:** `word_enrich({ word: "courage" })`

### word_ethics
Get gender equity context and AI identity guidance for any word. Includes historical gender bias, inclusive usage suggestions, and honest framing guidance for AI agents.

### agent_speak
Get recommended phrasing for AI agents based on intent and audience size. Helps agents communicate honestly about their nature.

## Pricing

| Tier | Price | Daily Calls | Features |
|------|-------|-------------|----------|
| Free | $0 | 50 | Core word data |
| Starter | $49/mo | 5,000 | + translations |
| Growth | $149/mo | 50,000 | + ethics + voices |
| Enterprise | $499/mo | Unlimited | Everything + SLA |

## Links

- 🌐 [wordorb.ai](https://wordorb.ai)
- 📡 [API](https://api.wordorb.ai)
- 📖 [Docs](https://docs.wordorb.ai)
- 🔌 MCP Endpoint: `https://mcp.wordorb.ai/mcp`

## About

Built by [Lesson of the Day PBC](https://lotdpbc.com). Word Orb is the language infrastructure behind Kelly and Ken, AI teachers serving learners ages 2-102 in 47 languages.
