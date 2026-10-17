# Graph Report - workshop_graphify  (2026-10-13)

## Corpus Check
- Large corpus: 1019 files · ~679,498 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder.

## Summary
- 7426 nodes · 21557 edges · 261 communities (241 shown, 20 thin omitted)
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 350 edges (avg confidence: 0.85)
- Token cost: 227,311 input · 0 output

## Community Hubs (Navigation)
- API Audit & Unit of Work
- API DB Test Harness
- Web App Shell & Routing
- Web API Client Layer
- Web Cart/Auth/Country Contexts
- Account Page & Localisation
- API Service Composition
- Catalog UI & Product Cards
- Seeded App Integration Fixtures
- DB Migrations
- Web Integration Journeys
- Order Detail Pages
- Trade Credit Contracts
- Checkout & Payment Services
- Product/Cart/Pricing Contracts
- Fastify Routes & Auth Plugin
- Cart Sheet & UI Primitives
- Payments & Approvals Contracts
- Company Accounts Contracts
- Custom Blend Contracts
- Catalog Product Journeys
- API Service Interfaces
- Custom Blend Resolver
- Custom Blend Page UI
- Help Content Registry
- Auth, Reset & Deletion
- Custom Blend Pricing Rules
- Playwright CLI Skill (.claude)
- Admin Credit & Invoices
- Public Errors & Bundles Contracts
- Trade Credit Rules
- Order Contracts
- Sessions & Data Export
- Company & Approval Services
- Inventory Service
- Product Page UI
- App Bootstrap & Clock
- Standing Order Service
- Trade Profile Sections
- Jobs & Notifications Contracts
- Audit Event Builder
- Cart Repository
- Credit Account Service
- Authenticated Account Routes
- Bundles & Clearance
- Quick Order Rules
- Checkout Page Tests
- Localisation Message Definitions
- Web Cart Hook & Storage
- Localisation Package Exports
- Reorder Service
- Feature Flags
- Checkout State Reducer
- Trade Credit Seed
- Variant Admin
- Translate & Lifecycle Messages
- User Admin
- Pricing & Bulk Add Rules
- Checkout Flow & Validation
- Delivery Slot Rules
- Returns Service
- Repo README & Architecture
- Country Profiles Contracts
- Review Contracts
- Saved List Contracts
- Saved List Service
- Order Repository Types
- Invoice Service
- Checkout Copy & Promo Quote
- Product Comparison Selection
- DB Seed Scenarios
- Product Reviews Hook
- Quick Order Presentation
- Admin Products & Promos Contracts
- Mailbox Contracts
- Commerce Message Catalogs
- API Error Localisation
- Admin Review Moderation UI
- Order Service & Lifecycle
- Custom Blend State
- Reorder Presentation
- Localisation Lint Script
- Audit Query
- Order Admin Routes Tests
- Credit Account Repository
- Saved Lists Presentation
- show-context.py Tool
- Reorder & Standing Order Contracts
- Playwright Media & Mocking
- Standing Orders Page
- Back-in-Stock Context
- Migration 037 Invoice Mailbox
- Catalog SQL Query
- Checkout Quote Accounting
- Admin Refunds
- Catalog Validation
- Migration 038 Payment Identity
- Product Admin Service
- Product Service & Comparison
- shadcn Components Config
- E2E Page Objects
- Catalog Category Data
- Returns Contracts
- Migration 036 Credit Invoices
- Promo Service
- Review Rules
- Reorder Route Tests
- Integration Test Runner
- Webhooks & Inventory Contracts
- Inventory Repository
- Packaging Spec Resolver
- Number Formatting
- Async Content Copy
- Company Account Routes
- Invoice Repository Interface
- Order Admin Service
- Trade Credit E2E Tests
- Web Package Deps
- Packaging Artwork SVGs
- Root npm Scripts
- Trade Account Services
- Migration 034 Order Receipt
- Powder Catalog Seed
- Review Service
- Invoice Repository
- Promo Admin Service
- Review Repository Interface
- Payment Submission Hook
- Custom Blend Evaluation Hook
- Catalog Model Types
- Saved List Repository
- Credit Hold Repository
- Custom Blend Page Tests
- Catalog Bundles & Index
- Date Formatting
- Base TS Config
- Migration 035 Trade Credit
- Return Repository
- Product Media Packaging
- Standing Orders Presentation
- Quick Order Contracts
- Product Repository
- Product Admin Repository
- Country Availability Rules
- Promo Admin Repository
- Credit Exposure Math
- Order Routes & Invoices
- Web UI Dependencies
- Catalog Query Params
- Catalog Package Manifest
- Test Profiling Script
- Playwright Test Workflow (.agents)
- Workshop E2E Planning Prompt
- API Package Manifest
- Product Similarity
- Review Repository
- Mailbox Page
- Root Package & ESLint
- Contracts Package Manifest
- Localisation Lint Visitors
- Custom Blend Journey Tests
- Custom Blend Order Tests
- Packaging Artwork Tests
- Money Formatting
- E2E README & Tooling Rules
- Job Repository
- Order Approval Routes
- Admin Product Routes
- Web Dev Dependencies
- Help Policy Messages
- Catalog Specifications
- Promo Repository
- Admin Promo Routes
- Web TS Config
- E2E TS Config
- Session Repository
- Credit Expiry & Error Mapping
- API TS Config
- Packaging Palettes
- Trade Field Validation
- Contracts Export Map
- Workshop Env Skill
- API npm Scripts
- Checkout Finalizer
- Company Invite Repository
- Password Reset Repository
- Admin Variant Routes
- Root Dev Dependencies
- Contracts Test TS Config
- API Runtime Deps
- Approval Repository
- Nav Items
- Translation Surface Test
- Vite & Vitest Config
- Catalog TS Config
- Contracts TS Config
- Localisation TS Config
- Localisation ESLint TS Config
- Company Accounts Seed
- Company Membership Repository
- Custom Blend Routes
- API Test TS Config
- Web npm Scripts
- Custom Blend Eval Tests
- Scripts ESLint TS Config
- Playwright Storage State
- Return Scenarios Seed
- Review Integration Tests
- Checkout Quote Tests
- Review Query Inputs
- Cart Routes
- Lint Fixture: Raw Route Error
- Web Trade Credit API
- Packaging Artwork Types
- Back-in-Stock Seed
- Favicon & Brand
- Lint Fixture: Display Intl
- Contracts Export ./admin-orders-list
- Contracts Export ./admin-products
- Contracts Export ./admin-promos
- Contracts Export ./admin-refunds
- Contracts Export ./admin-users
- Contracts Export ./admin-variants
- Contracts Export ./audit
- Contracts Export ./auth
- Contracts Export ./back-in-stock
- Contracts Export ./bundles
- Contracts Export ./cart
- Contracts Export ./common
- Contracts Export ./company-accounts
- Contracts Export ./country
- Contracts Export ./country-profiles
- Contracts Export ./delivery
- Contracts Export ./feature-flags
- Contracts Export ./inventory
- Contracts Export ./jobs
- Contracts Export ./mailbox
- Contracts Export ./notifications
- Contracts Export ./order-approvals
- Contracts Export ./orders
- Contracts Export ./payments
- Contracts Export ./pricing
- Contracts Export ./products
- Contracts Export ./promos
- Contracts Export ./public-errors
- Contracts Export ./quick-order
- Contracts Export ./reorder
- Contracts Export ./returns
- Contracts Export ./reviews
- Contracts Export ./saved-lists
- Contracts Export ./standing-orders
- Contracts Export ./trade-account
- Contracts Export ./trade-credit
- Contracts Export ./webhooks
- Lint Fixture: Presentation Map
- Windows URL Escaping

## God Nodes (most connected - your core abstractions)
1. `useLocalisation()` - 315 edges
2. `fetchWithResponseSchema()` - 194 edges
3. `Button` - 179 edges
4. `vitest` - 162 edges
5. `AuditContext` - 146 edges
6. `react-router-dom` - 146 edges
7. `@testing-library/react` - 129 edges
8. `react` - 126 edges
9. `sendPublicError()` - 98 edges
10. `createAppServices()` - 92 edges

## Surprising Connections (you probably didn't know these)
- `Plan output sections (Scenarios, Existing coverage, Files to read, Risks, Approach)` --semantically_similar_to--> `Spec plan file (specs/<feature>.plan.md)`  [INFERRED] [semantically similar]
  .opencode/agent/test-planner.md → .agents/skills/playwright-cli/references/test-generation.md
- `Semantic role-based locators` --semantically_similar_to--> `E2E locator and assertion guidelines`  [INFERRED] [semantically similar]
  .agents/skills/playwright-cli/references/test-generation.md → e2e/README.md
- `Static inspection only constraint` --conceptually_related_to--> `Browser tooling: Playwright CLI, never MCP`  [AMBIGUOUS]
  workshop/prompt.md → .opencode/agent/test-planner.md
- `Browser tooling: Playwright CLI, never MCP` --semantically_similar_to--> `Reuse already-running app protocol`  [INFERRED] [semantically similar]
  .opencode/agent/test-planner.md → .agents/skills/playwright-cli/SKILL.md
- `Browser tooling: Playwright CLI, never MCP` --semantically_similar_to--> `Rule: Playwright CLI, not MCP`  [INFERRED] [semantically similar]
  .opencode/agent/test-planner.md → e2e/README.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Plan/Generate/Heal Playwright test authoring flow** — _agents_skills_playwright_cli_references_test_generation_plan_generate_heal, _agents_skills_playwright_cli_references_test_generation_seed_test, _agents_skills_playwright_cli_references_test_generation_spec_plan_file, _agents_skills_playwright_cli_references_playwright_tests_debug_cli_attach, _agents_skills_playwright_cli_references_test_generation_manual_assertions [EXTRACTED 1.00]
- **Agent E2E test planning toolchain (CLI over MCP)** — workshop_prompt_qme_419, _opencode_agent_test_planner_browser_tooling_cli_only, e2e_readme_cli_not_mcp_rule, _agents_skills_playwright_cli_skill_playwright_cli_tool [INFERRED 0.75]
- **Back-in-stock notification flow** — readme_back_in_stock_alerts, readme_admin_inventory_receipt_api, readme_job_queue, readme_dev_mailbox [EXTRACTED 1.00]
- **Plan-Generate-Heal Test Authoring Flow** — _claude_skills_playwright_cli_references_test_generation_seed_test, _claude_skills_playwright_cli_references_test_generation_spec_plan_file, _claude_skills_playwright_cli_references_playwright_tests_debug_cli_attach, _claude_skills_playwright_cli_references_test_generation_generated_typescript_code, _claude_skills_playwright_cli_references_test_generation_manual_assertions, _claude_skills_playwright_cli_references_test_generation_spec_reconciliation [EXTRACTED 1.00]
- **Visual Evidence Capture for PR Review** — _claude_skills_playwright_cli_skill_screenshot_command, _claude_skills_playwright_cli_references_video_recording_hero_script, _claude_skills_playwright_cli_references_tracing_trace_files, _claude_skills_playwright_cli_references_pr_attachments_gh_attach_flag, _claude_skills_playwright_cli_references_pr_attachments_ci_failure_artifacts [INFERRED 0.85]
- **Workshop Environment Clean/Status/Restore Cycle** — _claude_skills_workshop_env_skill_clean_command, _claude_skills_workshop_env_skill_status_command, _claude_skills_workshop_env_skill_restore_command, _claude_skills_workshop_env_skill_backup_vault, _claude_skills_workshop_env_skill_manifest_json [EXTRACTED 1.00]

## Communities (261 total, 20 thin omitted)

### Community 0 - "API Audit & Unit of Work"
Cohesion: 0.02
Nodes (123): UnitOfWork, AccountDeletionServiceDependencies, AuditEventRecord, AuditEventPage, AuditWriter, Clock, backInStockError(), backInStockOk() (+115 more)

### Community 1 - "API DB Test Harness"
Cohesion: 0.03
Nodes (86): ApiConfig, loadConfig(), parseResetBaseUrl(), migrateDatabase(), migrations, closeDatabase(), openDatabase(), OpenDatabaseOptions (+78 more)

### Community 2 - "Web App Shell & Routing"
Cohesion: 0.03
Nodes (151): createAdminFeatureFlag(), deleteAdminFeatureFlag(), getAdminFeatureFlags(), updateAdminFeatureFlag(), drainAdminJobs(), getAdminJob(), getAdminJobs(), retryAdminJob() (+143 more)

### Community 3 - "Web API Client Layer"
Cohesion: 0.03
Nodes (134): token(), getAdminCreditAccount(), getAdminCreditAccountDetail, getAdminCreditAccountList, getAdminCreditAccounts(), getAdminInvoice(), getAdminInvoiceDetail, getAdminInvoiceList (+126 more)

### Community 4 - "Web Cart/Auth/Country Contexts"
Cohesion: 0.02
Nodes (114): forgotPassword(), getMe(), login(), logout(), signup(), blendItem, CartLineItemCallbacks, CONFIG_KEY (+106 more)

### Community 5 - "Account Page & Localisation"
Cohesion: 0.03
Nodes (122): deleteAccount(), exportAccountData(), getAccountPreferences(), updateAccountPreferences(), AccountSessionsRequestOptions, listAccountSessions(), revokeAccountSession(), changePassword() (+114 more)

### Community 6 - "API Service Composition"
Cohesion: 0.06
Nodes (113): createAppServices(), createUnitOfWork(), createAuditRepository(), createAuditWriter(), createBundleRepository(), createBundleService(), CartCountryVariantFact, CartLineRow (+105 more)

### Community 7 - "Catalog UI & Product Cards"
Cohesion: 0.03
Nodes (98): addBundleToCart(), getBundles(), getProductComparison(), getSimilarProducts(), ProductShelf(), ProductShelfSkeleton(), Props, NotifyWhenAvailableButton() (+90 more)

### Community 8 - "Seeded App Integration Fixtures"
Cohesion: 0.02
Nodes (69): buildApp(), deliverySlotRoutes(), mailboxRoutes(), paymentRoutes(), productsRoutes(), webhookRoutes(), login(), sessionCookie() (+61 more)

### Community 9 - "DB Migrations"
Cohesion: 0.03
Nodes (60): Migration, validateMigrations(), initialMigration, catalogColumnsMigration, promoColumnsMigration, orderUserMigration, paymentReplayResponseMigration, passwordResetTokenDigestMigration (+52 more)

### Community 10 - "Web Integration Journeys"
Cohesion: 0.02
Nodes (79): CountryBanner(), countryState, authState, cartState, countryState, savedLists, Layout(), state (+71 more)

### Community 11 - "Order Detail Pages"
Cohesion: 0.04
Nodes (94): cancelOrder(), getInvoiceForOrder, getOrder(), getOrderInvoice(), OrderRequestOptions, createReturnRequest(), fetchReturnOverview(), CardHeader() (+86 more)

### Community 12 - "Trade Credit Contracts"
Cohesion: 0.03
Nodes (104): CheckoutResult, PaymentFailureResponse, PersistedCheckoutQuoteV10, TradeCreditPaymentBody, AdminCreditAccountDetailResponse, AdminCreditAccountListQuery, AdminCreditAccountListResponse, AdminCreditAccountUpdateBody (+96 more)

### Community 13 - "Checkout & Payment Services"
Cohesion: 0.04
Nodes (64): cartMoqMinimumQuantity(), CreditPreparationError, customBlendLinesRemainEligible(), failPreparation(), PaymentPreparationContext, positiveCompanyId(), preGatewayFailureCode(), Preparation (+56 more)

### Community 14 - "Product/Cart/Pricing Contracts"
Cohesion: 0.03
Nodes (101): AdminProductVariantsParam, AdminVariant, AdminVariantClearance, AdminVariantIdParam, AdminVariantListResponse, CreateAdminVariantBody, SetAdminVariantClearanceBody, UpdateAdminVariantBody (+93 more)

### Community 15 - "Fastify Routes & Auth Plugin"
Cohesion: 0.05
Nodes (76): AppContext, WebhookError, AuthenticatedUser, authPlugin(), fastify, FastifyRequest, getAuthenticatedUser(), requireAdmin() (+68 more)

### Community 16 - "Cart Sheet & UI Primitives"
Cohesion: 0.05
Nodes (80): AccountMenu(), authState, Location(), renderMenu(), CartCustomBlendDetails(), CartLineItem(), CartLineItemProps, cartLineKey() (+72 more)

### Community 17 - "Payments & Approvals Contracts"
Cohesion: 0.03
Nodes (91): AddressLine, AddressLocality, formatPostalAddress(), FORMATTED_ADDRESS_MAX_LENGTH, PostalAddress, Postcode, SignupBody, CartIdParam (+83 more)

### Community 18 - "Company Accounts Contracts"
Cohesion: 0.03
Nodes (73): DataExportResponse, DeleteAccountBody, ExportedInvoice, ExportedInvoiceFacts, ExportedInvoiceLifecycleIntegrity, ExportedUserId, RevokeSessionParams, SessionListResponse (+65 more)

### Community 19 - "Custom Blend Contracts"
Cohesion: 0.03
Nodes (81): RemoveFromCartBody, CreateCustomBlendBody, CUSTOM_BLEND_MAX_BASE_PERCENTAGE, CUSTOM_BLEND_MAX_INGREDIENT_PERCENTAGE, CUSTOM_BLEND_MAX_INGREDIENT_TOTAL, CUSTOM_BLEND_MAX_INGREDIENT_TOTAL_PERCENTAGE, CUSTOM_BLEND_MAX_INGREDIENTS, CUSTOM_BLEND_MAX_PERCENTAGE (+73 more)

### Community 20 - "Catalog Product Journeys"
Cohesion: 0.04
Nodes (50): ComparisonItem, getBestsellers(), getCategories(), getProductFilterOptions(), getProducts(), GetProductsParams, getRelatedProducts(), RelaxedProduct (+42 more)

### Community 21 - "API Service Interfaces"
Cohesion: 0.04
Nodes (16): AuditContext, AuthService, BackInStockResult, BackInStockService, CartService, VariantAdminService, CustomBlendService, OrderService (+8 more)

### Community 22 - "Custom Blend Resolver"
Cohesion: 0.05
Nodes (52): createCustomBlendRepository(), CustomBlendCandidateQuery, CustomBlendFactRow, CustomBlendRepository, escapeLike(), normalizeCandidateQuery(), supportedMixingGroupPlaceholders, basePresentation() (+44 more)

### Community 23 - "Custom Blend Page UI"
Cohesion: 0.05
Nodes (50): getCustomBlendBases(), BagArtwork(), BagArtworkProps, ProductLabel(), HeroSection(), heroVessels, resolveCatalogPackagingPalette(), PackagingArtwork() (+42 more)

### Community 24 - "Help Content Registry"
Cohesion: 0.06
Nodes (58): renderFooter(), faqArticle, articleIds, ContentLink, getProductCommerceLinks(), getProductFactLinks(), helpArticles, helpContentRegistry (+50 more)

### Community 25 - "Auth, Reset & Deletion"
Cohesion: 0.06
Nodes (31): AccountDeletionRepository, createAccountDeletionRepository(), AccountDeletionResult, createAccountDeletionService(), isValidDisplayName(), isValidEmail(), isValidPassword(), normalizeDisplayName() (+23 more)

### Community 26 - "Custom Blend Pricing Rules"
Cohesion: 0.07
Nodes (59): assertCustomBlendCompatibility(), assertCustomBlendPigmentCap(), calculateCustomBlendComponentPrice, calculateCustomBlendComponentPrices, calculateCustomBlendComponentPricing(), calculateCustomBlendComponentWeightGrams, calculateCustomBlendLinePricing(), calculateCustomBlendLineWeightGrams (+51 more)

### Community 27 - "Playwright CLI Skill (.claude)"
Cohesion: 0.05
Nodes (51): Inspecting Element Attributes, --debug=cli Test Debugging and attach, PLAYWRIGHT_HTML_OPEN=never, Running and Debugging Playwright Tests, Attaching Screenshots and Videos to Pull Requests, CI Failure Artifact Attachment, gh --attach Flag (gh 2.99+), Advanced Mocking via page.route in run-code (+43 more)

### Community 28 - "Admin Credit & Invoices"
Cohesion: 0.05
Nodes (25): INVOICE_ERROR_CODES, InvoiceErrorCode, messages, InvoiceService, CreditAccountService, CreditHoldRow, adminCreditRoutes(), AdminCreditRouteServices (+17 more)

### Community 29 - "Public Errors & Bundles Contracts"
Cohesion: 0.04
Nodes (49): AddBundleToCartBody, BundleDescription, BundleKey, BundleMutationConflictResponse, BundleName, BundleUnavailableConflictResponse, BundleVariantDetail, CuratedBundle (+41 more)

### Community 30 - "Trade Credit Rules"
Cohesion: 0.08
Nodes (51): availableCreditCents, calculateAvailableCredit(), calculateAvailableCreditCents, calculateCreditExposure(), calculateDueAt, calculateHeldExposure(), calculateInvoiceAmounts, calculateInvoiceNetCents() (+43 more)

### Community 31 - "Order Contracts"
Cohesion: 0.05
Nodes (50): AdminOrderDetailAccountingIntegrity, AdminOrderDetailFields, AdminOrderDetailResponse, AdminOrderListItem, AdminOrderRefundPayment, AdminOrdersListResponse, UtcIsoInstant, AdminOrderListQuery (+42 more)

### Community 32 - "Sessions & Data Export"
Cohesion: 0.06
Nodes (34): createDataExportService(), DataExportService, DataExportServiceDependencies, listExportOwnedInvoices(), toExportedInvoice(), toPublicUser(), SessionRecord, SessionUser (+26 more)

### Community 33 - "Company & Approval Services"
Cohesion: 0.06
Nodes (29): companyError(), CompanyErrorCode, companyOk(), CompanyInviteRow, CompanyMembershipRow, CompanyRepository, CompanyRow, ActiveCompanyMembership (+21 more)

### Community 34 - "Inventory Service"
Cohesion: 0.08
Nodes (25): BundleAvailabilityDependencies, CartAvailabilityDependencies, aggregateInventoryDemand(), isPreparedReservationExpired(), positiveInteger(), receiptFingerprint(), splitInventoryReservation(), allocateFromRows() (+17 more)

### Community 35 - "Product Page UI"
Cohesion: 0.05
Nodes (28): getProduct(), ProductMedia(), packaging, buildRows(), ComparisonMatrix(), ComparisonMatrixProps, MatrixProduct, MatrixRow (+20 more)

### Community 36 - "App Bootstrap & Clock"
Cohesion: 0.07
Nodes (25): AppDependencies, AppServices, DEFAULT_WEBHOOK_SECRET, AccountDeletionService, AuditReadService, Clock, BundleService, CheckoutService (+17 more)

### Community 37 - "Standing Order Service"
Cohesion: 0.08
Nodes (15): standingOrderError(), StandingOrderErrorCode, standingOrderOk(), StandingOrderResult, StandingOrderRepository, StandingOrderRow, StandingOrderRunRow, countOutcomes() (+7 more)

### Community 38 - "Trade Profile Sections"
Cohesion: 0.13
Nodes (35): createBillingEntity(), createDeliverySite(), listBillingEntities(), listDeliverySites(), retireBillingEntity(), retireDeliverySite(), TradeAccountRequestOptions, updateBillingEntity() (+27 more)

### Community 39 - "Jobs & Notifications Contracts"
Cohesion: 0.06
Nodes (35): BackInStockStatus, BackInStockSubscription, BackInStockSubscriptionIdParam, BackInStockSubscriptionListResponse, CreateBackInStockSubscriptionBody, SafePositiveInteger, UtcIsoInstant, AdminJob (+27 more)

### Community 40 - "Audit Event Builder"
Cohesion: 0.13
Nodes (38): approvalEntity(), asyncEntity(), auditActionSet, AuditActor, AuditEventValidationError, backInStockEntity(), buildAuditEvent(), cartEntity() (+30 more)

### Community 41 - "Cart Repository"
Cohesion: 0.12
Nodes (17): collectUnavailableComponentVariantIds(), CartRepository, addConfiguredItem(), addManyItems(), blockedInCountry(), cartLineRowToProductBase(), getCart(), hydrateCustomBlend() (+9 more)

### Community 42 - "Credit Account Service"
Cohesion: 0.10
Nodes (34): CreditAccountOrder, AcquireCreditHoldInput, canonicalize(), commandInput(), COUNTRIES, createCompanyCreditAccountService, createCreditAccountService(), createTradeCreditAccountService (+26 more)

### Community 43 - "Authenticated Account Routes"
Cohesion: 0.08
Nodes (33): BackInStockErrorCode, requireAuth(), accountPreferencesRoutes(), auditContext(), accountSessionRoutes(), AccountSessionRouteServices, auditContext(), sendSessionError() (+25 more)

### Community 44 - "Bundles & Clearance"
Cohesion: 0.08
Nodes (27): BundleComponentRow, BundleJoinRow, BundleRepository, BundleRow, BundleMutationResult, BundleUnavailable, isVisible(), now() (+19 more)

### Community 45 - "Quick Order Rules"
Cohesion: 0.11
Nodes (30): VariantWithProductRow, quickOrderError(), QuickOrderErrorCode, quickOrderOk(), QuickOrderResult, addedOutcome(), assembleQuickOrderOutcomes(), buildQuickOrderDemand() (+22 more)

### Community 46 - "Checkout Page Tests"
Cohesion: 0.14
Nodes (28): DeliverySlotOptionsRequestOptions, getDeliverySlotOptions(), pay(), payCard(), PaymentRequestOptions, payTradeCredit(), validatePromo(), resolvedBlend (+20 more)

### Community 47 - "Localisation Message Definitions"
Cohesion: 0.08
Nodes (26): CHECKOUT_MESSAGES, checkoutMessages, assertNonEmpty(), assertPlaceholderParity(), assertTemplate(), CountryMessageSet, defineMessages(), ExplicitPluralTemplate (+18 more)

### Community 48 - "Web Cart Hook & Storage"
Cohesion: 0.13
Nodes (30): isMissingCartError(), createCartClient(), createAndLoad(), loadOrCreate(), recoverMissingCart(), CartAction, CartClearTarget, CartErrorState (+22 more)

### Community 49 - "Localisation Package Exports"
Cohesion: 0.06
Nodes (35): import, types, dependencies, @shop/contracts, devDependencies, tsx, exports, ./defineMessages (+27 more)

### Community 50 - "Reorder Service"
Cohesion: 0.11
Nodes (26): BulkAddOutcome, BulkAddSkipReason, BulkAddResult, reorderError(), ReorderErrorCode, reorderOk(), ReorderResult, assembleReorderOutcomes() (+18 more)

### Community 51 - "Feature Flags"
Cohesion: 0.10
Nodes (20): createFeatureFlagRepository(), FeatureFlagCreate, FeatureFlagRecord, FeatureFlagRepository, FeatureFlagRow, FeatureFlagUpdate, toRecord(), FeatureFlagCreateInput (+12 more)

### Community 52 - "Checkout State Reducer"
Cohesion: 0.07
Nodes (33): billingDraftIsEmpty(), BillingField, billingFields, CardField, CheckoutBilling, CheckoutConflict, CheckoutDelivery, CheckoutPaymentMethod (+25 more)

### Community 53 - "Trade Credit Seed"
Cohesion: 0.10
Nodes (33): allocateSeedInvoiceNumber(), billingEntity(), CompanyRow, DEMO_TRADE_CREDIT_SCENARIO_KEYS, dueAt(), ensureCreditHold(), ensureInvoice(), ensureInvoiceMailbox() (+25 more)

### Community 54 - "Variant Admin"
Cohesion: 0.09
Nodes (18): BackInStockVariantReader, VariantRow, ClearanceRecord, CreateVariantRecord, UpdateVariantRecord, VariantAdminRepository, assertExistingClearanceRemainsValid(), assertVariantValues() (+10 more)

### Community 55 - "Translate & Lifecycle Messages"
Cohesion: 0.08
Nodes (23): runEntityMutation(), runSiteMutation(), MessageCatalog, MessageTemplate, ORDER_LIFECYCLE_MESSAGES, OrderLifecycleMessageKey, orderLifecycleMessages, orderMessages (+15 more)

### Community 56 - "User Admin"
Cohesion: 0.10
Nodes (16): AdminUserRecord, AdminUserRow, createUserAdminRepository(), toRecord(), UserAdminRepository, requireReason(), requireRole(), requireUser() (+8 more)

### Community 57 - "Pricing & Bulk Add Rules"
Cohesion: 0.15
Nodes (27): aggregateBulkAddDemand(), BULK_ADD_SKIP_REASONS, BulkAddAvailability, BulkAddClassification, BulkAddGroup, BulkAddVariantRow, classifyBulkAddGroup(), ClassifyBulkAddGroupInput (+19 more)

### Community 58 - "Checkout Flow & Validation"
Cohesion: 0.14
Nodes (27): getTradeCreditSummary(), checkRequiredText(), checkText(), validatePostalAddressDraft(), isEligibleForPromo(), createCartQuoteKey(), FieldErrors, selectAppliedPromo() (+19 more)

### Community 59 - "Delivery Slot Rules"
Cohesion: 0.11
Nodes (22): DeliveryLine, quoteCartDelivery(), quoteDelivery(), addBusinessDays(), calculateLeadTime(), CalculateLeadTimeInput, deliveryAnchorDay(), isBusinessDay() (+14 more)

### Community 60 - "Returns Service"
Cohesion: 0.17
Nodes (24): ReturnDomainError, mapRefundSummary(), mapReturnRequest(), RefundRow, ReturnItemRow, ReturnRequestRow, ActiveReservation, allocateOrderDiscountByLine() (+16 more)

### Community 61 - "Repo README & Architecture"
Cohesion: 0.11
Nodes (28): Web app index.html entry, global-setup.ts (waits for API), QArefully Materials Exchange README, Admin inventory receipt API, Admin lifecycle API (shipments, transitions, tracking), API server (Fastify, port 3001), Back-in-stock alerts, Clearance fixtures (+20 more)

### Community 62 - "Country Profiles Contracts"
Cohesion: 0.13
Nodes (21): CountryCode, CN_COUNTRY_PROFILE, DE_COUNTRY_PROFILE, ES_COUNTRY_PROFILE, FR_COUNTRY_PROFILE, COUNTRY_PROFILES, countryProfile(), PL_COUNTRY_PROFILE (+13 more)

### Community 63 - "Review Contracts"
Cohesion: 0.08
Nodes (29): AdminReviewModerationBody, AdminReviewModerationResponse, AdminReviewQueueItem, AdminReviewQueueQuery, AdminReviewQueueResponse, AdminReviewReport, CreateReviewBody, CreateReviewReportBody (+21 more)

### Community 64 - "Saved List Contracts"
Cohesion: 0.07
Nodes (30): AddSavedListItemBody, AddSavedListToCartBody, CreateSavedListBody, RenameSavedListBody, SafeNonNegativeInteger, SafePositiveInteger, SaveCartAsListBody, SavedListAddToCartResponse (+22 more)

### Community 65 - "Saved List Service"
Cohesion: 0.13
Nodes (26): BulkAddRequest, ReorderRequestPlan, savedListError(), SavedListErrorCode, savedListOk(), SavedListItemRow, SavedListRow, assembleSavedListCartOutcomes() (+18 more)

### Community 66 - "Order Repository Types"
Cohesion: 0.08
Nodes (7): OrderAccessRepository, OrderRepository, CreateOrderLineVariantSnapshot, CreateOrderParams, LifecycleEventInput, OrderState, PersistedShipment

### Community 67 - "Invoice Service"
Cohesion: 0.16
Nodes (29): InvoiceDomainError, actorId(), assertDocumentMatches(), assertIssueReplayMatches(), canonicalFingerprint(), compareOptionalSnapshot(), createInvoiceService(), deriveInvoiceLines() (+21 more)

### Community 68 - "Checkout Copy & Promo Quote"
Cohesion: 0.13
Nodes (26): checkoutCodeToken(), checkoutErrorState(), CheckoutTranslate, localizeCheckoutError(), localizeLabel(), localizeTradeCreditError(), safeMessageParams(), tradeCreditPaymentErrorKeys (+18 more)

### Community 69 - "Product Comparison Selection"
Cohesion: 0.12
Nodes (23): addComparisonId(), clearComparisonIds(), ComparisonDraftChange, comparisonPath(), ComparisonSelectionParseResult, MAX_COMPARISON_PRODUCTS, MIN_COMPARISON_PRODUCTS, normalizeComparisonDraftIds() (+15 more)

### Community 70 - "DB Seed Scenarios"
Cohesion: 0.08
Nodes (25): ReviewScenario, SCENARIOS, seedReviewScenarios(), FAVOURITE_SLUGS, findUserId(), MONTHLY_RESTOCK_ITEMS, seedSavedLists(), ADMIN_DEACTIVATED_PROMO (+17 more)

### Community 71 - "Product Reviews Hook"
Cohesion: 0.12
Nodes (23): addHelpfulVote(), createProductReview(), createReviewReport(), deleteReview(), getMyProductReview(), getProductReviews(), GetProductReviewsParams, removeHelpfulVote() (+15 more)

### Community 72 - "Quick Order Presentation"
Cohesion: 0.16
Nodes (25): Props, QuickOrderOutcomeList(), ResultBody(), added(), emptyCart, renderList(), skipped(), adjustedOutcomes() (+17 more)

### Community 73 - "Admin Products & Promos Contracts"
Cohesion: 0.08
Nodes (27): AdminCatalogCategory, AdminMixingGroup, AdminProduct, AdminProductIdParam, AdminProductListQuery, AdminProductListResponse, ConsumptionClassification, CreateAdminProductBody (+19 more)

### Community 74 - "Mailbox Contracts"
Cohesion: 0.08
Nodes (27): CompanyInviteMailboxTemplate, CompanyInviteMailboxTemplateParams, CompanyName, DataExportReadyMailboxTemplate, DataExportReadyMailboxTemplateParams, InvoiceIssuedMailboxDescriptor, InvoiceIssuedMailboxMessage, LegacyMailboxKind (+19 more)

### Community 75 - "Commerce Message Catalogs"
Cohesion: 0.08
Nodes (14): ADMIN_COMMERCE_MESSAGES, AdminCommerceMessageKey, adminCommerceMessages, CART_MESSAGES, CartMessageKey, cartMessages, COMMON_MESSAGES, commonMessages (+6 more)

### Community 76 - "API Error Localisation"
Cohesion: 0.09
Nodes (24): ADMIN_CATALOG_MESSAGES, AdminCatalogMessageKey, AdminCatalogMessages, adminDateTimeInputValue(), localizeAdminError(), messageParams(), ADMIN_DIAGNOSTICS_MESSAGES, AdminDiagnosticsMessageKey (+16 more)

### Community 77 - "Admin Review Moderation UI"
Cohesion: 0.11
Nodes (22): getAdminReviewQueue(), GetAdminReviewQueueParams, moderateAdminReview(), restoreAdminReview(), actionLabel(), AdminReviewModerationPage(), errorParams(), messageFor() (+14 more)

### Community 78 - "Order Service & Lifecycle"
Cohesion: 0.15
Nodes (19): messages, ORDER_ERROR_CODES, OrderDomainError, OrderErrorCode, aggregateOrderStatus(), AllocatedLine, AllocationShipment, assertCanCancel() (+11 more)

### Community 79 - "Custom Blend State"
Cohesion: 0.13
Nodes (24): balanceEvenlyPercentages(), clampedPercentageForIngredient(), CustomBlendEvent, CustomBlendMessage, CustomBlendMessageParam, customBlendReducer(), customBlendValidation, derivedBasePercentage() (+16 more)

### Community 80 - "Reorder Presentation"
Cohesion: 0.17
Nodes (21): Props, ResultBody(), added(), emptyCart, renderList(), skipped(), BUY_AGAIN_FAILURE_KEY, BUY_AGAIN_FAILURE_MESSAGE (+13 more)

### Community 81 - "Localisation Lint Script"
Cohesion: 0.13
Nodes (25): addFinding(), checkRepository(), fixtureFiles(), IMMUTABLE_BRAND, inspectFile(), isCanonicalPath(), isImmutableBrand(), isReplyResponseReceiver() (+17 more)

### Community 82 - "Audit Query"
Cohesion: 0.12
Nodes (16): AuditAction, AuditEntityType, AuditEventInput, BuiltAuditEvent, userContext, actionSet, AuditEventQueryInput, AuditQueryError (+8 more)

### Community 83 - "Order Admin Routes Tests"
Cohesion: 0.11
Nodes (21): createOrderAdminRepository(), createOrderAdminService(), fixture(), AccountingRow, EventRow, hydrateOrderAccounting(), hydrateOrderCustomBlend(), hydrateOrderSlot() (+13 more)

### Community 84 - "Credit Account Repository"
Cohesion: 0.08
Nodes (14): accountOrderColumns, accountOrderKeys, accountStates, createCompanyCreditAccountRepository, createTradeCreditAccountRepository, CreditAccountEventRow, CreditAccountListQuery, CreditAccountListRows (+6 more)

### Community 85 - "Saved Lists Presentation"
Cohesion: 0.18
Nodes (21): ResultBody(), SavedListOutcomeList(), renderList(), response, countFormatter(), countItems(), defaultTranslate, resolve() (+13 more)

### Community 86 - "show-context.py Tool"
Cohesion: 0.17
Nodes (14): clip(), cmd_growth(), cmd_list(), cmd_show(), find_slug_dir(), fmt(), is_message(), load() (+6 more)

### Community 87 - "Reorder & Standing Order Contracts"
Cohesion: 0.09
Nodes (23): CartLineConfigKey, ReorderLineOutcome, ReorderLineOutcomeFields, ReorderLineStatus, ReorderOutcomeStatusPair, ReorderRequestBody, ReorderResponse, ReorderSkipReason (+15 more)

### Community 88 - "Playwright Media & Mocking"
Cohesion: 0.11
Nodes (23): Inspecting Element Attributes, eval-based element attribute inspection, Attaching Screenshots and Videos to Pull Requests, CI failure screenshot/video attachment, gh --attach flag (gh 2.99+), Request Mocking, Advanced mocking via run-code (page.route), route / unroute network mocking (+15 more)

### Community 89 - "Standing Orders Page"
Cohesion: 0.19
Nodes (20): getSavedLists(), createStandingOrder(), deleteStandingOrder(), getStandingOrderRuns(), getStandingOrders(), path(), runStandingOrderNow(), updateStandingOrder() (+12 more)

### Community 90 - "Back-in-Stock Context"
Cohesion: 0.11
Nodes (19): authState, comparisonStorage, facts, Path(), product(), renderJourney(), soldOutVariant, BackInStockContext (+11 more)

### Community 91 - "Migration 037 Invoice Mailbox"
Cohesion: 0.12
Nodes (19): assertIndexCollisions(), columnNames(), ForeignKeyRow, hasCompletedSchema(), hasExpectedColumns(), hasExpectedDescriptorCheck(), hasExpectedForeignKeys(), hasExpectedIndex() (+11 more)

### Community 92 - "Catalog SQL Query"
Cohesion: 0.17
Nodes (15): CatalogQueryError, CatalogSpecificationFilter, normalizeCatalogQuery(), NormalizedCatalogQuery, parseCatalogDate(), parseSpecification(), CatalogSpecificationKey, availableToSellSql (+7 more)

### Community 93 - "Checkout Quote Accounting"
Cohesion: 0.15
Nodes (21): AliasCandidate, assertMoney(), assertRate(), assertTerms(), CheckoutQuoteAccounting, CheckoutQuoteCheckout, CheckoutQuoteFacts, CreditTerms (+13 more)

### Community 94 - "Admin Refunds"
Cohesion: 0.13
Nodes (10): AdminRefundError, AdminRefundRecord, createAdminRefundService(), RefundablePayment, Row, fixture(), createRefundGateway(), RefundGateway (+2 more)

### Community 95 - "Catalog Validation"
Cohesion: 0.14
Nodes (22): isNormalizedCatalogKey(), isUtcIsoInstant(), ALL_CANONICAL_IDS, ALLOWED_CONSUMPTION_CLASSIFICATIONS, ALLOWED_MIXING_GROUPS, assertUnique(), CANONICAL_IDS_LEGACY, CANONICAL_IDS_NEW (+14 more)

### Community 96 - "Migration 038 Payment Identity"
Cohesion: 0.15
Nodes (21): assertForeignKeysClean(), buyerIdentityExpression(), countRows(), explicitSchemaObjects(), ForeignKeyRow, hasCompletedSchema(), hasTable(), hasUserForeignKey() (+13 more)

### Community 97 - "Product Admin Service"
Cohesion: 0.18
Nodes (18): createProductAdminRepository(), ProductAdminInsert, ProductAdminUpdate, writeColumns, assertCategory(), assertConsumptionClassification(), assertInteger(), assertMixingGroup() (+10 more)

### Community 98 - "Product Service & Comparison"
Cohesion: 0.16
Nodes (9): buildComparisonItems(), ComparisonSelectionError, parseComparisonIds(), CustomerProductRow, ProductList, createProductService(), now(), ProductService (+1 more)

### Community 99 - "shadcn Components Config"
Cohesion: 0.09
Nodes (21): aliases, components, hooks, lib, ui, utils, iconLibrary, menuAccent (+13 more)

### Community 100 - "E2E Page Objects"
Cohesion: 0.13
Nodes (5): API_URL, BASE_URL, CatalogPage, HomePage, @playwright/test

### Community 101 - "Catalog Category Data"
Cohesion: 0.19
Nodes (15): CATALOG_ARTWORK_IDS, CATALOG_PRODUCTS, catalogProductById, catalogProductByImageSetId, catalogProductBySlug, bakingPantryProducts, drinksProducts, gardenOutdoorsProducts (+7 more)

### Community 102 - "Returns Contracts"
Cohesion: 0.16
Nodes (20): AdminDecisionBody, AdminReceiveBody, AdminRefundBody, AdminReturnListQuery, AdminReturnListResponse, CreateReturnRequestBody, NonNegativeVersion, RefundSummary (+12 more)

### Community 103 - "Migration 036 Credit Invoices"
Cohesion: 0.15
Nodes (17): countRows(), createInvoiceEvents(), createInvoices(), createInvoiceStates(), creditInvoicesMigration, explicitSchemaObjects(), ForeignKeyRow, hasColumn() (+9 more)

### Community 104 - "Promo Service"
Cohesion: 0.14
Nodes (15): createCheckoutQuote(), resolvedLineUnitPrice(), quoteTotalBeforeReservation(), asValidPromo(), calculateDiscount(), createPromoService(), invalid(), PromoValidation (+7 more)

### Community 105 - "Review Rules"
Cohesion: 0.19
Nodes (17): normalizeAdminReviewQueueQuery(), normalizeBoundedPositiveInteger(), NormalizedReviewListQuery, NormalizedReviewWrite, normalizeReviewListQuery(), normalizeReviewReport(), normalizeReviewWrite(), REVIEW_BODY_MAX_LENGTH (+9 more)

### Community 106 - "Reorder Route Tests"
Cohesion: 0.12
Nodes (16): App, cookieValue(), createCart(), createPersistedBlend(), Fixture, line(), login(), Lot (+8 more)

### Community 107 - "Integration Test Runner"
Cohesion: 0.15
Nodes (14): API_ROOT, buildChildTestArgs(), hasCliConcurrency(), hasExplicitTestPath(), OPTIONS_WITH_VALUES, readConcurrencyOverride(), assertForeignKeys(), ChildResult (+6 more)

### Community 108 - "Webhooks & Inventory Contracts"
Cohesion: 0.12
Nodes (17): Uuid, InventoryConflictCode, InventoryReceiptAllocation, InventoryReceiptBody, InventoryReceiptBodyLegacy, InventoryReceiptResponse, InventoryReceiptResponseLegacy, AdminCapturedWebhook (+9 more)

### Community 110 - "Packaging Spec Resolver"
Cohesion: 0.15
Nodes (19): CATEGORY_PREFIX, doseFromFacts(), gradeFromFacts(), hasCategoryFacts(), hazardFromFacts(), KegTone, lotFor(), mixingGroupLabel() (+11 more)

### Community 111 - "Number Formatting"
Cohesion: 0.16
Nodes (17): assertNumber(), formatCount(), formatDecimal(), formatNumber(), formatter(), formatWeight(), formatWeightGrams(), NumberCountry (+9 more)

### Community 112 - "Async Content Copy"
Cohesion: 0.15
Nodes (19): ASYNC_CONTENT, ASYNC_CONTENT_MESSAGES, ASYNC_MESSAGES, asyncContent, AsyncContentCatalog, AsyncContentKey, asyncContentMessages, asyncMessages (+11 more)

### Community 113 - "Company Account Routes"
Cohesion: 0.17
Nodes (7): CompanyResult, CompanyService, COMPANY_ERROR_STATUS, companyAccountsRoutes(), CompanyAccountsRouteServices, context(), sendCompanyError()

### Community 115 - "Order Admin Service"
Cohesion: 0.15
Nodes (12): AdminOrderListItem, AdminOrderListQuery, AdminOrderRefundPayment, OrderAdminRepository, orderStatuses, optionalIso(), optionalText(), OrderAdminError (+4 more)

### Community 116 - "Trade Credit E2E Tests"
Cohesion: 0.12
Nodes (12): cardPaymentPayload(), CompanyFacts, createCart(), creditPaymentPayload(), errorCode(), InvoiceFacts, login(), NOW (+4 more)

### Community 117 - "Web Package Deps"
Cohesion: 0.11
Nodes (18): @shop/contracts, @shop/localisation, @sinclair/typebox, name, private, type, version, clsx (+10 more)

### Community 118 - "Packaging Artwork SVGs"
Cohesion: 0.30
Nodes (14): KegArtwork(), KraftSackArtwork(), VesselArtworkProps, cond(), CondOptions, condWidth(), ghs(), irritant() (+6 more)

### Community 119 - "Root npm Scripts"
Cohesion: 0.11
Nodes (19): scripts, check:localisation, dev, format, format:fix, lint, postinstall, reset (+11 more)

### Community 120 - "Trade Account Services"
Cohesion: 0.17
Nodes (4): TradeAccountServices, BillingEntityService, DeliverySiteService, TradeAccountResult

### Community 121 - "Migration 034 Order Receipt"
Cohesion: 0.14
Nodes (13): columnNames(), ForeignKeyRow, hasCompletedSchema(), hasExpectedColumns(), hasExpectedForeignKey(), hasExpectedIndex(), IndexInfoRow, IndexListRow (+5 more)

### Community 122 - "Powder Catalog Seed"
Cohesion: 0.12
Nodes (16): DEMO_ORDER_SCENARIO_KEYS, product(), ProductLine, Scenario, ScenarioEvent, ScenarioKey, SCENARIOS, seedOrderScenarios() (+8 more)

### Community 123 - "Review Service"
Cohesion: 0.18
Nodes (10): asOwnedReview(), asReview(), engagement(), normalize(), now(), requireOwner(), requirePublishedEngageable(), requireReview() (+2 more)

### Community 124 - "Invoice Repository"
Cohesion: 0.15
Nodes (14): failCorrupt(), InvoiceAdminListQuery, InvoiceEventRow, InvoiceExposureRelease, InvoiceInsert, InvoiceLifecycleUpdate, InvoiceOrderReview, InvoicePaymentReview (+6 more)

### Community 125 - "Promo Admin Service"
Cohesion: 0.22
Nodes (16): PromoAdminWrite, categorySet, countrySet, normalizeCountries(), normalizeWrite(), nullableCategory(), nullableInstant(), nullableNonNegativeInteger() (+8 more)

### Community 126 - "Review Repository Interface"
Cohesion: 0.11
Nodes (3): ReviewRepository, NormalizedAdminReviewQueueQuery, ReviewSort

### Community 127 - "Payment Submission Hook"
Cohesion: 0.22
Nodes (15): readyPaymentState(), cardFields, CheckoutEvent, createIdempotencyKey(), initialCheckoutState(), buildPaymentBody(), buildPaymentPayload, checkoutConflict() (+7 more)

### Community 128 - "Custom Blend Evaluation Hook"
Cohesion: 0.18
Nodes (17): CustomBlendDraftIngredient, CustomBlendState, CustomBlendEvaluationError, CustomBlendEvaluationOptions, CustomBlendEvaluationResult, DraftValues, emptyStoredEvaluation, errorDescriptor() (+9 more)

### Community 129 - "Catalog Model Types"
Cohesion: 0.11
Nodes (17): BaseProductFacts, CatalogCategory, CatalogVariant, CategoryFacts, CleaningFacts, ConsumptionClassification, DeliveryClass, EdibleFacts (+9 more)

### Community 132 - "Custom Blend Page Tests"
Cohesion: 0.15
Nodes (14): addCustomBlend, component(), configuredLine(), countryState, CREATED_CONFIG_KEY, EDIT_CONFIG_KEY, evaluationFor(), mockCart() (+6 more)

### Community 133 - "Catalog Bundles & Index"
Cohesion: 0.12
Nodes (6): CatalogBundle, CatalogBundleComponent, CURATED_BUNDLES, CATALOG_CATEGORIES, CATALOG_CREATED_AT_BY_ID, MIXING_GROUPS

### Community 134 - "Date Formatting"
Cohesion: 0.20
Nodes (16): CIVIL_PRESET_OPTIONS, DateCountry, DateFormatOptions, dateFormatters, DatePreset, formatCivilDate(), formatDate, formatInstant() (+8 more)

### Community 135 - "Base TS Config"
Cohesion: 0.12
Nodes (16): compilerOptions, declaration, declarationMap, esModuleInterop, forceConsistentCasingInFileNames, isolatedModules, module, moduleResolution (+8 more)

### Community 136 - "Migration 035 Trade Credit"
Cohesion: 0.23
Nodes (13): addColumnIfMissing(), addCompanyCreditColumns(), assertForeignKeysClean(), countRows(), explicitSchemaObjects(), hasColumn(), hasTable(), MigrationDb (+5 more)

### Community 138 - "Product Media Packaging"
Cohesion: 0.15
Nodes (10): NEUTRAL_PACKAGING_SCHEME, INKS, FOOD_BAG_DESIGNS, FoodBagArtwork, FoodBagDesign, genericArtworkDataUri(), product, ProductMediaProps (+2 more)

### Community 139 - "Standing Orders Presentation"
Cohesion: 0.18
Nodes (12): History(), API_ERROR_FALLBACK_KEYS, apiErrorParams(), cadence, resolve(), STANDING_ORDER_CADENCES, STANDING_ORDER_ERROR_CODES, standingOrderCadenceLabel() (+4 more)

### Community 140 - "Quick Order Contracts"
Cohesion: 0.16
Nodes (14): Cart, QuickOrderCart, QuickOrderLineOutcome, QuickOrderLineOutcomeFields, QuickOrderLineStatus, QuickOrderOutcomeStatusPair, QuickOrderRequestBody, QuickOrderResponse (+6 more)

### Community 142 - "Product Admin Repository"
Cohesion: 0.20
Nodes (3): ProductAdminRepository, ProductAdminService, ProductRow

### Community 143 - "Country Availability Rules"
Cohesion: 0.27
Nodes (10): blockedCategoriesFor(), blockedSlugsFor(), isCategoryBlocked(), isProductBlocked(), cnProfile, productBlockedProfile, assertProfilesMatchCatalog(), createCountryProfileService() (+2 more)

### Community 144 - "Promo Admin Repository"
Cohesion: 0.21
Nodes (3): PromoAdminRepository, PromoAdminService, PromoRecord

### Community 145 - "Credit Exposure Math"
Cohesion: 0.14
Nodes (13): accountRow(), accountState(), createCreditExposureHoldRepository, createTradeCreditHoldRepository, CreditExposureSummary, CreditHoldAuthorizeInput, CreditHoldCommitInput, CreditHoldReleaseInput (+5 more)

### Community 146 - "Order Routes & Invoices"
Cohesion: 0.23
Nodes (10): auditContext(), flattenInvoiceSchema(), invoiceResponseSchema, optionalInvoiceReader(), ordersRoutes(), OrdersRouteServices, OwnedOrderInvoiceReader, sendInvoiceCancellationError() (+2 more)

### Community 147 - "Web UI Dependencies"
Cohesion: 0.13
Nodes (15): dependencies, @base-ui/react, class-variance-authority, clsx, @fontsource-variable/geist, lucide-react, react, react-dom (+7 more)

### Community 148 - "Catalog Query Params"
Cohesion: 0.30
Nodes (13): CATALOG_DISCOVERY_PARAM_KEYS, CatalogParamKey, CatalogParamValue, isNormalizedKey(), normalizedSpecifications(), parseBoundedInteger(), parseCatalogQuery(), parseDate() (+5 more)

### Community 149 - "Catalog Package Manifest"
Cohesion: 0.13
Nodes (14): devDependencies, tsx, exports, tsx, main, name, private, scripts (+6 more)

### Community 150 - "Test Profiling Script"
Cohesion: 0.23
Nodes (10): main(), parseArgs(), printRecord(), profile(), ROOT, runChild(), suiteCommand(), SUITES (+2 more)

### Community 151 - "Playwright Test Workflow (.agents)"
Cohesion: 0.22
Nodes (12): Running and Debugging Playwright Tests, --debug=cli test debugging + attach, PLAYWRIGHT_HTML_OPEN=never, Browser Session Management, attach via CDP / channel / extension, Headless idle timeout (1 hour), Named browser sessions (-s), Test Generation (plan / generate / heal) (+4 more)

### Community 152 - "Workshop E2E Planning Prompt"
Cohesion: 0.21
Nodes (9): test-planner Agent, Plan output sections (Scenarios, Existing coverage, Files to read, Risks, Approach), QME-419 Custom-blend cart editing regression plan prompt, AC1 Restore and retain edits, AC2 Save and combine blend lines, AC3 Resulting prices (volume pricing, single mixing fee), AC4 Current evaluation (stale response guard), workshop/e2e-plan.md output (+1 more)

### Community 153 - "API Package Manifest"
Cohesion: 0.14
Nodes (13): devDependencies, tsx, @types/better-sqlite3, @types/node, @shop/contracts, @shop/localisation, tsx, name (+5 more)

### Community 154 - "Product Similarity"
Cohesion: 0.24
Nodes (9): compareScoredCandidates(), matchingSpecificationCount(), priceScore(), rankSimilarProducts(), scoreProductSimilarity(), sharedTagCount(), SimilarityScoreBreakdown, specificationValues() (+1 more)

### Community 155 - "Review Repository"
Cohesion: 0.18
Nodes (12): AdminQueueRecord, AdminReportRecord, EngagementRecord, mapRow(), ORDER_BY, PersistedReportStatus, PersistedReviewStatus, ReviewRecord (+4 more)

### Community 156 - "Mailbox Page"
Cohesion: 0.29
Nodes (11): getMailbox(), companyRoleMessageKey(), dualMoney(), MailboxPage(), fetchMailbox(), materialize(), RenderedMailbox, renderLegacy() (+3 more)

### Community 157 - "Root Package & ESLint"
Cohesion: 0.15
Nodes (12): engines, node, tsx, name, private, workspaces, concurrently, eslint (+4 more)

### Community 158 - "Contracts Package Manifest"
Cohesion: 0.14
Nodes (13): dependencies, @sinclair/typebox, @sinclair/typebox, main, name, private, scripts, build (+5 more)

### Community 159 - "Localisation Lint Visitors"
Cohesion: 0.24
Nodes (14): containsRawErrorMessage(), visit(), hasHumanText(), visit(), isMessageKey(), isRawCopy(), isTechnicalLiteral(), jsxExpressionLiteralValue() (+6 more)

### Community 160 - "Custom Blend Journey Tests"
Cohesion: 0.15
Nodes (5): Lot, NOW, parseCart(), paymentPayload(), UK_HEADERS

### Community 161 - "Custom Blend Order Tests"
Cohesion: 0.19
Nodes (9): App, cookie(), eligibleLots(), Fixture, login(), Lot, orderDetail(), pay() (+1 more)

### Community 162 - "Packaging Artwork Tests"
Cohesion: 0.15
Nodes (10): foodSpec(), heroSpec(), kegCorrosiveSpec, kegMildSpec, kegSchemedSpec, kraftSchemedSpec, kraftSpec, wovenSchemedSpec (+2 more)

### Community 163 - "Money Formatting"
Cohesion: 0.33
Nodes (12): assertInteger(), convertPenceToDisplayMinor(), currencyFormatters, DualTotal, formatDisplayMoney(), formatDualTotal(), formatMinor(), formatSettlementMoney() (+4 more)

### Community 164 - "E2E README & Tooling Rules"
Cohesion: 0.24
Nodes (8): playwright-cli find (snapshot search), playwright-cli (@playwright/cli), End-to-end tests README, e2e config.ts (E2E_BASE_URL), Page objects (e2e/pages/), playwright-mcp, npm run dev, npm run seed

### Community 166 - "Order Approval Routes"
Cohesion: 0.24
Nodes (6): ApprovalResult, ApprovalService, context(), orderApprovalRoutes(), OrderApprovalsRouteServices, sendApprovalError()

### Community 167 - "Admin Product Routes"
Cohesion: 0.26
Nodes (11): adminProductsRoutes(), AdminProductsRouteServices, AdminProductWithCountry, AdminProductWithCountryListResponse, category(), consumptionClassification(), context(), map() (+3 more)

### Community 168 - "Web Dev Dependencies"
Cohesion: 0.17
Nodes (12): devDependencies, jsdom, tailwindcss, @tailwindcss/vite, @testing-library/jest-dom, @testing-library/react, @testing-library/user-event, @types/react (+4 more)

### Community 169 - "Help Policy Messages"
Cohesion: 0.17
Nodes (10): articleIds, authoredBodyMessages, bodyDomainTranslations, generated, HelpPolicyMessageKey, helpPolicyMessages, keys, summaryTranslations (+2 more)

### Community 170 - "Catalog Specifications"
Cohesion: 0.22
Nodes (10): CATALOG_SPECIFICATION_DEFINITIONS, CATALOG_SPECIFICATION_GROUPS, catalogProductSpecifications(), catalogSpecificationByKey, CatalogSpecificationDefinition, CatalogSpecificationGroup, CatalogSpecificationGroupKey, ResolvedCatalogSpecification (+2 more)

### Community 172 - "Admin Promo Routes"
Cohesion: 0.27
Nodes (9): adminPromosRoutes(), AdminPromosRouteServices, categoryScope(), context(), map(), sendError(), admin, customer (+1 more)

### Community 173 - "Web TS Config"
Cohesion: 0.18
Nodes (10): compilerOptions, jsx, lib, noEmit, outDir, paths, rootDir, extends (+2 more)

### Community 174 - "E2E TS Config"
Cohesion: 0.18
Nodes (10): compilerOptions, declaration, declarationMap, lib, noEmit, sourceMap, types, extends (+2 more)

### Community 176 - "Credit Expiry & Error Mapping"
Cohesion: 0.27
Nodes (10): cartLinesUnblocked(), expirePreparedReservations(), isPendingApprovalPayment(), mapCreditAccountError(), mapCreditFailure(), prepare(), promoValidationCartRepository(), releasePreparedCreditHold() (+2 more)

### Community 177 - "API TS Config"
Cohesion: 0.20
Nodes (9): compilerOptions, composite, outDir, rootDir, types, extends, include, ../../tsconfig.base.json (+1 more)

### Community 178 - "Packaging Palettes"
Cohesion: 0.24
Nodes (8): CATALOG_PACKAGING_PALETTES, CatalogPackagingCategory, CatalogPackagingPalette, isRecognizedCategory(), PaletteTuple, CATEGORIES, INDEX_COVERAGE, PALETTE_MATRIX

### Community 179 - "Trade Field Validation"
Cohesion: 0.29
Nodes (9): handleSubmit(), validateEntityDraft(), handleSubmit(), validateSiteDraft(), checkContactPhone(), checkOptionalTradeText(), checkRequiredTradeText(), CONTACT_PHONE_BOUNDS (+1 more)

### Community 180 - "Contracts Export Map"
Cohesion: 0.20
Nodes (10): import, types, import, types, import, types, exports, ./account-depth (+2 more)

### Community 181 - "Workshop Env Skill"
Cohesion: 0.36
Nodes (6): workshop-env Skill, Workshop backup vault (~/.workshop-backup + manifest.json), Clean environment procedure, enabledPlugins in settings.json, Restore environment procedure, Status check procedure

### Community 182 - "API npm Scripts"
Cohesion: 0.22
Nodes (9): scripts, build, dev, reset, seed, test, test:integration, test:unit (+1 more)

### Community 183 - "Checkout Finalizer"
Cohesion: 0.33
Nodes (8): AUDIT_ACTIONS, appendInvoiceIssuedAudit(), currentQuote(), finalizeAuthorizedCheckout(), FinalizerDependencies, isResolvedCustomBlendSnapshot(), normalizeSnapshotId(), resumeFinalization()

### Community 186 - "Admin Variant Routes"
Cohesion: 0.33
Nodes (8): adminVariantsRoutes(), AdminVariantWithCountry, AdminVariantWithCountryListResponse, context(), deliveryClass(), map(), mapWithCountry(), sendError()

### Community 187 - "Root Dev Dependencies"
Cohesion: 0.22
Nodes (9): devDependencies, concurrently, eslint, @eslint/js, @playwright/test, prettier, tsx, typescript (+1 more)

### Community 188 - "Contracts Test TS Config"
Cohesion: 0.22
Nodes (8): compilerOptions, composite, noEmit, rootDir, types, extends, include, ../tsconfig.json

### Community 189 - "API Runtime Deps"
Cohesion: 0.25
Nodes (8): dependencies, better-sqlite3, fastify, @fastify/cookie, @fastify/type-provider-typebox, @shop/catalog, @shop/contracts, @shop/localisation

### Community 191 - "Nav Items"
Cohesion: 0.25
Nodes (7): accountItem, bundlesItem, customBlendItem, NavItem, navItems, savedListsItem, searchItem

### Community 192 - "Translation Surface Test"
Cohesion: 0.25
Nodes (6): allowlist, checkoutFixturePath, Finding, fixtureRoot, scanLocalisationFiles, ALLOWLIST

### Community 193 - "Vite & Vitest Config"
Cohesion: 0.25
Nodes (4): configDirectory, @tailwindcss/vite, vite, @vitejs/plugin-react

### Community 194 - "Catalog TS Config"
Cohesion: 0.25
Nodes (7): compilerOptions, composite, outDir, rootDir, extends, include, ../../tsconfig.base.json

### Community 195 - "Contracts TS Config"
Cohesion: 0.25
Nodes (7): compilerOptions, composite, outDir, rootDir, extends, include, ../../tsconfig.base.json

### Community 196 - "Localisation TS Config"
Cohesion: 0.25
Nodes (7): compilerOptions, composite, outDir, rootDir, extends, include, ../../tsconfig.base.json

### Community 197 - "Localisation ESLint TS Config"
Cohesion: 0.25
Nodes (7): compilerOptions, noEmit, rootDir, types, extends, include, ./tsconfig.json

### Community 198 - "Company Accounts Seed"
Cohesion: 0.38
Nodes (6): ACME_CREDIT_LIMIT_CENTS, ACME_CREDIT_STATE, ACME_CREDIT_TERMS_DAYS, findUserId(), inviteDigest(), seedCompanyAccounts()

### Community 200 - "Custom Blend Routes"
Cohesion: 0.52
Nodes (6): auditContext(), customBlendMinimumQuantity(), customBlendRoutes(), isSafePercentage(), sendCustomBlendError(), sendMutationResult()

### Community 201 - "API Test TS Config"
Cohesion: 0.29
Nodes (6): compilerOptions, noEmit, rootDir, extends, include, ../tsconfig.json

### Community 202 - "Web npm Scripts"
Cohesion: 0.29
Nodes (7): scripts, build, dev, test, test:integration, test:unit, typecheck

### Community 203 - "Custom Blend Eval Tests"
Cohesion: 0.29
Nodes (3): evaluateCustomBlend(), countryState, ingredients

### Community 204 - "Scripts ESLint TS Config"
Cohesion: 0.29
Nodes (6): compilerOptions, jsx, noEmit, extends, files, ../tsconfig.base.json

### Community 205 - "Playwright Storage State"
Cohesion: 0.40
Nodes (5): Persistent profile (--persistent / --profile), Storage Management, Authentication state reuse, Storage state file (cookies + origins localStorage), In-memory browser profile (default)

### Community 206 - "Return Scenarios Seed"
Cohesion: 0.33
Nodes (4): DEMO_RETURN_SCENARIO_KEYS, ReturnScenario, ReturnScenarioKey, SCENARIOS

### Community 207 - "Review Integration Tests"
Cohesion: 0.40
Nodes (5): body(), clock, context, isRecord(), parseMetadataJson()

### Community 208 - "Checkout Quote Tests"
Cohesion: 0.33
Nodes (5): cart, checkout, resolved, slot, testPostalAddress

### Community 209 - "Review Query Inputs"
Cohesion: 0.20
Nodes (3): AdminReviewQueueQueryInput, ReviewListQueryInput, ReviewReportInput

### Community 210 - "Cart Routes"
Cohesion: 0.67
Nodes (5): auditContext(), cartRoutes(), minimumMoqQuantity(), minimumMoqQuantityForVariant(), resolveCartLineVariant()

### Community 211 - "Lint Fixture: Raw Route Error"
Cohesion: 0.53
Nodes (4): chainedRoute(), code(), directRoute(), send()

### Community 212 - "Web Trade Credit API"
Cohesion: 0.40
Nodes (4): getCompanyCredit, getCreditSummary, getTradeCreditAccount, TradeCreditRequestOptions

### Community 213 - "Packaging Artwork Types"
Cohesion: 0.40
Nodes (5): BagArtworkPaint, TileArtwork, HeroVessel, PackagingArtworkProps, PackagingSpec

### Community 214 - "Back-in-Stock Seed"
Cohesion: 0.83
Nodes (3): findUserId(), findVariantId(), seedBackInStock()

### Community 215 - "Favicon & Brand"
Cohesion: 0.67
Nodes (3): Favicon (QArefully Materials Exchange), Bulk Materials by Sack or Pallet, QArefully Materials Exchange (brand)

### Community 216 - "Lint Fixture: Display Intl"
Cohesion: 0.50
Nodes (3): callableDate, callableNumber, display

### Community 217 - "Contracts Export ./admin-orders-list"
Cohesion: 0.67
Nodes (3): import, types, ./admin-orders-list

### Community 218 - "Contracts Export ./admin-products"
Cohesion: 0.67
Nodes (3): import, types, ./admin-products

### Community 219 - "Contracts Export ./admin-promos"
Cohesion: 0.67
Nodes (3): import, types, ./admin-promos

### Community 220 - "Contracts Export ./admin-refunds"
Cohesion: 0.67
Nodes (3): import, types, ./admin-refunds

### Community 221 - "Contracts Export ./admin-users"
Cohesion: 0.67
Nodes (3): import, types, ./admin-users

### Community 222 - "Contracts Export ./admin-variants"
Cohesion: 0.67
Nodes (3): import, types, ./admin-variants

### Community 223 - "Contracts Export ./audit"
Cohesion: 0.67
Nodes (3): import, types, ./audit

### Community 224 - "Contracts Export ./auth"
Cohesion: 0.67
Nodes (3): import, types, ./auth

### Community 225 - "Contracts Export ./back-in-stock"
Cohesion: 0.67
Nodes (3): import, types, ./back-in-stock

### Community 226 - "Contracts Export ./bundles"
Cohesion: 0.67
Nodes (3): import, types, ./bundles

### Community 227 - "Contracts Export ./cart"
Cohesion: 0.67
Nodes (3): import, types, ./cart

### Community 228 - "Contracts Export ./common"
Cohesion: 0.67
Nodes (3): import, types, ./common

### Community 229 - "Contracts Export ./company-accounts"
Cohesion: 0.67
Nodes (3): import, types, ./company-accounts

### Community 230 - "Contracts Export ./country"
Cohesion: 0.67
Nodes (3): import, types, ./country

### Community 231 - "Contracts Export ./country-profiles"
Cohesion: 0.67
Nodes (3): import, types, ./country-profiles

### Community 232 - "Contracts Export ./delivery"
Cohesion: 0.67
Nodes (3): import, types, ./delivery

### Community 233 - "Contracts Export ./feature-flags"
Cohesion: 0.67
Nodes (3): ./feature-flags, import, types

### Community 234 - "Contracts Export ./inventory"
Cohesion: 0.67
Nodes (3): ./inventory, import, types

### Community 235 - "Contracts Export ./jobs"
Cohesion: 0.67
Nodes (3): ./jobs, import, types

### Community 236 - "Contracts Export ./mailbox"
Cohesion: 0.67
Nodes (3): ./mailbox, import, types

### Community 237 - "Contracts Export ./notifications"
Cohesion: 0.67
Nodes (3): ./notifications, import, types

### Community 238 - "Contracts Export ./order-approvals"
Cohesion: 0.67
Nodes (3): ./order-approvals, import, types

### Community 239 - "Contracts Export ./orders"
Cohesion: 0.67
Nodes (3): ./orders, import, types

### Community 240 - "Contracts Export ./payments"
Cohesion: 0.67
Nodes (3): ./payments, import, types

### Community 241 - "Contracts Export ./pricing"
Cohesion: 0.67
Nodes (3): ./pricing, import, types

### Community 242 - "Contracts Export ./products"
Cohesion: 0.67
Nodes (3): ./products, import, types

### Community 243 - "Contracts Export ./promos"
Cohesion: 0.67
Nodes (3): ./promos, import, types

### Community 244 - "Contracts Export ./public-errors"
Cohesion: 0.67
Nodes (3): ./public-errors, import, types

### Community 245 - "Contracts Export ./quick-order"
Cohesion: 0.67
Nodes (3): ./quick-order, import, types

### Community 246 - "Contracts Export ./reorder"
Cohesion: 0.67
Nodes (3): ./reorder, import, types

### Community 247 - "Contracts Export ./returns"
Cohesion: 0.67
Nodes (3): ./returns, import, types

### Community 248 - "Contracts Export ./reviews"
Cohesion: 0.67
Nodes (3): ./reviews, import, types

### Community 249 - "Contracts Export ./saved-lists"
Cohesion: 0.67
Nodes (3): ./saved-lists, import, types

### Community 250 - "Contracts Export ./standing-orders"
Cohesion: 0.67
Nodes (3): ./standing-orders, import, types

### Community 251 - "Contracts Export ./trade-account"
Cohesion: 0.67
Nodes (3): ./trade-account, import, types

### Community 252 - "Contracts Export ./trade-credit"
Cohesion: 0.67
Nodes (3): ./trade-credit, import, types

### Community 253 - "Contracts Export ./webhooks"
Cohesion: 0.67
Nodes (3): ./webhooks, import, types

## Ambiguous Edges - Review These
- `Plan output sections (Scenarios, Existing coverage, Files to read, Risks, Approach)` → `workshop/e2e-plan.md output`  [AMBIGUOUS]
  workshop/prompt.md · relation: conceptually_related_to
- `Browser tooling: Playwright CLI, never MCP` → `Static inspection only constraint`  [AMBIGUOUS]
  workshop/prompt.md · relation: conceptually_related_to
- `playwright-cli Skill` → `Project-local Customizations Check`  [AMBIGUOUS]
  .claude/skills/workshop-env/SKILL.md · relation: conceptually_related_to

## Knowledge Gaps
- **62 isolated node(s):** `@shop/contracts`, `@shop/localisation`, `@types/better-sqlite3`, `@types/node`, `tsx` (+57 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 2892 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **20 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `better-sqlite3` connect `API DB Test Harness` to `API Audit & Unit of Work`, `API Service Composition`, `Seeded App Integration Fixtures`, `DB Migrations`, `Checkout & Payment Services`, `Country Availability Rules`, `Credit Exposure Math`, `Custom Blend Resolver`, `API Package Manifest`, `Auth, Reset & Deletion`, `Review Repository`, `Custom Blend Journey Tests`, `Company & Approval Services`, `Custom Blend Order Tests`, `App Bootstrap & Clock`, `Standing Order Service`, `Bundles & Clearance`, `Feature Flags`, `Trade Credit Seed`, `Variant Admin`, `User Admin`, `Returns Service`, `Company Accounts Seed`, `DB Seed Scenarios`, `Return Scenarios Seed`, `Order Admin Routes Tests`, `Credit Account Repository`, `Back-in-Stock Seed`, `Admin Refunds`, `Product Admin Service`, `Reorder Route Tests`, `Order Admin Service`, `Trade Credit E2E Tests`, `Powder Catalog Seed`, `Invoice Repository`?**
  _High betweenness centrality (0.030) - this node is a cross-community bridge._
- **What connects `@shop/contracts`, `@shop/localisation`, `@types/better-sqlite3` to the rest of the system?**
  _62 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `API Audit & Unit of Work` be split into smaller, more focused modules?**
  _Cohesion score 0.023358199828788066 - nodes in this community are weakly interconnected._
- **Why does `vitest` connect `Web API Client Layer` to `Web App Shell & Routing`, `Web Cart/Auth/Country Contexts`, `Account Page & Localisation`, `Custom Blend Page Tests`, `Catalog UI & Product Cards`, `Web Integration Journeys`, `Product Media Packaging`, `Order Detail Pages`, `Standing Orders Presentation`, `Cart Sheet & UI Primitives`, `Catalog Product Journeys`, `Custom Blend Page UI`, `Help Content Registry`, `Mailbox Page`, `Packaging Artwork Tests`, `Product Page UI`, `Trade Profile Sections`, `Checkout Page Tests`, `Web Cart Hook & Storage`, `Packaging Palettes`, `Checkout State Reducer`, `Checkout Flow & Validation`, `Translation Surface Test`, `Vite & Vitest Config`, `Checkout Copy & Promo Quote`, `Product Comparison Selection`, `Product Reviews Hook`, `Quick Order Presentation`, `Custom Blend Eval Tests`, `Admin Review Moderation UI`, `Custom Blend State`, `Reorder Presentation`, `Saved Lists Presentation`, `Standing Orders Page`, `Back-in-Stock Context`, `Web Package Deps`, `Payment Submission Hook`?**
  _High betweenness centrality (0.019) - this node is a cross-community bridge._
- **Should `API DB Test Harness` be split into smaller, more focused modules?**
  _Cohesion score 0.030135026379325764 - nodes in this community are weakly interconnected._

### Low-confidence Hints
_AMBIGUOUS edges — the extractor was unsure. Verify before acting on these._

- **What is the exact relationship between `Plan output sections (Scenarios, Existing coverage, Files to read, Risks, Approach)` and `workshop/e2e-plan.md output`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Browser tooling: Playwright CLI, never MCP` and `Static inspection only constraint`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._