# nextjs-shadcn-template

Boilerplate setup for Nextjs including shadcn-ui.

## How this repo was created

```bash
npx create-next-app@latest . --typescript --tailwind --eslint --app --use-npm --no-src-dir --import-alias "@/*"
npm i next-themes
npx shadcn-ui@latest init
npx shadcn-ui@latest add --yes --overwrite accordion alert alert-dialog aspect-ratio avatar badge button calendar card checkbox collapsible combobox command context-menu data-table date-picker dialog dropdown-menu form hover-card input label menubar navigation-menu popover progress radio-group scroll-area select separator sheet skeleton slider switch table tabs textarea toast toggle tooltip
npm run dev
```

## How to run this repo after checking out

```bash
npm i
npm run dev
```
