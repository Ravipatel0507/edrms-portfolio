# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [1.0.0] — 2024-09-15

### Added
- Initial release of the Municipal EDRMS portfolio demo
- Animated splash screen with seal and entry button
- Sticky top navigation bar with user badge
- **Dashboard** — KPI stat cards (total records, pending reviews, overdue dispositions, classified records), active alerts panel, disposition schedule summary
- **Records Register** — searchable/filterable records table with status badges (Active, Under Review, Disposed, Archived), record detail modal, add/edit/dispose/archive actions, classification and security level fields
- **Retention Schedule** — categorized retention rule cards across six record series: Administrative, Financial, Legal, Infrastructure, Personnel, Planning; includes trigger, active period, total retention, and disposition method per category
- **Classification Scheme** — hierarchical browser with parent categories and nested record series; security level indicators (Public, Confidential, Restricted, Highly Restricted); cross-link to Records Register
- **Audit Log** — timestamped action log (CREATE, EDIT, VIEW, DISPOSE, CLASSIFY) with user attribution, action filter dropdown, and CSV export
- **Policy Wizard** — four-step guided workflow: scope definition, policy drafting, review assignment, and publication; policy index panel with approval status
- Toast notification system for all user actions
- Responsive layout with horizontal scroll fallback for narrow screens
- Self-contained single-file architecture (no build tools or external scripts)
- Google Fonts integration: DM Mono + Playfair Display

---

## [Unreleased]

### Planned
- `localStorage` persistence for demo session data
- Print/export to PDF for retention schedules
- Dark mode toggle
- FOIP request intake and tracking module
- Keyboard navigation and ARIA improvements for accessibility
