![Baselayer.css](assets/baselayer.svg)

```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/baselayer.css@latest/dist/baselayer.css">
```

or

```sh
$ npm i baselayer.css
```

## What is baselayer.css?

Baselayer.css is a basic stylesheet for native HTML elements. It requires no classes, and it gives you nothing beyond normalized, styled native HTML elements. There is no grid, there are no components, just the bare basics.

- Sensible defaults for native HTML elements (no classes necessary).
- Visual Consistency (CSS custom props FTW)
- Themeable (see above)
- Stardards-compliant browser support (press f for ie)
- Tiny size (~3KB gzipped)

## What does it look like?

[Here is a demo](https://thisanimus.github.io/baselayer.css/) that shows most of the elements you're likely to use in their typical context.

## Why does this exist?

For most of my projects I don't want or need an entire CSS framework, but I found myself writing minor variations of the same resets and CSS custom props over and over. Baselayer.css is my attempt to codify this into something focussed, consistent and reusable.

## Is this for you?

Baselayer.css will make your HTML look nice without any extra effort, it will give you basic CSS custom-props for color and spacing, it's seriously small, and it won't get in the way of the rest of the stuff you want to build. If that sounds good to you, baselayer.css may be for you.

There are plenty of good reasons to choose another tool instead:

- "I just want a CSS reset." Use [Josh Comeau's reset](https://www.joshwcomeau.com/css/custom-css-reset/) or [Eric Meyer's reset](https://meyerweb.com/eric/tools/css/reset/).
- "I like what you're doing here, but it's a little too minimal, and I really wish borders were `box-shadow` instead of `border`." Use [water.css](https://watercss.kognise.dev/).
- "I want a small CSS framework, but I need a grid and some components." Use [Miligram](https://milligram.io/), [Mustard](https://kylelogue.github.io/mustard-ui/index.html), or [Bulma](https://bulma.io/).
- "I know what I'm about son, and what I'm about is blue buttons." Use [Bootstrap](https://getbootstrap.com/) or [Foundation](https://get.foundation/).
- "CSS SUCKS!!! Have you tried Tailwi..." \*sigh. Go [Tailwind](https://tailwindcss.com/) it up.

## Installation - HTML

Throw this in your website's `<head>`:

### ☾/☼ Automatic Theme:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/baselayer.css@latest/dist/baselayer.css" />
```

or

```js
import '../node_modules/baselayer.css/dist/baselayer.css';
```

### ☾ Dark Theme:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/baselayer.css@latest/dist/baselayer-dark.css" />
```

or

```js
import '../node_modules/baselayer.css/dist/baselayer-dark.css';
```

### ☼ Light Theme:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/baselayer.css@latest/dist/baselayer-light.css" />
```

or

```js
import '../node_modules/baselayer.css/dist/baselayer-light.css';
```

<br>

## CSS Custom Props

Colors and sizing are done via CSS custom props so you can make whatever adjustments you need.

### UI Colors

```
--color-light-muted
--color-light
--color-light-intense

--color-dark-muted
--color-dark
--color-dark-intense

--color-ui-muted
--color-ui
--color-ui-intense

--color-link-default
--color-link-hover
--color-link-visited
```

### Theme Colors

```
--color-primary-muted
--color-primary
--color-primary-intense

--color-accent-muted
--color-accent
--color-accent-intense
```

### Sizing

```
--border-radius
--border-width
--space-sm
--space-md
--space-lg
--space-xl
```

### Fonts

```
--font-sans: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell,
'Helvetica Neue', sans-serif;
--font-monospace: 'SFMono-Regular', Andale Mono, Consolas, 'Liberation Mono', Menlo, monospace;
--font-serif: Palatino, 'Palatino Linotype', 'Palatino LT STD', 'Book Antiqua', Georgia, serif;
```
