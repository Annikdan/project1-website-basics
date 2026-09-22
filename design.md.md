---
version: alpha
name: "Annik - Project 1"
description: "this should feel like a personal vlog, for like girls to share tips and stuff they learn day by day and feel like sharing for others as well. kinda like a community of wellness"
omitted: [rounded]
colors:
  defaultText: "#45496A"
  defaultBackground: "#F9F8CD"
  alternateText: "#7D8BAE"
  alternateBackground: "#FCD1B7"
  action: "#FF8B9D"
  hover: "#FCF6B9"
  buttonText: "#FFC9C9"
typography:
  rootSize: 20px

fontFamilies:
  body: "Lato"
  headings: "Pacifico"

sizes:
  body: 1rem
  small: 0.8rem
  h1: 2.441rem
  h2: 1.953rem
  h3: 1.563rem
  h4: 1rem
  h5: 1rem
  h6: 1rem

spacing:
  sm: 1.5rem
  md: 2rem
  lg: 4rem
  xl: 6rem
  xxl: 8rem
---

## Overview

this should feel like a personal vlog, for like girls to share tips and stuff they learn day by day and feel like sharing for others as well. kinda like a community of wellness

## Colors

Default colors apply to the page. Alternate colors apply to grouped sections. Links and buttons use the action color, then hover on pointer hover. Button text uses buttonText. Keep links underlined.

- Default Text on Default Background: 8.01:1 — meets the 4.5:1 target for normal text.
- Alternate Text on Alternate Background: 2.42:1 — below the 4.5:1 target for normal text.
- Links and buttons on Default Background: 2.05:1 — below the 4.5:1 target for normal text.
- Links and buttons on hover on Default Background: 1.02:1 — below the 4.5:1 target for normal text.
- Button text: 1.53:1 — below the 4.5:1 target for normal text.
- Button text on hover: 1.32:1 — below the 4.5:1 target for normal text.

## Typography

The base font size is 20px. Use Lato for body text and Pacifico for headings. All size values use rem so changing the root size scales the full type system.

## Layout

Default line height is 1.7. Default page width is 960px. Use the spacing scale for gaps and padding: sm 1.5rem, md 2rem, lg 4rem, xl 6rem, xxl 8rem.

## Do and Don't

### Do

- Use the same exported `style.css` on every page so the type, colors, and spacing stay consistent.
- Use headings in order, beginning with one `h1`, then moving through lower heading levels as the content needs them.
- Keep underlined links and visible keyboard focus so people can find and use interactive content.

### Don't

- Create one-off colors, font sizes, or spacing values when an exported choice already fits the purpose.
- Rely on color alone to communicate meaning; use clear text, labels, or icons too.
- Change a design decision in only one file. Update the form and export a fresh set of files when the system changes.
