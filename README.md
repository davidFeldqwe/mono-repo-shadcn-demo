# shadcn/ui monorepo template

This demo was created with the shadcn/ui monorepo template is for creating a monorepo with shadcn/ui. 

> **⚠️ Warning**  
> This is a demo and currently does not work fully. Radix packages are not being installed correctly.

## Usage

```bash
pnpm dlx shadcn@latest init
```

## Adding components

To add components to your app, run the following command at the root of your `web` app:

```bash
pnpm dlx shadcn@latest add dialog -c apps/web
```

This will place the ui components in the `packages/ui/src/components` directory.

## Tailwind

Your `tailwind.config.ts` and `globals.css` are already set up to use the components from the `ui` package.

## Using components

To use the components in your app, import them from the `ui` package.

```tsx
import { Button } from "@workspace/ui/components/ui/button"
```
