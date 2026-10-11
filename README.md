# gorth-ui

Shared React UI library.

## Install from GitHub

```bash
bun add @goraricorp/base
```

Or via dependency alias in another project:

```json
{
  "dependencies": {
    "@goraricorp/base": "^1.0.0"
  }
}
```

## Usage

Import library CSS once in your app entry (for Next.js App Router, put this in `app/layout.tsx`):

```tsx
import "@goraricorp/base/globals.css";
```

For custom template put this in `app/globals.css` or `styles/globals.css`

```css
@import "@goraricorp/base/globals.css";
```

```tsx
import { Button } from "@goraricorp/base/default/button";

export function Demo() {
  return <Button>Click me</Button>;
}
```

## Development

```bash
bun install
```
