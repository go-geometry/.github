<p align="center"><img src="https://raw.githubusercontent.com/go-geometry/brand/main/social/go-geometry.png" alt="go-geometry" width="720"></p>

# go-geometry

🌐 **[Website](https://go-geometry.github.io)** · 📚 **[Documentation](https://go-geometry.github.io/docs/)** · 🗺️ **[Roadmap](https://github.com/go-scikit/roadmap)**

**Robust predicates, convex hulls, Delaunay triangulations, Voronoi diagrams, k-d trees and mesh generation in pure Go (CGO=0). Planned, wave 2.**

**Status: planned (wave 2).** This organization holds no library yet: only
its landing, its documentation and its brand. Its scope is robust predicates, convex hulls, Delaunay, Voronoi, k-d trees, mesh generation. The plan is in
[PLAN.md](https://github.com/go-scikit/roadmap/blob/main/PLAN.md), where it is
item 7 of wave 2 (exact predicates, Quickhull, Delaunay, Voronoi, alpha shapes, k-d trees) and, in wave 3, item 13 (meshing); its progress is in
[STATUS.md](https://github.com/go-scikit/roadmap/blob/main/STATUS.md).

## Planned packages

The names are working names; none exists as a repository yet.

| Package | Status | What it will provide |
|---------|--------|----------------------|
| §predicates§ | planned (wave 2), no repository yet | Exact geometric predicates at near floating-point cost. |
| §hull§ | planned (wave 2), no repository yet | Convex hulls, Delaunay triangulations, Voronoi diagrams and alpha shapes. |
| §nearest§ | planned (wave 2), no repository yet | k-d trees and exact nearest-neighbour search. |
| §meshgen§ | planned (wave 3), no repository yet | Constrained Delaunay triangulation and quality mesh generation, 2D then 3D. |

## Repositories

| Repo | What it is |
|------|------------|
| [**docs**](https://github.com/go-geometry/docs) | the documentation site (Hugo + Hextra), served at [/docs/](https://go-geometry.github.io/docs/) |
| [**go-geometry.github.io**](https://github.com/go-geometry/go-geometry.github.io) | the landing page (Hugo) |
| [**brand**](https://github.com/go-geometry/brand) | logo, icons and social images |

Every package will be pure Go (CGO=0), tested on the architectures the fleet's
CI covers, and validated against the reference tool of its domain.
