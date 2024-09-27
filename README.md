# slidev-theme-chromablend

[![NPM version](https://img.shields.io/npm/v/slidev-theme-chromablend?color=3AB9D4&label=)](https://www.npmjs.com/package/slidev-theme-chromablend)

A (...) theme for [Slidev](https://github.com/slidevjs/slidev).

<!--
  Learn more about how to write a theme:
  https://sli.dev/themes/write-a-theme.html
--->

<!--
  run `npm run dev` to check out the slides for more details of how to start writing a theme
-->

<!--
  Put some screenshots here to demonstrate your theme

  Live demo: [...]
-->

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>chromablend</b>
---</code></pre>

Learn more about [how to use a theme](https://sli.dev/themes/use).

## Layouts

This theme provides the following layouts:

> TODO:

## Components

This theme provides the following components:

> TODO:

## Customizations

```yaml
themeConfig:
  # Background
  background-angle: "180deg";
  background-from: "#161616 30%";
  background-to: "#313845 100%";

  # Text
  color: "#f9e0d9"
  link: "#f9e0d9"
  link-hover: "#cfcfea"
  font-size: "1.1em"

  # Heading
  heading-angle: "45deg"
  heading-from: '#ff2e74 20%'
  heading-to: "#eac435 80%"

  # Default
  default-angle:
  default-from:
  default-to:

  # Cover
  cover-title-angle:
  cover-title-from:
  cover-title-to:

  # Center
  center-title-angle:
  center-title-from:
  center-title-to:

  # Section
  section-title-angle:
  section-title-from:
  section-title-to:
```

## Contributing

- `npm install`
- `npm run dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `npm run export` to generate the preview PDF
- `npm run screenshot` to generate the preview PNG
