---
name: design-a-shirt
description: Design a custom t-shirt with VibeShirt, show it on a garment mockup, quote the price and build a cart. Use when the user asks for a shirt, tee, merch or apparel design.
---

# Design a shirt with VibeShirt

## When to use

- The user wants a custom t-shirt or merch design
- The user wants to see a design on a shirt, change its size or position, or get a price

## Steps

1. Create the art with the design tool (or `upload_image` / `get_upload_link` if the user has their own file).
2. Show it on a shirt with `preview_mockup` (pick the color the user asked for).
3. For changes to an existing design, call `list_layers`, then `edit_layers` on the same project, then `preview_mockup` again.
4. Use `quote_price` and `list_discounts` for pricing; mention the volume discount when it applies.
5. Use `add_to_cart` with style, color, size and quantity, then share the checkout link.

## Notes

- Sign-in uses OAuth the first time a tool is called. No API key is needed.
- Original designs only: no third-party logos, team marks or famous characters.
