# Graph Report - caveman-ponytail  (2026-06-17)

## Corpus Check
- 5 files · ~1,758 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 49 nodes · 47 edges · 8 communities (3 shown, 5 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `46bac3d0`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 118|Community 118]]
- [[_COMMUNITY_Community 364|Community 364]]
- [[_COMMUNITY_Community 518|Community 518]]
- [[_COMMUNITY_Community 519|Community 519]]

## God Nodes (most connected - your core abstractions)
1. `main()` - 3 edges
2. `commit_message()` - 2 edges
3. `git()` - 2 edges
4. `Caveman + Ponytail + graphify` - 2 edges
5. `Explorar / entender cualquier parte del sistema # (no obligatorio)` - 2 edges
6. `Rotación inicial` - 2 edges
7. `Después de cambios grandes` - 2 edges
8. `Ver ayuda` - 2 edges
9. `Git save: add, commit (versión del README), push.` - 1 edges
10. `1.4 - Funcional, perfecto - Caveman + Ponytail + graphify (se añade graphify)` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (8 total, 5 thin omitted)

### Community 118 - "Community 118"
Cohesion: 0.06
Nodes (30): ACTIVAR GRAPHIFY #, Actualizar el mapa después de cambios, Antes de refactorizar, Comandos en terminal, cuando cambias código, Empiezas a trabajar, encontrar entry point del sistema, entender arquitectura general (+22 more)

### Community 364 - "Community 364"
Cohesion: 0.60
Nodes (4): commit_message(), git(), main(), Git save: add, commit (versión del README), push.

## Knowledge Gaps
- **35 isolated node(s):** `1.4 - Funcional, perfecto - Caveman + Ponytail + graphify (se añade graphify)`, `Caveman + Ponytail + graphify`, `Proposito:`, `Comandos en terminal`, `Proyecto nuevo` (+30 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **5 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Después de cambios grandes` connect `Community 1` to `Community 118`?**
  _High betweenness centrality (0.031) - this node is a cross-community bridge._
- **Why does `Ver ayuda` connect `Community 0` to `Community 118`?**
  _High betweenness centrality (0.031) - this node is a cross-community bridge._
- **What connects `Git save: add, commit (versión del README), push.`, `1.4 - Funcional, perfecto - Caveman + Ponytail + graphify (se añade graphify)`, `Caveman + Ponytail + graphify` to the rest of the system?**
  _36 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 118` be split into smaller, more focused modules?**
  _Cohesion score 0.06451612903225806 - nodes in this community are weakly interconnected._