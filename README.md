# Real Estate Lettings Filament

Filament 5 adapter for Lettings. Its resource is tenant-scoped and delegates
creation, updates, transitions, and failure handling to the core actions.

<!-- module-presentation-guide:begin -->
## Presentation architecture and project hosts

- Capability/source key: `liberusoftware/real-estate-lettings`.
- Actual Composer identity: `liberusoftware/real-estate-lettings-filament`.
- [Filament capability plan](https://github.com/liberusoftware/documentation/blob/main/projects/real-estate/filament/lettings.md) · [Filament standard](https://github.com/liberusoftware/documentation/blob/main/standards/FILAMENT.md) · [Module architecture](https://github.com/liberusoftware/documentation/blob/main/architecture/MODULES.md).

The application owns panel composition, routing, session integration and deployment. This module owns its focused presentation and delegates domain behavior to reviewed public owner contracts. Keep host App aliases, duplicate records and client-only authorization outside reusable package boundaries.

Documented consumer project families:

- [Real Estate](https://github.com/liberusoftware/project-real-estate-laravel-filament): Listings, sales, lettings and agency operations.

Other web, mobile and desktop presentations are listed in the [project catalog](https://github.com/liberusoftware/documentation/blob/main/projects/REPOSITORIES.md). Those skeletons provide starting structures; links do not establish feature parity, compatible releases or completed device/API integrations. Independent presentation packages keep their own Composer, npm or pub metadata.
<!-- module-presentation-guide:end -->
