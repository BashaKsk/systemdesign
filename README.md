# systemdesign

A playground for building and demonstrating system design techniques
(caching, rate limiting, queues, idempotency, pagination, circuit breakers, etc.).

## Layout

| Folder | Stack | Dev command |
| ------ | ----- | ----------- |
| `api/` | NestJS + TypeScript | `cd api && npm run start:dev` (http://localhost:3000) |
| `web/` | React + TypeScript (Vite) | `cd web && npm run dev` (http://localhost:5173) |

## Getting started

```bash
cd api && npm install && npm run start:dev
cd web && npm install && npm run dev
```

## Techniques

Each technique gets its own module under `api/src/<technique>/` and, where it
has a UI, a page under `web/src/<technique>/`. Document the idea, trade-offs and
how to try it in a `README.md` inside that folder.

| # | Technique | API | Web | Notes |
| - | --------- | --- | --- | ----- |
| _(none yet)_ | | | | |
