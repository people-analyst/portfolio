# Mike West — Software Portfolio

*As of September 17, 2026. Public summary from this repo; most product code remains private.*

**Contact**: mike@peopleanalyst.com · Pittsburgh, PA · linkedin.com/in/michaelcwest · peopleanalyst.com

---

## Overview

I build products for domains that are still under-served by data, and I build the measurement science underneath them. The center of gravity has shifted from "apps that use AI" to "measurement systems that make AI outputs more reliable, more honest, and more decision-useful." My through-line is unchanged: behavioral science is not just an analytics discipline; it is an AI quality discipline.

The portfolio now operates as a joined system: content surfaces where practitioners learn, tool surfaces where they act, and canonical data surfaces where the claims are measured. Per `devplane/data/site-library.json` (updated 2026-09-17), the active inventory tracks **82 sites** (80 self-declared by their owning repos), with explicit `UNKNOWN` states where probes cannot verify a live verdict.

---

## Product Lines (September 2026)

### 1) People Analytics Toolbox + Frames
**Domains:** `peopleanalyticstoolbox.com` · `jobframe.global` · `geoframe.global` · `skillframe.global`

This is the shared analytical substrate and still the most important technical bet: 45+ services callable over HTTP and MCP, consumed by product fronts rather than reimplemented per app. Since May, intent moved from "one analytics app" to "one reusable capability layer plus frame products" where JobFrame, GeoFrame, and SkillFrame act as cross-product join keys for business context (job, place, skill), not isolated feature pages.

### 2) Principia
**Domain:** `peopleprincipia.com`

Principia has become the evidence authority for organization measurement: source-graded constructs, instruments, priors, effects, metrics, and refusal/gate records served as a living registry. The design evolution is from handbook-style synthesis to a continuously measured public contract that other products consume directly.

### 3) Performix
**Domain:** `performix.app`

Performix is now clearly positioned as a tool product (not a content desk): measurement science for leadership decisions, delivered through CAMS and protected-feedback constraints. The intent evolved from broader content ambitions to product clarity: one decision tool, multiple persona doors, and explicit partner honesty that this sits alongside Mike and Alvan's Tiny Boat relationship instead of being represented as a solo shell.

### 4) Compensation Professional Cluster
**Domains:** `compensationprofessional.com` · `anycomp.ai` · `compdata.ai` · `compensationtoolbox.com`

This line has sharpened into a cluster with separated roles: a full persona site (`compensationprofessional.com`) plus tool/data surfaces (AnyComp, CompData, Compensation Toolbox). The design change since May is less "one big compensation product" and more "content home plus task-specific tools," with domain/persona boundaries enforced in the inventory model.

### 5) Bicycle Guide Platform + Bicycle.LLC
**Domains:** `bicycle.guide` (+ front domains across `*.guide`) · `bicycle.llc` (in stand-up)

Bicycle Guide has evolved from a single guide destination into a front-platform: many focused `.guide` surfaces generated from field canons, with one shared engine and strict host-role boundaries. The September ruling extends that model: `bicycle.llc` is built as its own front inside the same repo/deploy (host-routed), with Guide preserved as Guide and company portfolio pages kept separate by checks.

### 6) CanonicAI (Engine + Front Door)
**Domains:** `canonicai.com` (front door) · engine row has no public primary domain

CanonicAI now has an explicit two-part identity: corpus-to-canonical-data engine (`canonicai` row) plus human-facing brand front (`canonicai.com`, `canonicai-site`). The intent evolved from a mostly internal producer to a declared external interface with Answers corpus surfaces and MCP/REST access, while keeping engine/source-of-truth responsibilities distinct.

### 7) Writer's Desk Publications
**Domains:** `peopleanalyst.com` · `vela.study` · `penwright.ink` · `namesake.baby`

The writing stack includes PeopleAnalyst, a learning and resources site for people analytics professionals; Vela, an adaptive magazine; Penwright, a writers' desk; and Namesake, a bounded decision product. bicycle.llc is the portfolio hub. The key change since May is design discipline around voice, role, and evidence boundaries: each surface has a declared purpose, and writing systems are treated as product infrastructure rather than side content.

### 8) DevPlane (Operator Cockpit)
**Domains:** `devplane.dev` · `docs.devplane.app`

DevPlane has shifted from "solo builder cockpit" to one product with two offers: managed operation for site owners and self-operated control plane for technical estates. The design evolution is major: cockpit grammar is now catalog/focus/work axes, admin is list grammar (not page sprawl), and unattended work is being moved to an off-laptop runner model.

### 9) Fourth & Two
**Domain:** `fourth-and-two.performix.app`

Fourth & Two remains a live fantasy-football decision product with its own domain and data posture, now framed as a distinct portfolio line rather than a side experiment. The direction is consistent with the rest of the portfolio: analytics substrate first, then product surfaces and controlled expansion.

---

## Design Principles That Changed

- **2026-08-23 — Cockpit three axes:** operator UI is catalog + focus + work mode, not tab proliferation.
- **2026-09-03 — AI crawler policy is per surface:** crawl/training policy depends on product type (open content, registry, or app), not one portfolio-wide robots rule.
- **2026-09-09 — DevPlane one product, two offers:** managed and self-operated are packaging of one control-plane product.
- **2026-09-13 — Admin is one list grammar:** add typed rows/chips/pills/wizards instead of minting new admin pages per feature.
- **2026-09-17 — `bicycle.llc` is a front inside `bicycle-guide`:** host-level separation with one deploy pipeline now; extract later if needed.
- **2026-09-17 — Off-laptop runner is accepted:** unattended agent work moves to a dedicated runner (Hetzner path accepted), laptop stays interactive cockpit.

---

## How The Work Is Run

The portfolio is now run as an agent-operable system with explicit gates. Programs define measured completion criteria (not declaration-only checklists), and improvements are expected to be observable in artifacts, not just exit codes. This shows up in multiple places: AIDL adoption rules, improvement-loop governors, frame conformance gates, and Bicycle reliability grading tied to published evidence tiers. The underlying doctrine is simple: if a claim cannot be measured, it is a draft.

Execution is splitting into two planes. The laptop remains the human cockpit for review, judgement, and close decisions. Unattended workloads move to a runner environment with persistent scheduler behavior, CLI-authenticated toolchains, and maintenance that agents can perform end-to-end. The point is not "more automation"; the point is reliable throughput without pretending that unverified output is done.

---

## Public vs Private Repo Honesty

This repository (`portfolio`) is public and intentionally high-level. The product inventory tracks deploy and ownership states, but does not encode GitHub visibility for every repo. What is explicit today: `devplane` is declared with `deploy_status: private`; many product repos remain private by operating choice, and any repo not explicitly marked private in the inventory should be treated as `UNKNOWN` for visibility unless verified directly.

---

## Contact

Mike West  
Pittsburgh, PA  
mike@peopleanalyst.com  
[peopleanalyst.com](https://peopleanalyst.com)  
[linkedin.com/in/michaelcwest](https://linkedin.com/in/michaelcwest)
