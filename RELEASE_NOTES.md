# BELLATOR Control Center 2026 — English R2 (N176)

**Version:** English R2 · OEM build 2.0.2.1161  
**Target:** Lecoo Bellator N176 (2025 hardware) with AMD Ryzen 9 8940HX  
**Status:** Unofficial, user-supplied release documentation  
**Development credit:** Developed with Rea (per project maintainer)

## Changes reported in R2

- Updated English UI for Settings, About, Feedback, menus and startup resources.
- English Support page with regional resources for the China-market N176.
- English-local Home including Quiet, Balanced, Beast and Battle modes.
- Restored separate fan-control handling with validation via `BellatorFanHost.exe`.
- Per-performance-mode fan caps and Restore defaults.
- Local mode allows device controls without Lenovo login.
- Steam Boost correctly indicates the Lenovo ID requirement.

## Verification reported by contributor

- Installation, upgrade, removal and fresh install checked on Windows en-US.
- One physical machine used for verification (N176 / Ryzen 9 8940HX / RTX 5060).
- Fan-mode and RPM-change checks, UI navigation stability, and invalid input checks described in `docs/Huong-dan-R2.txt`.
- User-supplied report: `docs/Kiem-thu-R2.json`.

## Known limitations

- Not tested on other N176 CPU/BIOS variants or N176B/C.
- No verified 80% battery charge limit.
- Some online content is controlled by manufacturer servers.
- Unofficial package: no manufacturer's digital signature.
- No source code or installer is included in this documentation repository.

**Binary verification SHA-256:** `8633AB20765C1CD4BCD98292303CA5727FEED2031FBD4590D0A8F5F44CA05CA0`

> Upload an installer as a Release asset only when you have the rights to redistribute the included OEM components, and only if its computed SHA-256 matches the checksum above.
