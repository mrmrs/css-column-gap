# css-column-gap

Functional CSS for column-gap

## Filesize

| File | Size |
|------|------|
| `dist/column-gap.css` | 873 bytes |
| `dist/column-gap.min.css` | 589 bytes (169 Gzipped) |

## Install

```sh
npm install css-column-gap
```

## Usage

### Import

```css
@import "css-column-gap";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-column-gap/dist/column-gap.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-column-gap/dist/column-gap.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.cg-1` | `column-gap: 1rem;` |
| `.cg-2` | `column-gap: 2rem;` |
| `.cg-3` | `column-gap: 4rem;` |
| `.cg-n` | `column-gap: normal;` |
| `.cg-i` | `column-gap: inherit;` |
| `.cg-1-s` | `column-gap: 1rem;` |
| `.cg-2-s` | `column-gap: 2rem;` |
| `.cg-3-s` | `column-gap: 4rem;` |
| `.cg-n-s` | `column-gap: normal;` |
| `.cg-i-s` | `column-gap: inherit;` |
| `.cg-1-m` | `column-gap: 1rem;` |
| `.cg-2-m` | `column-gap: 2rem;` |
| `.cg-3-m` | `column-gap: 4rem;` |
| `.cg-n-m` | `column-gap: normal;` |
| `.cg-i-m` | `column-gap: inherit;` |
| `.cg-1-l` | `column-gap: 1rem;` |
| `.cg-2-l` | `column-gap: 2rem;` |
| `.cg-3-l` | `column-gap: 4rem;` |
| `.cg-n-l` | `column-gap: normal;` |
| `.cg-i-l` | `column-gap: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.cg-1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/column-gap.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/column-gap.css` — formatted
- `dist/column-gap.min.css` — minified

## License

MIT
