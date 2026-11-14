# AskLucien for Claude

AskLucien lets Claude phone a restaurant, shop, hotel or someone you know on your behalf, then
tells you the answer in the same conversation. Calls work in 83 languages and last up to three
minutes. Before anything happens, Claude shows the number, the task, how long the call can last
and the most it can cost. The call starts only when you ask for it, and a live card follows it
while it rings, connects and ends.

## Setup

1. Install the plugin, open its **Connectors** tab and connect AskLucien.
2. Sign in with your AskLucien account (or create one at https://app.asklucien.com) and approve
   the connection.
3. Ask, for example: "Use AskLucien to call +33 1 23 45 67 89 in French and ask if they have a
   table for two tonight at 8."

Calls are paid from your AskLucien credit. This plugin doesn't sell anything or handle payments.
AskLucien doesn't handle emergencies, bulk calling, purchases or bookings.

## What's inside

- `.mcp.json` connects the AskLucien server (`https://app.asklucien.com/api/claude/mcp`). Sign-in
  happens through AskLucien's own OAuth page; the plugin holds no credentials.
- `skills/asklucien-calls` tells Claude when to use AskLucien and in what order to use its tools.

Support: https://asklucien.com/contact · Privacy: https://asklucien.com/privacy ·
Terms: https://asklucien.com/terms
