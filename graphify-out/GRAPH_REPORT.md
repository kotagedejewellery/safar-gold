# Graph Report - safar-gold  (2026-10-29)

## Corpus Check
- 178 files · ~91,280 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 8 file(s) not represented in the graph (top: (none) 5, .example 1, .ico 1)

## Summary
- 1072 nodes · 2584 edges · 69 communities (58 shown, 11 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 9 edges (avg confidence: 0.89)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `dccfde76`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- createAdminClient
- AdminHargaClient.tsx
- (public)/page.tsx
- devDependencies
- eod/route.ts
- requireCapability
- OrdersClient.tsx
- analytics/cs-performance/route.ts
- (public)/harga/page.tsx
- vitest
- adjust/route.ts
- PriceApprovalPanel
- tentang/page.tsx
- OrdersClient
- internalServerError
- App Icon
- getUserRole
- eslint.config.mjs
- next
- postcss.config.mjs
- import_historis.py
- @supabase/ssr
- About Us Hero Image
- Safar Gold Store Interior Hero
- UsersClient
- cs-performance.ts
- Spec: Order Lifecycle Hardening
- regions/route.ts
- Stock Modal Design
- plan.md
- Pekerjaan Selesai
- Q: Analisa CodeGraph dan Graphify untuk project ini dan propose kesimpulannya
- Q: Apakah lifecycle order create edit cancel konsisten?
- eod/page.tsx
- dependencies
- JenisEmasClient.tsx
- analytics.ts
- admin/cs-performance/route.ts
- StockClient
- hasCapability
- migration.sql
- admin-input.ts
- analytics/route.ts
- Q: Scraping tool apa untuk fallback XAU XAG dan XPD?
- Spec: Dashboard Performa CS
- Migrasi v17 — Proteksi Data Operasional dan Pelanggan
- Analytics Chart Visual System
- Q: Task todo.md mana yang penting dikerjakan lebih dahulu tanpa overengineering?
- Stock Correction
- scripts
- Q: Dashboard statistik stock dan sumber pelanggan sebaiknya ditempatkan di mana dan berisi apa
- package.json
- admin/page.tsx
- gold-api.ts
- Gold Type Modal Design
- normalizeAppRole
- react
- stock-adjustment.ts
- Q: Apakah dashboard CS dan admin sudah saling sinkron untuk seluruh fitur?
- PriceChart.tsx
- Q: Apalagi untuk selanjutnya?
- SignaturePad
- PelangganClient.tsx
- laporan/page.tsx
- pengaturan/page.tsx

## God Nodes (most connected - your core abstractions)
1. `internalServerError()` - 74 edges
2. `createAdminClient()` - 66 edges
3. `next` - 65 edges
4. `validationError()` - 48 edges
5. `requireCapability()` - 43 edges
6. `hasCapability()` - 38 edges
7. `react` - 36 edges
8. `requireRole()` - 33 edges
9. `vitest` - 31 edges
10. `formatRupiah()` - 28 edges

## Surprising Connections (you probably didn't know these)
- `Layout / shell` --references--> `main()`  [INFERRED]
  DESIGN.md → scripts/smoke-v17.mts
- `State patterns` --references--> `AdminSkeleton()`  [INFERRED]
  DESIGN.md → src/components/admin/AdminSkeleton.tsx
- `Hardening Autentikasi dan Otorisasi API` --references--> `requireUser()`  [INFERRED]
  tasks/todo.md → src/lib/supabase/server-user.ts
- `Hardening Autentikasi dan Otorisasi API` --references--> `requireRole()`  [INFERRED]
  tasks/todo.md → src/lib/supabase/server-user.ts
- `Favicon Logo` --semantically_similar_to--> `App Icon`  [INFERRED] [semantically similar]
  public/favicon.png → src/app/icon.png

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Brand Identity Assets** — public_favicon_png, public_logo_1_webp, src_app_icon_png [EXTRACTED 0.90]
- **UI Vector Icons** — public_file_svg, public_globe_svg, public_window_svg [INFERRED 0.70]

## Communities (69 total, 11 thin omitted)

### Community 0 - "createAdminClient"
Cohesion: 0.15
Nodes (18): dynamic, GET(), addDay(), dynamic, GET(), dynamic, GET(), dynamic (+10 more)

### Community 1 - "AdminHargaClient.tsx"
Cohesion: 0.17
Nodes (12): AdminHargaClient(), fetchRole(), formatPrice(), getPrice(), getPriceLabel(), isBuyable(), formatRupiahClient(), MODE_TABS (+4 more)

### Community 2 - "(public)/page.tsx"
Cohesion: 0.08
Nodes (37): ref_fs, ref_path, ref_server_only, PublicLayout(), dynamic, HomePage(), metadata, BackToTop() (+29 more)

### Community 3 - "devDependencies"
Cohesion: 0.20
Nodes (10): devDependencies, eslint, eslint-config-next, tailwindcss, @tailwindcss/postcss, @types/node, @types/react, @types/react-dom (+2 more)

### Community 4 - "eod/route.ts"
Cohesion: 0.13
Nodes (16): dynamic, GET(), OrderItemQuantity, dynamic, EodOrder, EodOrderItem, GET(), GoldTypeCat (+8 more)

### Community 5 - "requireCapability"
Cohesion: 0.20
Nodes (11): dynamic, GET(), dynamic, GET(), dynamic, GET(), logInternalError(), parseStockRange() (+3 more)

### Community 6 - "OrdersClient.tsx"
Cohesion: 0.13
Nodes (16): BUYBACK_CATEGORIES, CartItem, CustomerLookup, LM_PRODUCTS, Order, OrderDetail, TODO: add brand selector UI for buyback if needed, RegionOption (+8 more)

### Community 7 - "analytics/cs-performance/route.ts"
Cohesion: 0.22
Nodes (8): addDays(), dynamic, GET(), isValidDate(), wibToday(), aggregateCsTeamPerformance(), adminAuth, mocks

### Community 8 - "(public)/harga/page.tsx"
Cohesion: 0.12
Nodes (21): dynamic, HargaPage(), metadata, dynamic, KalkulatorPage(), metadata, Calculator(), switchTransaction() (+13 more)

### Community 9 - "vitest"
Cohesion: 0.05
Nodes (49): Buttons, Component vocabulary, DESIGN.md — Safar Gold "Atelier", Design tokens, Fonts, Layout / shell, Radius scale, Shadows (+41 more)

### Community 10 - "adjust/route.ts"
Cohesion: 0.17
Nodes (11): dynamic, POST(), dynamic, POST(), dynamic, POST(), conflictError(), adminAuth (+3 more)

### Community 11 - "PriceApprovalPanel"
Cohesion: 0.12
Nodes (13): PreviewPriceItem, PriceApprovalPanel(), cleanNumber(), handleSaveAntamPrice(), handleSaveGlobalGoldPrice(), handleScrapeAntam(), Props, CATEGORY_LABELS (+5 more)

### Community 12 - "tentang/page.tsx"
Cohesion: 0.40
Nodes (3): metadata, timeline, values

### Community 13 - "OrdersClient"
Cohesion: 0.14
Nodes (7): OrdersClient(), applyLookup(), fetchOrders(), handleSubmit(), openEdit(), resetForm(), titleCase()

### Community 14 - "internalServerError"
Cohesion: 0.33
Nodes (10): authErrorCode(), authProviderError(), DELETE(), dynamic, GET(), POST(), PUT(), internalServerError() (+2 more)

### Community 15 - "App Icon"
Cohesion: 0.67
Nodes (3): Favicon Logo, Safar Gold Logo, App Icon

### Community 17 - "getUserRole"
Cohesion: 0.18
Nodes (15): AnalyticsPage(), dynamic, metadata, dynamic, metadata, PelangganPage(), CsPerformancePage(), dynamic (+7 more)

### Community 18 - "eslint.config.mjs"
Cohesion: 0.50
Nodes (3): eslintConfig, eslint, eslint-config-next

### Community 19 - "next"
Cohesion: 0.18
Nodes (19): nextConfig, next, POST(), DELETE(), PUT(), POST(), POST(), POST() (+11 more)

### Community 21 - "import_historis.py"
Cohesion: 0.29
Nodes (5): json, openpyxl, os, sys, urllib_request

### Community 28 - "UsersClient"
Cohesion: 0.17
Nodes (8): dynamic, metadata, UsersPage(), UserRow, UsersClient(), handleSave(), openAdd(), resetForm()

### Community 29 - "cs-performance.ts"
Cohesion: 0.23
Nodes (11): aggregateCsActivity(), aggregateCsActivityBase(), aggregateCsPerformance(), bucketKey(), CsActivityResult, CsPerformanceOrder, CsPerformanceResult, CsTeamMember (+3 more)

### Community 30 - "Spec: Order Lifecycle Hardening"
Cohesion: 0.12
Nodes (16): Boundaries, Cancel, Code Style, Commands, Create, Edit, EOD, Objective (+8 more)

### Community 32 - "Stock Modal Design"
Cohesion: 0.29
Nodes (6): Adjustment, Correction, Direction, Minimum Stock, Shared Shell, Stock Modal Design

### Community 34 - "Pekerjaan Selesai"
Cohesion: 0.06
Nodes (30): Backlog Audit Pre-Deployment, Browser, Accessibility, dan Performance, CI/CD dan Release Safety, Dashboard Analitik, Dashboard Performa CS, Definition of Done Backlog, Dependency Security, Error Handling dan Observability (+22 more)

### Community 35 - "Q: Analisa CodeGraph dan Graphify untuk project ini dan propose kesimpulannya"
Cohesion: 0.40
Nodes (4): Answer, Outcome, Q: Analisa CodeGraph dan Graphify untuk project ini dan propose kesimpulannya, Source Nodes

### Community 36 - "Q: Apakah lifecycle order create edit cancel konsisten?"
Cohesion: 0.40
Nodes (4): Answer, Outcome, Q: Apakah lifecycle order create edit cancel konsisten?, Source Nodes

### Community 37 - "eod/page.tsx"
Cohesion: 0.23
Nodes (10): Breakdown, EOD, EODClient(), handleGenerate(), load(), formatDate(), StockSnapshot, dynamic (+2 more)

### Community 38 - "dependencies"
Cohesion: 0.18
Nodes (11): dependencies, chart.js, html2canvas, jspdf, next, react, react-chartjs-2, react-dom (+3 more)

### Community 39 - "JenisEmasClient.tsx"
Cohesion: 0.12
Nodes (16): CATEGORIES, emptyForm, FormData, FormModal(), getCategoryLabel(), JenisEmasClient(), nameToSlug(), dynamic (+8 more)

### Community 40 - "analytics.ts"
Cohesion: 0.29
Nodes (10): addDays(), aggregateAnalytics(), AnalyticsMetrics, AnalyticsOrder, bucketKey(), calculateChangePercent(), getPreviousRange(), roundPercent() (+2 more)

### Community 41 - "admin/cs-performance/route.ts"
Cohesion: 0.33
Nodes (8): addDays(), dynamic, GET(), isValidDate(), loadOrders(), wibToday(), AnalyticsGrain, CsActivityOrder

### Community 43 - "hasCapability"
Cohesion: 0.12
Nodes (32): dynamic, InvoicePage(), dynamic, GET(), Context, DELETE(), dynamic, GET() (+24 more)

### Community 44 - "migration.sql"
Cohesion: 0.13
Nodes (25): idx_price_date, idx_price_type_date, idx_stock_brand, idx_stock_movements_brand, idx_stock_movements_correction_of, idx_stock_movements_created_by, public.adjust_stock_atomic(), public.app_settings (+17 more)

### Community 45 - "admin-input.ts"
Cohesion: 0.11
Nodes (38): AdminUserCreateInput, AdminUserRole, AdminUserUpdateInput, CustomerMutationInput, DailyReportRange, GOLD_TYPE_CATEGORIES, GoldTypeCategory, GoldTypeCreateInput (+30 more)

### Community 46 - "analytics/route.ts"
Cohesion: 0.48
Nodes (6): addDays(), dynamic, GET(), isValidDate(), loadOrders(), wibToday()

### Community 47 - "Q: Scraping tool apa untuk fallback XAU XAG dan XPD?"
Cohesion: 0.40
Nodes (4): Answer, Outcome, Q: Scraping tool apa untuk fallback XAU XAG dan XPD?, Source Nodes

### Community 48 - "Spec: Dashboard Performa CS"
Cohesion: 0.18
Nodes (10): Admin Team View, Boundaries, Code Style, Objective, Open Questions, Project Structure, Spec: Dashboard Performa CS, Success Criteria (+2 more)

### Community 49 - "Migrasi v17 — Proteksi Data Operasional dan Pelanggan"
Cohesion: 0.25
Nodes (7): Bukti verifikasi, Eksekusi, Migrasi v17 — Proteksi Data Operasional dan Pelanggan, Prasyarat, Rollback dan forward-fix, Smoke test otomatis, Verifikasi database

### Community 50 - "Analytics Chart Visual System"
Cohesion: 0.40
Nodes (4): Analytics Chart Visual System, Applied Views, Direction, Shared Rules

### Community 51 - "Q: Task todo.md mana yang penting dikerjakan lebih dahulu tanpa overengineering?"
Cohesion: 0.40
Nodes (4): Answer, Outcome, Q: Task todo.md mana yang penting dikerjakan lebih dahulu tanpa overengineering?, Source Nodes

### Community 52 - "Stock Correction"
Cohesion: 0.33
Nodes (5): Acceptance, Objective, Rules, Stock Correction, User Interface

### Community 55 - "scripts"
Cohesion: 0.22
Nodes (9): scripts, build, dev, lint, smoke:v17, smoke:v17:anon, smoke:v17:roles, start (+1 more)

### Community 56 - "Q: Dashboard statistik stock dan sumber pelanggan sebaiknya ditempatkan di mana dan berisi apa"
Cohesion: 0.40
Nodes (4): Answer, Outcome, Q: Dashboard statistik stock dan sumber pelanggan sebaiknya ditempatkan di mana dan berisi apa, Source Nodes

### Community 57 - "package.json"
Cohesion: 0.15
Nodes (12): name, private, version, react-dom, react-google-reviews, @supabase/supabase-js, tailwindcss, @tailwindcss/postcss (+4 more)

### Community 61 - "admin/page.tsx"
Cohesion: 0.14
Nodes (20): State patterns, AdminLoading(), dynamic, metadata, OrdersPage(), AdminDashboard(), loadData(), loadSettings() (+12 more)

### Community 62 - "gold-api.ts"
Cohesion: 0.07
Nodes (50): ref_node_crypto, AdminKontenClient(), AdminKontenPage(), dynamic, dynamic, POST(), dynamic, POST() (+42 more)

### Community 63 - "Gold Type Modal Design"
Cohesion: 0.40
Nodes (4): Add and Edit, Delete, Gold Type Modal Design, Shared Language

### Community 65 - "normalizeAppRole"
Cohesion: 0.19
Nodes (17): AdminLoginPage(), handleSubmit(), AdminLayout(), fetchUser(), getPageMeta(), pageMeta, AdminSidebar(), fetchRole() (+9 more)

### Community 66 - "react"
Cohesion: 0.06
Nodes (69): chart.js, react, react-chartjs-2, AnalyticsCharts(), countOptions, fullMoney, horizontalMoneyOptions, lineOptions (+61 more)

### Community 67 - "stock-adjustment.ts"
Cohesion: 0.13
Nodes (24): boundedOptionalText(), canGenerateEod(), canManageOrders(), finitePositive(), optionalBoundedInteger(), optionalText(), OrderItemInput, OrderType (+16 more)

### Community 74 - "Q: Apakah dashboard CS dan admin sudah saling sinkron untuk seluruh fitur?"
Cohesion: 0.40
Nodes (4): Answer, Outcome, Q: Apakah dashboard CS dan admin sudah saling sinkron untuk seluruh fitur?, Source Nodes

### Community 75 - "PriceChart.tsx"
Cohesion: 0.21
Nodes (10): crosshairPlugin, formatCompact(), formatDateLabel(), formatRupiah(), HistoryRow, periods, PriceChart(), SERIES (+2 more)

### Community 76 - "Q: Apalagi untuk selanjutnya?"
Cohesion: 0.40
Nodes (4): Answer, Outcome, Q: Apalagi untuk selanjutnya?, Source Nodes

### Community 78 - "SignaturePad"
Cohesion: 0.36
Nodes (4): SignaturePad(), getPos(), move(), start()

### Community 80 - "PelangganClient.tsx"
Cohesion: 0.11
Nodes (16): html2canvas, jspdf, Customer, CustomerOrder, PelangganClient(), InvoiceDownloadButton(), downloadPdf(), Props (+8 more)

### Community 84 - "laporan/page.tsx"
Cohesion: 0.28
Nodes (6): DailySummary, LaporanClient(), StockRow, dynamic, LaporanPage(), metadata

### Community 87 - "pengaturan/page.tsx"
Cohesion: 0.47
Nodes (3): AdminPengaturanClient(), AdminPengaturanPage(), dynamic

## Knowledge Gaps
- **371 isolated node(s):** `eslintConfig`, `nextConfig`, `name`, `version`, `private` (+366 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 476 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **11 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Work-memory lessons

**Preferred sources** — corroborated by past sessions; start here.
- `fetchInternationalGoldPrice()` (2× useful, score=1.970613076) _(code changed — re-verify)_

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `next` connect `next` to `createAdminClient`, `(public)/page.tsx`, `eod/route.ts`, `requireCapability`, `analytics/cs-performance/route.ts`, `(public)/harga/page.tsx`, `adjust/route.ts`, `tentang/page.tsx`, `internalServerError`, `getUserRole`, `@supabase/ssr`, `UsersClient`, `regions/route.ts`, `eod/page.tsx`, `admin/cs-performance/route.ts`, `hasCapability`, `analytics/route.ts`, `package.json`, `admin/page.tsx`, `gold-api.ts`, `normalizeAppRole`, `react`, `laporan/page.tsx`?**
  _High betweenness centrality (0.182) - this node is a cross-community bridge._
- **Why does `react` connect `react` to `AdminHargaClient.tsx`, `normalizeAppRole`, `(public)/page.tsx`, `eod/page.tsx`, `OrdersClient.tsx`, `JenisEmasClient.tsx`, `(public)/harga/page.tsx`, `PriceApprovalPanel`, `PriceChart.tsx`, `SignaturePad`, `PelangganClient.tsx`, `getUserRole`, `laporan/page.tsx`, `pengaturan/page.tsx`, `package.json`, `UsersClient`, `admin/page.tsx`, `gold-api.ts`?**
  _High betweenness centrality (0.096) - this node is a cross-community bridge._
- **Why does `vitest` connect `vitest` to `createAdminClient`, `react`, `stock-adjustment.ts`, `eod/route.ts`, `requireCapability`, `OrdersClient.tsx`, `analytics/cs-performance/route.ts`, `analytics.ts`, `adjust/route.ts`, `hasCapability`, `internalServerError`, `PelangganClient.tsx`, `next`, `package.json`, `cs-performance.ts`, `gold-api.ts`?**
  _High betweenness centrality (0.058) - this node is a cross-community bridge._
- **What connects `eslintConfig`, `nextConfig`, `name` to the rest of the system?**
  _371 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `(public)/page.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.07878787878787878 - nodes in this community are weakly interconnected._
- **Should `eod/route.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.13450292397660818 - nodes in this community are weakly interconnected._
- **Should `OrdersClient.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.1286549707602339 - nodes in this community are weakly interconnected._