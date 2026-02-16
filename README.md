# css-text-decoration

Functional CSS for text-decoration

## Filesize

| File | Size |
|------|------|
| `dist/text-decoration.css` | 1041 bytes |
| `dist/text-decoration.min.css` | 757 bytes (190 Gzipped) |

## Install

```sh
npm install css-text-decoration
```

## Usage

### Import

```css
@import "css-text-decoration";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-text-decoration/dist/text-decoration.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-text-decoration/dist/text-decoration.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.under` | `text-decoration: underline;` |
| `.over` | `text-decoration: overline;` |
| `.strike` | `text-decoration: line-through;` |
| `.blink` | `text-decoration: blink;` |
| `.none` | `text-decoration: none;` |
| `.under-s` | `text-decoration: underline;` |
| `.over-s` | `text-decoration: overline;` |
| `.strike-s` | `text-decoration: line-through;` |
| `.blink-s` | `text-decoration: blink;` |
| `.none-s` | `text-decoration: none;` |
| `.under-m` | `text-decoration: underline;` |
| `.over-m` | `text-decoration: overline;` |
| `.strike-m` | `text-decoration: line-through;` |
| `.blink-m` | `text-decoration: blink;` |
| `.none-m` | `text-decoration: none;` |
| `.under-l` | `text-decoration: underline;` |
| `.over-l` | `text-decoration: overline;` |
| `.strike-l` | `text-decoration: line-through;` |
| `.blink-l` | `text-decoration: blink;` |
| `.none-l` | `text-decoration: none;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.under-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/text-decoration.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/text-decoration.css` — formatted
- `dist/text-decoration.min.css` — minified

## License

MIT
