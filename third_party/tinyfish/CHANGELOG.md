# Changelog

All notable changes to this plugin will be documented here.

## 1.0.0 — initial release

- Added the `tinyfish` MCP server pointing at TinyFish's hosted Streamable HTTP endpoint (`https://agent.tinyfish.ai/mcp`).
- Auth uses OAuth with TinyFish user login (PKCE, dynamic client registration via `clerk.tinyfish.ai`) — no API key or client ID to configure. Registration was verified to accept every Cursor redirect set, including Grok Bot mobile.
- Logo: TinyFish's official fish mark, from the app icon published on tinyfish.ai, on a 192×192 tile.
