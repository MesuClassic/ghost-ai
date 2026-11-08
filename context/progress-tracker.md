# Progress Tracker

Update this file after every meaningful implementation
change.

## Current Phase

- In progress

## Current Goal

- 01 – Design System: shadcn/ui setup, UI primitives, `cn()` helper

## Completed

- 01 – Design System (`context/feature-specs/01-design-system.md`): shadcn/ui configured, Button/Card/Dialog/Input/Tabs/Textarea/ScrollArea added (unmodified), `lucide-react` installed, `cn()` in `lib/utils.ts`, dark-only theme tokens in `globals.css`, `dark` class on `<html>`. `tsc --noEmit` and `npm run build` pass.

## In Progress

- None.

## Next Up

- [First unit to build]

## Open Questions

- [Any unresolved product or technical decisions]

## Architecture Decisions

- The shadcn `base-nova` registry emits `import { cn } from "cn"` in every component. Instead of editing generated files, `tsconfig.json` maps `"cn"` to `./lib/utils`. Do not add the unrelated `cn` npm package.

## Session Notes

- [Context needed to resume work in the next session]
