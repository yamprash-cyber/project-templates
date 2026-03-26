# 🏗️ UNIVERSAL PROJECT TEMPLATE

## Unified Asana Structure for ALL Projects (Bybit, VINTED, VIBL LINE, Future)

Created: 2026-03-26  

Status: STANDARD FOR ALL PROJECTS  

Owner: Robert (Decision Master)  

---

## 🎯 CORE PRINCIPLE

VERTICAL (Columns): Standardized across ALL projects  

HORIZONTAL (Phases): Workflow sequence from start → end (unified process, project-specific content)

---

## 📊 UNIFIED COLUMNS (VERTICAL STANDARDIZATION)

Every task in every project has these 12 mandatory columns:

| # | Column Name | Type | Requirement | Example |

|---|------------|------|-------------|---------|

| 1 | Task name | Text | Mandatory | "P1.1: Daily loss cutoff enforcement (-1.5%)" |

| 2 | Description | Text (long) | Mandatory | "Implement -1.5% daily loss stop. When balance drops..." |

| 3 | Phase | Dropdown | Mandatory | Phase 0, Phase 1, Phase 2, Phase 3, Phase 4, Operations, Docs |

| 4 | Section | Dropdown | Auto | Foundation, Execution, Optimization, Validation, etc. |

| 5 | Status | Dropdown | Mandatory | To Do, In Progress, Testing, Done, Waiting, Blocked |

| 6 | Priority | Dropdown | Mandatory | Critical, High, Medium, Low |

| 7 | Assignee | User | Mandatory | me, Cowork, Claude, Robert, @person |

| 8 | Owner | User | Optional | Project lead (for accountability) |

| 9 | Start date | Date | Conditional | Only for Phase 1-3 (detail work) |

| 10 | Due date | Date | Mandatory | Specific day or date range |

| 11 | Hours est. | Number | Mandatory | 0.5, 1, 2, 3, 5, 10+ (for planning) |

| 12 | Dependencies | Link | Optional | "Depends on: [Task name]" or "Blocks: [Task name]" |

### 13 Optional (Advanced)

| # | Column Name | Type | Use |

|---|------------|------|-----|

| 13 | Progress % | Number | Only Phase 1-3, updated weekly |

| 14 | Custom field: Blockers | Text | If blocked, why? |

| 15 | Custom field: Notes | Text | Learnings, decision log |

---

## 🔄 UNIFIED PHASES (HORIZONTAL WORKFLOW)

Every project follows this sequence (content varies by project, structure is identical):

### PHASE 0: Foundation & Setup (Days 1-5)

- Setup infrastructure / tooling / accounts

- Team alignment, access granted

- Baseline established

- Gate: ✅ All setup complete, team ready to execute

Typical tasks:

- Environment setup (VPS, APIs, accounts)

- Access provisioning

- Documentation skeleton

- Kickoff meeting logged

---

### PHASE 1: Core Execution — Critical Path (Days 6-15)

- Primary features / mechanics implemented

- MVP delivered

- Real-world testing begins (testnet / staging / demo)

- Success criteria: 100% critical features live

Typical tasks:

- Feature 1: Core engine (e.g., Risk enforcement, Domain setup, Listings)

- Feature 2: Secondary engine (e.g., TP logic, Sellers integration, Pricing)

- Feature 3: Data tracking (e.g., Win rate logging, Competitor monitoring, Analytics)

- Testing & validation (24h+ live)

- Gate: ✅ All critical features pass tests

---

### PHASE 2: Optimization & Scaling (Days 16-25)

- Performance tuning, efficiency gains

- Secondary features added

- Pair/product ranking, filtering, ranking applied

- Real data sample collected (50+ units)

- Success criteria: Metrics improve, no regressions

Typical tasks:

- Kelly sizing / dynamic scaling / A/B testing

- Pair ranking / category prioritization / inventory optimization

- Correlation filters / redundancy checks

- Weekly metrics review

- Gate: ✅ Optimization validated, metrics >target

---

### PHASE 3: Advanced & Refinement (Days 26-35)

- Edge cases handled, advanced features

- Order book / liquidation / funding integration

- Correlation management, volume checks

- 72h+ continuous run without restart

- Success criteria: Uptime ≥99%, all edge cases covered

Typical tasks:

- Advanced filter (correlation, volume, liquidity)

- API depth checks, slippage estimation

- Monitoring alerts, auto-restart logic

- Documentation complete

- Gate: ✅ All advanced features live & stable

---

### PHASE 4: Validation & Go-Live Decision (Days 36-60)

- 60+ data points collected

- ALL success criteria validated

- Decision point: GO / NO-GO / EXTEND

- If GO → deploy to production

- If NO-GO → extend with optimization focus

Typical tasks:

- Metric validation (WR%, PF, PnL, Drawdown, Uptime, SL accuracy, Risk enforcement)

- Decision task: "DECISION POINT: GO/NO-GO [Date]"

- If GO: "Deploy to live [Platform]"

- If NO-GO: "Extend & optimize — new roadmap"

Gate: ✅ DECISION + Next phase clarity

---

### OPERATIONS: Continuous (parallel to Phases 1-4)

- Daily health checks

- Weekly metric reviews

- Monitoring & alerting

- Risk enforcement audits

- Never stops — runs 24/7, logged weekly

Typical tasks:

- Daily health check (VPS uptime, CPU, memory)

- Daily P&L review (today's numbers, alerts)

- Weekly strategy review (pattern analysis, optimization proposals)

- Weekly risk audit (SL accuracy, rule violations)

- Bi-weekly sync (decision-making, priority setting)

---

### DOCUMENTATION & SUPPORT: Continuous

- Chat channels (strategy, production, monitoring, decisions)

- API documentation

- Troubleshooting runbooks

- Decision logs

Typical tasks:

- Chat-1: Live strategy optimization

- Chat-2: Production bot / core execution

- Chat-3: Live monitoring & analytics

- Chat-4: Daily reports & decisions

- API docs update

- Troubleshooting runbook

---

## 📋 TASK NAMING CONVENTION (STANDARDIZED)

Format: [Phase].[Number]: [Action] ([Context])

### Examples (all projects):

Bybit:

- P1.1: Daily loss cutoff enforcement (-1.5%)

- P2.1: Kelly Criterion position sizing (dynamic)

- P3.1: Inter-pair correlation matrix (real-time)

VINTED:

- P1.1: Domain Decision & Purchase (setup)

- P2.1: Batch 1 Repair (200+ listings)

- P3.1: Monitoring engineer — Week 1 (24/7)

VIBL LINE:

- P1.1: Shopify free Account Setup (domain)

- P2.1: Manual Design Generation (20 designs)

- P3.1: Scenario 1: Auto-listing (Google Trends → Shopify)

PHASE 0 (all projects):

- 0.1: VPS / Infrastructure setup

- 0.2: API credentials & access provisioning

- 0.3: Kickoff meeting + team alignment

OPERATIONS (all projects):

- OPS.1: Daily health check (VPS uptime)

- OPS.2: Daily P&L review

- OPS.3: Weekly strategy review (Monday)

- OPS.4: Weekly risk audit (Friday)

DOCS (all projects):

- DOC.1: Chat-1: Live strategy optimization

- DOC.2: Chat-2: Production bot (Bybit API)

- DOC.3: API docs (Bybit + Binance)

---

## 🎯 STATUS PIPELINE (UNIFIED FOR ALL)
