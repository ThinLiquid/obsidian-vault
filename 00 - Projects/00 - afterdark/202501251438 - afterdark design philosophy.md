# afterdark design philosophy
## Key points
- Backgrounds aren't used, borders should be used to separate content.
## Fonts
### User interface elements
User interface elements like buttons and inputs should be rendered in a monospace font like JetBrains Mono or Iosevka.
## Readable content
Readable content such as documents/blogs/etc... should be rendered in a sans-serif font like Neue Haas Grotesk, Alte Hass Grotesk, Helvetica Neue or Arial.
### What is readable content?
Readable content is main content on the page that has large amounts of text.
## Shadows
Shadows should be kept to a minimum, only use shadows for objects that appear over the main content like modals.
## Radiuses
The radius works on an 8-system.
## Colors
| type    | name      | purpose           | hex       | hsl                  |
| ------- | --------- | ----------------- | --------- | -------------------- |
| utility | dark      | shadows, overlays | `#0A0A0A` | `hsl(0, 0%, 4%)`     |
| ^^      | white     |                   | `#FFFFFF` | `hsl(0, 0%, 100%)`   |
| neutral | base      |                   | `#141414` | `hsl(0, 0%, 8%)`     |
| ^^      | surface 0 | interior borders  | `#292929` | `hsl(0, 0%, 16%)`    |
| ^^      | surface 1 | exterior borders  | `#525252` | `hsl(0, 0%, 32%)`    |
| ^^      | subtext 0 |                   | `#828287` | `hsl(240, 2%, 52%)`  |
| ^^      | subtext 1 |                   | `#9A9A9E` | `hsl(240, 2%, 61%)`  |
| ^^      | text      |                   | `#CBCBCD` | `hsl(240, 2%, 80%)`  |
| color   | red       | decline, danger   | `#F23F4F` | `hsl(355, 87%, 60%)` |
| ^^      | orange    | warning           | `#EE6748` | `hsl(11, 83%, 61%)`  |
| ^^      | yellow    |                   | `#fa9f50` | `hsl(28, 94%, 65%)`  |
| ^^      | green     | primary           | `#52eea3` | `hsl(151, 82%, 63%)` |
| ^^      | cyan      |                   | `#51e1e9` | `hsl(183, 78%, 62%)` |
| ^^      | blue      |                   | `#437cf3` | `hsl(221, 88%, 61%)` |
| ^^      | purple    |                   | `#6f51f4` | `hsl(251, 88%, 64%)` |
| ^^      | pink      |                   | `#e54f9b` | `hsl(330, 74%, 60%)` |
# Test
`sigam`www