---
title: "Breaking MCP at the Identity Layer"
url: "https://slashid.dev/blog/mcp-identity-layer/"
date: "2026-07-30"
author: "SlashID Team, Vincenzo Iozzo"
feed_url: "https://www.slashid.dev/blog/rss.xml"
---
Part 1 attacked the MCP server itself. This part assumes all of that is patched and breaks in through the identity layer instead — where nothing is a bug you can close, and the server does exactly what it was told by the wrong person. We walk the 2026-07-28 authorization spec and the RFCs behind it, the confused-deputy attack that comes from getting consent wrong, how EMA and ID-JAG move consent to the IdP — and the four gaps that remain open afterwards, where every token is valid and nothing in the OAuth stack fires.
