# Master Index

| Destination family | First route | Fallback | Freshness |
|---|---|---|---|
| Social | official public page or API | public RSS/export | verify live |
| News | publisher page, RSS, Atom | licensed archive | verify live |
| Video | official page, embed, API | channel feed | verify live |
| Shopping | merchant page, catalog API | product feed | verify live |
| Docs | docs site, sitemap | downloadable reference | verify live |
| Code | public repository, release API | package registry | verify live |
| Music | artist/label page, RSS | official catalog | verify live |
| Forums | public thread, RSS | official search/API | verify live |

## Selection algorithm

1. Identify the destination and intended content.
2. Check `regions.md` for the category.
3. Check `routes.md` for a direct public route.
4. Check `blockers.md` for known constraints.
5. Use `shortcuts.md` only when the endpoint is documented and permitted.
6. Report the route and its freshness to the user.
