# Word Orb MCP server

This repository holds an early configuration for the Word Orb MCP server. The current code, setup instructions and plans live in **[nicoletterankin/word-orb](https://github.com/nicoletterankin/word-orb)**. Please use that repository.

Word Orb is a dictionary and lesson API for developers: 162,253 AI-assisted English word records and 601,143 translations. Coverage varies by word and language, so check your own word list with the [evaluator](https://wordorb.ai/playground#evaluate) before you integrate.

## Connect

The MCP endpoint is `https://wordorb.ai/mcp` (Streamable HTTP). Tools that look up words need a Word Orb API key, sent as a header:

```json
{
  "mcpServers": {
    "word-orb": {
      "url": "https://wordorb.ai/mcp",
      "headers": {
        "Authorization": "Bearer wo_YOUR_KEY"
      }
    }
  }
}
```

`wo_YOUR_KEY` is a placeholder. Keep your real key in your client's secret storage, never in a committed file.

## Plans and docs

- Plans and limits: [wordorb.ai/pricing](https://wordorb.ai/pricing)
- API docs: [wordorb.ai/docs](https://wordorb.ai/docs)

## About

Word Orb is made by [Lesson of the Day, PBC](https://lotdpbc.com), a California Public Benefit Corporation based in Malibu, California.
