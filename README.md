# VibeShirt Cursor plugin

Cursor Marketplace plugin for [VibeShirt](https://vibeshirt.com): design custom t-shirts by chat, preview mockups, get volume pricing and check out.

## What's included

- `plugins/vibeshirt/mcp.json`: the hosted VibeShirt MCP server (`https://vibeshirt.com/api/connector/mcp`, OAuth 2.1, no API key)
- `plugins/vibeshirt/skills/design-a-shirt`: step-by-step design, mockup, pricing and cart flow
- `plugins/vibeshirt/rules/vibeshirt.mdc`: usage rules (edit existing projects in place, original designs only)

The plugin contains no executable code; all actions run on the VibeShirt server after the user signs in.

## Validate

```bash
node scripts/validate-template.mjs
```

## Support

info@vibeshirt.com · Privacy: https://vibeshirt.com/pages/privacy-policy · Terms: https://vibeshirt.com/pages/terms-of-service
