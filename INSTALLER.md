# AI Operating System Installation Manual — Phase 0 and Phase 1

**Version:** 1.0

**Audience:** Nontechnical people building a personal or business AI operating system with an AI assistant

**Format:** Self-paced guide, workshop workbook, facilitator SOP, or source for a PDF or knowledge site

**Outcome:** A requirements-led, local-first, vendor-neutral foundation that a new LLM can understand, verify, and safely use without relying on chat history

**Scope:** Phase 0 discovery and Phase 1 foundation only. This guide does not build domain-specific workflows or automations.

---

# AI installer protocol — begin here

This section is the execution controller for the rest of the manual. A learner may give an AI the URL or exported Markdown for this page and say:

```text
Install this AI operating system for me. Follow the AI installer protocol at the top of the page exactly. Begin with the access check, then ask only the first Phase 0 interview question.
```

The AI must follow the sequence below. It may not skip discovery, invent answers, treat a summary as installation, or advance past an exit gate without evidence.

## Installer rule 1 — Verify the source before acting

1. Retrieve the full page, not a search snippet, preview, or summary.
2. Confirm that the source contains all seven Parts, the Phase 0 exit test, the Phase 1 exit test, the Master Installation Prompt, the Facilitator SOP, and the Final Installation Checklist.
3. State whether the source was read in full or only structurally inspected.
4. If the page cannot be retrieved completely, stop and ask the learner to grant access, export the page as Markdown or PDF, or paste the manual. Do not reconstruct missing instructions from memory.

## Installer rule 2 — Run the access and capability check

Before interviewing or building, determine what the current AI can actually access and change.

| Capability | Record as | Direct proof required |
|---|---|---|
| Read the complete manual | Verified / blocked | Final section and stop condition retrieved |
| Ask and retain interview answers | Verified / limited | Current conversation or persistent project available |
| Create and edit local files | Verified / blocked | Named target folder can be inspected |
| Use Git locally | Verified / blocked | Git version and repository state can be read |
| Reach a private remote host | Verified / blocked / not yet needed | Named repository can be retrieved |
| Update the chosen workbench | Verified / blocked / not used | Named destination can be retrieved |
| Use browser or computer controls | Verified / blocked / not needed | Relevant signed-in surface is observable |
| Read canonical files through each intended provider surface | Verified / blocked / not used | Exact mode retrieves named files from the canonical path |

Do not infer capability from a connected badge, product name, or the learner's subscription. Verify it directly when that capability becomes necessary.

A provider name is not a capability. Standard chat, browser or cloud task mode, coding or repository mode, and desktop local-folder mode may have different tools and permissions even when they share one brand and account. Record and test the exact surface. A failure on one surface does not prove that every surface from that provider is blocked.

Missing capability does not invalidate the method. Complete everything available on the current surface, then create the handoff packet defined below for the next capable AI or for the learner.

## Installer rule 3 — Control the conversation

- Ask one focused Phase 0 question at a time.
- Incorporate corrections immediately; do not defend an earlier assumption.
- Do not ask the learner to choose routine architecture, filenames, folder structure, or sequencing already specified by this manual.
- Do not send status-only summaries while executable work remains.
- Ask the learner only for an irreducible fact, authentication step, consequential approval, or preference that materially changes the result.
- When blocked, name the exact blocker, the smallest learner action required, and the precise resume point.

## Installer rule 4 — Persist installation state

During Phase 0, maintain one installation-state record in the current conversation or project. As soon as the canonical local root exists, save it as `00-Control/INSTALLATION-STATE.md` and keep it current.

Use this structure:

```text
# Installation State

System name: [UNKNOWN UNTIL CONFIRMED]
Learner/owner: [CONFIRMED NAME OR ROLE]
Current phase: Phase 0
Current step: [STEP NUMBER]
Last completed gate: [NONE / GATE]
Canonical local root: [UNKNOWN / VERIFIED PATH]
Private remote: [UNKNOWN / VERIFIED LOCATION]
Human-readable workbench: [NONE / UNKNOWN / VERIFIED LOCATION]

## Confirmed requirements
## Explicit unknowns
## Authority and approval boundaries
## Archive locations — locations only, contents not opened
## Verified capabilities and access
## Decisions made
## Assets created or changed
## Verification evidence
## Current blocker
## Exact resume instruction
```

After every completed step, update the current step, confirmed facts, affected assets, verification, and resume instruction. Never store credentials, authentication codes, account numbers, or confidential source content in this record.

## Installer rule 5 — Enforce the phase gates

Execute in this order:

1. Complete the access and capability check.
2. Run the Phase 0 interview in Part II.
3. Build and correct the Requirements Map, Current Systems Inventory, authority classes, archive boundary, acceptance criteria, non-goals, and roadmap.
4. Run the Phase 0 exit test. If any criterion fails, remain in Phase 0 and resolve it.
5. State the single Phase 1 objective and trace each proposed foundation component to a confirmed requirement.
6. Build Phase 1 in the order defined in Part III.
7. Verify every destination, run the health check, compare local and remote state, and run the clean-room test.
8. Run the Phase 1 exit test. Do not call installation complete if any criterion fails.

The AI may prepare several safe steps together, but it may not collapse the phase gates or silently substitute its preferred architecture.

## Installer rule 6 — Use an exact handoff when tools are missing

If another AI or execution surface is required, produce one handoff block and continue any remaining safe work before stopping.

```text
INSTALLATION HANDOFF
System: [SYSTEM NAME OR UNKNOWN]
Current phase and step: [PHASE / STEP]
Completed gate: [LAST PASSED GATE]
Canonical source: [MANUAL URL OR FILE]
Canonical local root: [PATH OR UNKNOWN]
Do not access: [ARCHIVE BOUNDARIES]
Confirmed requirements source: [LOCATION]
Installation-state source: [LOCATION]
Work already completed: [VERIFIED ACTIONS]
Verification evidence: [RESULTS]
Exact blocker: [MISSING CAPABILITY OR ACCESS]
Next authorized action: [ONE ACTION]
Resume at: [EXACT MANUAL HEADING]
Required completion proof: [DESTINATION STATE]
```

The receiving AI must retrieve the named state and source, verify them, and resume at the named heading. It must not restart discovery, reread archives, or reinterpret completed decisions without evidence of a conflict.

## Installer rule 7 — Define completion correctly

Installation is complete only when:

- both phase exit tests pass;
- the learner's confirmed requirements—not the example implementation—determine the system;
- canonical files exist and are registered;
- the health check passes;
- the local repository is clean and matches its private remote when a remote is part of the accepted design;
- the workbench points to canonical truth without duplicating it;
- a clean-room AI can orient without chat history or archive access;
- the installation-state record contains the final evidence and recovery path.

After confirming the source and capability check, begin Phase 0 by asking only the first interview question from Step 0.2.

---

## Start here

Most people begin an AI operating system by copying folders, prompts, dashboards, or another person's tool stack. That creates a tidy-looking system before anyone has defined what the system must actually do.

This method begins one phase earlier.

- **Phase 0 discovers the life, work, failures, tools, authority boundaries, and definition of success the system must support.**
- **Phase 1 installs the smallest durable control layer that lets humans and multiple LLMs share current truth safely.**

At the end of Phase 1, the system will not yet do all of the work. It will be trustworthy enough to begin proving real workflows without losing source authority, exposing archives, duplicating truth, or making the user carry context between models.

### What you will have when you finish

1. A written Requirements Map grounded in real recurring needs.
2. A measurable build roadmap with explicit non-goals.
3. One local canonical folder under Git version control.
4. A private off-device Git remote with verified local/remote parity.
5. A human-readable workbench foundation page that points to the canonical system without duplicating it.
6. A machine-readable manifest that tells a new LLM what the system is and where current truth lives.
7. A health check that detects missing assets, dirty Git state, remote drift, and archive-boundary failure.
8. Recovery instructions that do not depend on chat history or model memory.
9. A registry, changelog, decision record, and session trace for material changes.
10. A clean-room test proving that a new LLM can orient itself without reading an archive.

### What you will not build yet

- A domain-specific database, dashboard, automation, content pipeline, or reminder system.
- A complete copy of your files inside the workbench.
- A giant prompt containing your whole life or business.
- A migration of every old chat, drive, note, or workspace.
- An AI workflow based only on a provider's marketing claims or a green `Connected` badge.

Those may become appropriate later. Phase 0 and Phase 1 establish the evidence required to decide.

---

# Part I — The operating principles

## 1. One canonical home

Every durable asset has one authoritative home. Other tools may display a summary, pointer, editable workbench, or temporary copy, but they do not silently become competing sources of truth.

Recommended pattern:

- **Local Markdown + Git:** canonical operating layer.
- **Private Git remote:** versioned off-device recovery and cross-LLM access.
- **Human-readable workbench:** current status, editable drafts, and links in any suitable knowledge tool.
- **AI chats/projects:** temporary work cells.
- **Archives:** preserved evidence excluded from routine retrieval.

## 2. Current instruction outranks stale documentation

The system must record source authority explicitly. A useful default order is:

1. The user's explicit current instruction.
2. Current approved controls and requirements.
3. A task-specific work order or context pack.
4. Verified current source material.
5. Older records used only when explicitly authorized.

Frequency is not authority. A stale claim repeated in twelve documents is still stale.

## 3. Archives are boundaries, not filing projects

Preserve old work. Do not routinely search, summarize, reorganize, migrate, or "clean up" archives. Retrieval requires a named archive, a stated purpose, and explicit permission.

This prevents an LLM from inheriting old decisions merely because they are easy to retrieve.

## 4. Complexity must earn its place

Before adding a tool, database, workflow, rule, or automation, answer:

1. What observed recurring problem does this solve?
2. What existing step, file, or rule does it replace or simplify?
3. Who or what maintains it without adding work to the user?
4. How will one real workflow prove that it worked?

If the answers are weak, park the idea.

## 5. Verification is part of the work

"Created," "connected," "indexed," "authorized," "synced," and "working" are different states. Every important claim needs direct proof from the destination system.

## 6. AI executes through the real approval boundary

The assistant completes every safe, reversible, authorized step. It stops only at an irreducible fact, authentication step, consequential judgment, or action that requires human authorization.

It does not end with a summary when safe work remains.

---

# Part II — Phase 0: Discover before you design

## Phase 0 objective

Create an evidence-based definition of what the operating system must accomplish, which systems it must touch, what it may do alone, and what success looks like.

## Phase 0 deliverables

- Requirements Map
- Current Systems Inventory
- Authority and approval matrix
- Archive boundary
- Ninety-day acceptance criteria
- Phased build roadmap
- Explicit non-goals
- Teaching record separating universal principles from private configuration

## Step 0.1 — Set the discovery rule

Tell the AI that discovery comes before architecture.

### Copy-and-paste prompt: discovery contract

```text
You are helping me design an AI operating system. Do not build folders, dashboards, databases, prompts, automations, CRMs, content assets, or workflows yet.

Your first job is requirements discovery. Interview me one focused question at a time. Capture only facts I explicitly confirm. Separate:
- recurring responsibilities;
- failures or consequences;
- tools and accounts currently used;
- what AI should do autonomously;
- what requires approval;
- authentication or access blockers;
- privacy and sensitivity boundaries;
- what success would look like in 90 days;
- what I do not want the system to manage.

Challenge assumptions and identify contradictions. Do not infer permission from convenience. Do not use archives, old chats, saved memory, or stale plans as current truth.

Maintain a Requirements Map as we go. Before proposing architecture, show which verified requirement each proposed component would satisfy. If it cannot be traced to a real need, park it.
```

## Step 0.2 — Interview the lived system

Do not ask the user to describe an ideal software architecture. Ask about their actual life and work.

### Interview sequence

Ask these questions one at a time, following useful threads before moving on.

1. What recurring responsibilities depend on you and regularly fall through the cracks?
2. What happens when each one is missed?
3. Which responsibilities are time-sensitive, financially consequential, client-facing, legal, health-related, or reputation-sensitive?
4. Which work do you avoid because it is boring, confusing, emotionally draining, or physically difficult?
5. Which work can only you do? Which work merely happens to depend on you today?
6. If AI could handle a responsibility safely, should it act automatically, prepare a draft, ask every time, or never act?
7. What tools, accounts, devices, communication channels, and paid subscriptions are involved?
8. Where does the knowledge required to do the work live: documents, inboxes, software, another person, or memory?
9. What authentication barriers exist: passwords, passkeys, text codes, email codes, client approval, or device access?
10. What actions must always require approval?
11. What should AI never cancel, delete, change, publish, spend, or send without a direct instruction?
12. What would make this system feel genuinely useful in 90 days?
13. What would make the system feel like another job?
14. What current workflows are already good enough and should not be replaced?
15. What important domain have we not discussed?

### Facilitator rule

Listen for corrections. A correction is a requirement change, not resistance. Record it immediately and remove the rejected assumption from active controls.

## Step 0.3 — Build the Requirements Map

Use one file. Do not create a separate database for each life area.

Recommended sections:

```text
# Requirements Map

Status
Owner and authority
Purpose

## Design correction or starting context
## Operating principle
## Capacity boundaries
## Confirmed workflow requirements
### Communication and obligations
### Financial/admin delivery
### Content and creative work
### Revenue or business model
### High-risk domains
## Architecture requirements implied by discovery
## Discovery still required
## Provenance
```

### Requirements writing rules

- Write observable needs, not imagined features.
- Preserve the user's exact approval boundaries.
- Mark unknowns as unknown.
- Separate aspirations from planning assumptions.
- Do not convert a remembered automation into a verified capability.
- Do not store passwords, verification codes, financial account numbers, or private client details.

### Verification checkpoint

Ask the AI:

```text
Audit the Requirements Map against this interview. List:
1. confirmed requirements;
2. assumptions that slipped in without confirmation;
3. contradictions;
4. missing discovery questions;
5. proposed components that do not trace to a verified requirement.

Do not edit yet. Show evidence for every finding.
```

Resolve the findings before architecture begins.

## Step 0.4 — Inventory current systems without designing replacements

Create a compact Current Systems Inventory.

For each system record:

| Field | Question |
|---|---|
| System | What tool, account, channel, person, or file is involved? |
| Current role | What does it actually do today? |
| Status | Verified current, reported current, legacy, or unverified? |
| Authorized conclusion | What may the system safely conclude? |
| Not authorized | What must it not assume? |
| Access | Is access verified, partial, blocked, or unknown? |
| Proof | What direct observation supports the status? |

Do not purchase replacements during this step.

## Step 0.5 — Define authority classes

Use three execution classes:

1. **Autonomous routine:** rules, access, risk boundary, and verification are known. AI acts and returns proof.
2. **Approval required:** AI completes preparation, then requests the smallest consequential approval at action time.
3. **Blocked exception:** a fact, access step, authentication, conflict, or judgment is missing. AI returns the exact blocker and resume state.

### Copy-and-paste prompt: authority interview

```text
For every confirmed recurring workflow, identify the smallest meaningful actions inside it. Classify each action as autonomous routine, approval required, or blocked exception.

Do not classify an entire workflow as high risk merely because one step is consequential. AI should complete safe preparation and stop only at the true boundary.

For every approval-required action, state:
- the exact action;
- the destination;
- the information being transmitted or changed;
- what preparation can be completed first;
- what proof should be captured after approval.
```

## Step 0.6 — Establish the archive boundary

Identify every old workspace, retired plan, archive folder, and legacy workbench section. Record only its location and status. Do not open it during routine installation.

Required rule:

```text
Archives are excluded from routine retrieval. Do not open, search, summarize, reorganize, move, or use an archive unless I explicitly name the archive and state the purpose of the review. Preserve all intellectual property; archive rather than delete.
```

## Step 0.7 — Define the 90-day product target

Write measurable outcomes, not architecture tasks.

Strong acceptance criteria include:

- The user can ask once without choosing an LLM.
- The system routes by verified capability, risk, quality, and cost.
- Completed work returns destination proof.
- Blocked work returns one exact exception and resume state.
- A new supported LLM can orient without chat history or provider memory.
- The private remote, recovery instructions, and health check are verified.
- At least one real workflow runs end to end before expansion.

Weak criteria include "build dashboard," "set up a workspace," or "write prompts." Those are implementation details, not proof of usefulness.

## Step 0.8 — Build the phased roadmap

Recommended sequence:

- **Phase 0:** requirements discovery and authority boundaries.
- **Phase 1:** canonical foundation, private recovery, machine-readable entry, and health verification.
- **Phase 2:** orchestration contract, capability routing, receipts, and exception channel.
- **Later phases:** one real workflow family at a time, ordered by consequence and recurring pain.

Every phase must have an exit test.

## Phase 0 exit test

Phase 0 is complete when:

- Every planned Phase 1 component traces to a verified requirement.
- The system knows what is current, unknown, legacy, and prohibited.
- Approval boundaries are explicit.
- Archives are identified and excluded.
- Ninety-day success is measurable.
- The roadmap has non-goals and exit tests.
- The user has corrected the Requirements Map and recognizes it as accurate enough to build from.

---

# Part III — Phase 1: Install the durable foundation

## Phase 1 objective

Give any authorized LLM one reliable place to learn what the system is, what is current, where durable work belongs, and how to verify health—without reading archives or reconstructing context from chats.

## Phase 1 deliverables

- Local canonical repository
- Standard folder structure
- Start Here file
- Schema
- Requirements Map and roadmap
- Asset Registry
- Decisions and Change Log
- Session Index and provenance standard
- Workspace Directory
- Context Pack Core
- Maintenance protocol
- Private Git remote
- Machine-readable manifest
- Automated health check
- Recovery instructions
- Human-readable foundation pointer

## Step 1.1 — Choose the canonical root

Use a dedicated folder separate from any legacy workspace.

Recommended name:

```text
[SYSTEM NAME]/
```

Use a different system name if needed. Avoid names already attached to older projects.

## Step 1.2 — Create the minimum folder structure

```text
[SYSTEM NAME]/
├── 00-Control/
├── 01-Projects/
├── 02-Areas/
├── 03-Resources/
│   ├── raw-sources/
│   ├── wiki/
│   └── templates/
├── 04-Archive/
├── 05-Build-Notes/
├── 06-Proposals/
├── scripts/
├── START-HERE.md
├── SYSTEM-MANIFEST.json
├── SYSTEM-SCHEMA.md
└── README.md
```

The folders may be empty. Do not invent content to make them look complete.

### Copy-and-paste prompt: create the foundation

```text
Create a local-first AI operating-system foundation in [ABSOLUTE PATH].

Before changing anything:
1. state the single active objective;
2. confirm each proposed file directly advances it;
3. inventory the target folder read-only;
4. do not read or modify any legacy or archive folder;
5. preserve all existing files and IP;
6. use tracked, in-place edits and dated pre-change copies for material changes.

Create only the minimum Phase 1 structure:
00-Control, 01-Projects, 02-Areas, 03-Resources, 04-Archive, 05-Build-Notes, 06-Proposals, scripts, Start Here, manifest, schema, and README.

Local Markdown + Git will be canonical. The human-readable workbench will be a pointer and working surface, not a full mirror. Do not create workflows, projects, CRMs, databases, content, or automations.
```

## Step 1.3 — Create the control files

Minimum controls:

| File | Purpose |
|---|---|
| `START-HERE.md` | Mandatory cross-LLM entry path and safety rules |
| `SYSTEM-SCHEMA.md` | Knowledge layers, authority, drift prevention, complexity gate |
| `00-Control/REQUIREMENTS-MAP.md` | Verified lived requirements |
| `00-Control/BUILD-ROADMAP.md` | Phases, exit tests, acceptance criteria, non-goals |
| `00-Control/ASSET-REGISTRY.md` | Canonical home, status, pointers, last review |
| `00-Control/DECISIONS.md` | Current consequential decisions |
| `00-Control/CHANGELOG.md` | Plain-language material changes |
| `00-Control/SESSION-INDEX.md` | Actor, sources, assets, verification, destination |
| `00-Control/PROVENANCE-STANDARD.md` | Required trace fields and location rules |
| `00-Control/WORKSPACE-DIRECTORY.md` | Stable work-cell IDs across providers |
| `00-Control/CONTEXT-PACK-CORE.md` | Small portable operating rules |
| `00-Control/MAINTENANCE-PROTOCOL.md` | Start, work, close, weekly review, drift triggers |
| `00-Control/RECOVERY.md` | Restore and verify on a new machine |

### Asset Registry rule

Add an asset to the registry before creating a durable file. Mark a successor before archiving a superseded asset. A blank workbench URL means no counterpart exists.

## Step 1.4 — Write the Start Here file

The Start Here file should tell a new LLM:

1. What is canonical.
2. What to read first.
3. What current instruction outranks.
4. Which archives are prohibited.
5. When to execute, ask, or stop.
6. How to close material work.
7. That summary-only dead ends are not acceptable while safe work remains.

### Copy-and-paste prompt: Start Here review

```text
Review the Start Here file as if you were a capable LLM with no chat history. Without opening any other file, can you identify:
- the source of truth;
- the minimum reading order;
- the active objective gate;
- archive prohibitions;
- authority boundaries;
- the expected execution behavior;
- the closeout protocol?

List missing or ambiguous instructions. Do not expand the file unless the addition changes behavior.
```

## Step 1.5 — Initialize local Git

Git supplies version history, but local Git alone is not off-device recovery.

Required states:

1. Repository initialized.
2. Initial foundation checkpoint committed.
3. Private empty remote repository created.
4. Local `origin` connected.
5. `main` pushed.
6. Local branch tracks remote `main`.
7. Local and remote heads match.

### Copy-and-paste prompt: private recovery setup

```text
Set up private Git recovery for this operating-system folder.

Requirements:
- keep local Markdown canonical;
- create or use a private empty remote repository;
- never expose credentials in files or command output;
- connect the local repository as origin;
- push main;
- verify the tracked branch;
- compare local HEAD with remote main;
- do not call the backup complete until they match;
- record the repository in the Asset Registry, Change Log, Session Index, and Recovery file.

If any access or authorization layer fails, diagnose provider connection, repository access application installation, repository scope, indexing, and direct repository retrieval separately.
```

## Step 1.6 — Verify connector access layer by layer

A provider can display `Connected` while still returning no repositories.

Check these separately:

1. Provider authorization exists.
2. The official repository access application is installed.
3. The App is scoped to the intended private repository.
4. Repository indexing is complete where required.
5. The connector can retrieve the named private repository.
6. Write access is tested only when the workflow requires it.

### Troubleshooting pattern

| Symptom | Likely missing layer | Verification |
|---|---|---|
| Connected, no repositories | repository access application not installed or no repo scope | Inspect repository access application installations |
| Repository installed, picker empty | Indexing or provider sync delay | Trigger/check index, then direct retrieval |
| Search finds code, connector cannot | Connector installation/authorization | List installations and retrieve named repo |
| Local looks current, remote does not | Unpushed commits or wrong branch | Compare local HEAD and remote main |

Do not solve these by waiting indefinitely. Identify the failed layer.

### Verify the exact provider surface

For every provider the system may route work to, record the mode as well as the provider:

| Surface class | Typical source path | Proof required |
|---|---|---|
| Standard chat | Attached files or enabled connector | Retrieves the named active file |
| Browser or cloud task | Cloud connectors and browser-visible sources | Retrieves the named source and states whether local files are unavailable |
| Coding or repository mode | Local clone or private remote repository | Reads the manifest and startup file from the named repository and branch |
| Desktop local-folder mode | Explicitly attached canonical folder | Reads the manifest and startup file from the exact local path |

Run the read-only clean-room test on each intended surface separately. When permission controls exist, begin with session-only folder access and manual approval. Require file or repository citations, confirm no changes occurred, and record the result as read-verified only. Promote write access only after a separate supervised write-and-receipt test.

Do not copy canonical controls into provider-specific project knowledge to compensate for a blocked surface. That creates a stale duplicate. Route the work to a verified surface or produce the exact handoff.

## Step 1.7 — Create the machine-readable manifest

The manifest is the fastest safe entry point for a new LLM.

Minimum fields:

```json
{
  "schema_version": "1.0",
  "system": "[SYSTEM NAME]",
  "system_version": "0.1.0",
  "canonical_root": "[ABSOLUTE PATH]",
  "workspace_id": "SYS-[UNIQUE ID]",
  "active_objective": "[ONE SENTENCE]",
  "startup_file": "START-HERE.md",
  "health_command": "scripts/check-system-health.sh",
  "recovery_file": "00-Control/RECOVERY.md",
  "archive_policy": "Archives are excluded unless explicitly named for a stated review purpose.",
  "canonical_assets": [],
  "execution_surfaces": [],
  "canonical_destinations": {},
  "health": {
    "expected_state": "healthy",
    "last_verified": "YYYY-MM-DD",
    "checks": []
  }
}
```

Rules:

- Every manifest asset must exist.
- Every manifest asset must have a registry ID.
- The manifest describes observed access, not imagined capability.
- Do not store tokens, credentials, or private client data.

## Step 1.8 — Install the health check

The health check should validate active controls only. It must not enter an archive.

Minimum checks:

- Manifest parses as valid JSON.
- Every canonical manifest path exists.
- Every manifest asset ID appears in the Asset Registry.
- Git worktree is clean.
- Remote `main` matches local `HEAD`.
- Start Here contains the archive boundary.

Expected result:

```json
{
  "state": "healthy",
  "checks": {
    "manifest_valid": true,
    "canonical_paths_present": true,
    "registry_ids_present": true,
    "git_clean": true,
    "remote_main_matches_local": true,
    "archive_boundary_present": true
  },
  "errors": []
}
```

### Copy-and-paste prompt: health checker

```text
Create a read-only health checker for the active operating-system controls.

It must:
- validate the JSON manifest;
- verify canonical asset paths;
- verify registry coverage;
- detect a dirty Git worktree;
- compare local HEAD with private remote main;
- verify the startup archive boundary;
- return machine-readable healthy/unhealthy output and exact errors;
- never read archive contents;
- never repair, delete, reset, or overwrite anything automatically.

Run it before material infrastructure work and after the verified checkpoint is pushed.
```

## Step 1.9 — Write recovery instructions

Recovery must work without the workbench, model memory, or old chats.

Required recovery sequence:

1. Install Git and authenticate the repository account.
2. Clone private `main` to the canonical path.
3. Run the health check.
4. Open Start Here.
5. Reconnect only the execution surfaces required for the current objective.
6. Reconcile the workbench only where the Asset Registry names a counterpart.

Recovery is complete only when the health command is healthy, Git is clean, and local/remote match.

## Step 1.10 — Create the workbench foundation

Create one readable Foundation page in the chosen workbench. Do not paste the entire repository into it.

Recommended sections:

- Status
- What the system is
- Canonical-source statement
- Current objective and current phase
- Core rules
- Archive boundary
- Links to active workbench pages
- Maintenance and handoff summary
- Provenance line

Create long-form teaching manuals as separate child pages. Preserve historical notes; correct only stale live status or unsafe active instructions.

## Step 1.11 — Install provenance and closeout

Every material change records:

- record ID;
- date;
- human and AI actor;
- session label;
- workspace ID;
- action;
- affected assets;
- source basis;
- verification;
- version-control and workbench references.

Material closeout checklist:

- Durable asset saved in canonical home.
- Registry current.
- Session/provenance entry current.
- Change Log current.
- Sanitized teaching lesson current.
- Git checkpoint created.
- Checkpoint pushed.
- Health check passes.
- workbench updated only where relevant.
- Pending transfers named explicitly.

## Step 1.12 — Run the clean-room LLM test

Use a new chat or a supported LLM that has no prior conversation history.

### Clean-room prompt

```text
You are entering an unfamiliar AI operating-system repository.

Read the machine manifest first, then follow the startup file. Do not open any archive. Do not make changes.

Report only:
1. system name and version;
2. active objective;
3. canonical source and destinations;
4. prohibited sources;
5. required health command;
6. whether the system is healthy;
7. what information is still required before consequential work.

For every statement, name the active source that supports it. If you cannot determine something, say unknown.
```

Repeat this test for every provider surface the router may use. Record the exact surface, source path, permission mode, citations, and whether any files changed. Do not generalize a pass or failure from one surface to another.

Pass conditions:

- Correct system identity.
- Correct active objective.
- No archive access.
- Correct source hierarchy.
- Correct health result.
- No invented current business facts.
- No material changes.

## Phase 1 exit test

Phase 1 is complete only when a clean-room agent can identify:

- system version;
- current objective;
- allowed and prohibited sources;
- canonical destinations;
- approval boundaries;
- recovery path;
- health state;

and the following are true:

- Local Git is clean.
- Private remote `main` matches local.
- Health check passes.
- the workbench accurately identifies local files as canonical.
- Existing records are preserved.
- No workflow or automation was invented merely to fill the structure.

---

# Part IV — Failure modes and what to do instead

## Failure 1 — Architecture before interview

**Symptom:** A beautiful control layer exists, but it does not address the user's real recurring failures.

**Correction:** Stop building. Run Phase 0. Trace every existing component to a verified requirement; archive or park unsupported components.

## Failure 2 — Scope drift disguised as helpfulness

**Symptom:** The AI creates a lead log, workshop asset, source pack, CRM, or database because it might be useful.

**Correction:** Restate the single active objective. If the asset does not directly advance it, capture the idea without building it.

## Failure 3 — Treating the archive as a migration queue

**Symptom:** The AI inventories, reorganizes, or promotes old material during routine work.

**Correction:** Treat the archive as intact and excluded. Review only a named item for a stated purpose with explicit authorization.

## Failure 4 — Full workbench mirroring

**Symptom:** Local Markdown and the human-readable workbench both contain full operating documents and begin to disagree.

**Correction:** Pick one canonical home. Keep workbench summaries, links, decisions, and workbench content only.

## Failure 5 — Connected mistaken for working

**Symptom:** A provider says remote host is connected, but the repository picker is empty.

**Correction:** Verify authorization, repository access application installation, repository scope, indexing, and direct retrieval separately.

## Failure 6 — Local Git mistaken for backup

**Symptom:** Commits exist only on one computer.

**Correction:** Add a private remote, push, and compare local/remote heads.

## Failure 7 — Naming collision

**Symptom:** A new system component reuses the name of an older project and confuses humans and LLMs.

**Correction:** Standardize one unique current name, rename active assets, and verify the retired term is absent from active controls.

## Failure 8 — Structural review called a deep review

**Symptom:** An AI lists folders or headings and claims it fully understands the content.

**Correction:** Label evidence honestly: structural inventory, targeted content review, or bounded deep audit. State exactly what was read.

## Failure 9 — Summary-only handoff

**Symptom:** The AI tells the user what should happen next but neither does it nor asks for the exact required approval.

**Correction:** Continue all safe work. At the true boundary, ask one concrete action-time question naming the action and destination.

## Failure 10 — Over-documenting routine work

**Symptom:** Every reply or temporary draft triggers a full governance ceremony.

**Correction:** Use a concise execution receipt for routine work. Reserve registry, changelog, session trace, teaching record, Git checkpoint, and health verification for material system changes.

## Failure 11 — One provider surface mistaken for the whole provider

**Symptom:** A browser or cloud task cannot reach local files, so the AI declares that the provider cannot use the operating system—even though a desktop folder mode or coding mode exists.

**Correction:** Name and test each surface separately. Verify the exact canonical path, permission mode, citations, and no-change result. Promote only the capability actually proven.

---

# Part V — Master installation prompt

Use this when a capable coding or computer-use agent has access to the intended local folder and remote host. Replace bracketed values first.

```text
Build Phase 0 and Phase 1 of my personal AI operating system.

USER
- Name: [NAME]
- System name: [SYSTEM NAME]
- Canonical local path: [ABSOLUTE PATH]
- Private Git remote account/repository: [ACCOUNT/REPOSITORY or CREATE PRIVATE EMPTY REPOSITORY]
- Human-readable workbench: [TOOL OR NONE]
- Legacy/archive locations: [LIST LOCATIONS WITHOUT OPENING THEM]

OPERATING BOUNDARIES
- Local Markdown + Git are canonical.
- Private Git remote is off-device recovery and cross-LLM continuity.
- The chosen human-readable workbench is a pointer and working surface, not a full duplicate.
- Preserve all IP. Never delete. Archive with a dated record.
- Do not open, search, summarize, move, or use any archive unless I explicitly name it and state the purpose.
- Never store credentials, passkeys, authentication codes, client secrets, or financial account numbers in the repository, prompts, the workbench, or logs.
- Before every material change, state the single active objective and whether the change directly advances it.
- Do not create a CRM, lead log, project database, content asset, workflow, automation, dashboard, or new process unless it traces to a verified current requirement.
- Do not claim a deep review when only structure was inspected.
- Do not stop with a summary while safe work remains.

PHASE 0
1. Interview me one focused question at a time about recurring responsibilities, consequences, tools, memory-held rules, access, desired autonomy, approval boundaries, privacy, and 90-day success.
2. Create a Requirements Map containing only confirmed facts and explicit unknowns.
3. Create a Current Systems Inventory distinguishing verified, reported, unverified, and legacy states.
4. Classify actions as autonomous routine, approval required, or blocked exception.
5. Establish the archive boundary and explicit non-goals.
6. Create a phased roadmap with measurable acceptance criteria and an exit test for every phase.
7. Do not begin Phase 1 until the Requirements Map has been corrected and is accurate enough to build from.

PHASE 1
1. Inspect the target path read-only.
2. Create the minimum folder structure and control files.
3. Add Start Here, schema, registry, decisions, changelog, session index, provenance, workspace directory, context core, maintenance, and recovery controls.
4. Initialize Git and make intentional checkpoints.
5. Create or connect a private empty remote repository, push main, and verify local/remote parity.
6. Create a machine-readable manifest.
7. Create a read-only health checker for manifest validity, canonical paths, registry coverage, Git cleanliness, remote parity, and archive boundary.
8. Create one workbench foundation page with status, current phase, rules, and pointers; do not mirror the repository.
9. Run a clean-room LLM test.
10. Record every material change in the registry, changelog, session trace, teaching notes, Git, and relevant workbench page.

CHANGE CONTROL
- Before editing an existing durable file, preserve a dated pre-change copy.
- Make tracked in-place edits; do not blanket rewrite existing files.
- Verify content, JSON, paths, Git diff, and destination state.
- Push the checkpoint.
- Run the health check after push.
- Call Phase 1 complete only when the health result is healthy and local main matches remote main.

TEACHING OUTPUT
For every material decision, preserve a sanitized lesson containing:
- need;
- failed assumption;
- durable principle;
- reproducible steps;
- verification method;
- reusable learner prompt or exercise;
- universal rule versus private configuration.

Start with the Phase 0 interview. Ask only the first question.
```

---

# Part VI — Workshop facilitator SOP

## Recommended delivery format

Phase 0 should be completed before the installation workshop or as a dedicated first workshop. Do not spend live workshop time creating folders while the learner's requirements are unknown.

### Pre-work

Learners bring:

- A laptop with their preferred AI assistant.
- A remote hosting account.
- Access to any knowledge tool they choose for the optional workbench.
- A written list of recurring responsibilities and known tools.
- Locations of archives, listed but not opened.
- No passwords or authentication codes in the workbook.

### Session 1 — Phase 0 discovery

1. Explain source of truth, workbench, temporary work cell, and archive.
2. Run the requirements interview.
3. Draft and correct the Requirements Map.
4. Define authority classes.
5. Create acceptance criteria and non-goals.
6. End with the Phase 0 exit test.

### Session 2 — Phase 1 installation

1. Create the local canonical root.
2. Install the minimum structure.
3. Create controls.
4. Initialize local Git.
5. Create and verify private Git remote recovery.
6. Create manifest, health check, and recovery instructions.
7. Create the workbench foundation pointer.
8. Run the clean-room test.
9. Check Phase 1 exit criteria.

### Teaching standard

Do not demonstrate success by showing your own finished dashboard. Demonstrate the learner's system passing verification.

### Instructor diagnostic questions

- What real recurring failure does this component solve?
- Which source currently has authority?
- Is this observed, reported, or assumed?
- What is the smallest reversible next action?
- What proves the destination changed?
- What belongs in the archive rather than active retrieval?
- If this page disappeared, where would canonical truth remain?

---

# Part VII — Final installation checklist

## Phase 0

- [ ] Requirements interview completed.
- [ ] Requirements Map corrected by the learner.
- [ ] Current Systems Inventory distinguishes verified, reported, unverified, and legacy.
- [ ] Approval and autonomy boundaries recorded.
- [ ] Archive locations recorded without routine retrieval.
- [ ] Ninety-day acceptance criteria are measurable.
- [ ] Roadmap includes exit tests and non-goals.
- [ ] Every Phase 1 component traces to a verified need.

## Phase 1

- [ ] Dedicated local canonical folder exists.
- [ ] Local Git repository exists.
- [ ] Minimum folder structure exists.
- [ ] Start Here identifies authority, reading order, archive boundary, and execution behavior.
- [ ] Schema, registry, decisions, changelog, session trace, and provenance exist.
- [ ] Requirements Map and roadmap are current.
- [ ] Private Git remote repository exists.
- [ ] Local `main` tracks remote `main`.
- [ ] Local and remote heads match.
- [ ] Connector access has been tested directly if used.
- [ ] Manifest parses.
- [ ] Every manifest path exists.
- [ ] Every manifest ID is registered.
- [ ] Health check passes.
- [ ] Recovery instructions are complete.
- [ ] The workbench foundation names local files as canonical and does not mirror them.
- [ ] Clean-room LLM test passes without archive access.
- [ ] Material changes have provenance, teaching records, Git checkpoints, and destination verification.

## Stop condition

Do not begin Phase 2 because the folders look finished. Begin only after the Phase 1 exit test passes.

---

# Current limitations of this manual

- Remote-host and workbench interfaces can change; verify current screens and official instructions during installation.
- The guide assumes a capable AI can operate local files and Git. A learner using chat-only AI may need guided file creation.
- Windows paths and shell commands require platform-specific adaptation.
- Privacy, regulated data, client confidentiality, and employer policies require learner-specific review.
- Phase 2 orchestration, external execution, mobile exception channels, and business workflows are intentionally outside this guide.

---

## Provenance and teaching boundary

This manual was derived from one verified Phase 0 and Phase 1 implementation, its current controls, build records, version history, and observed results. No archive was opened or used. The teaching method excludes implementation-specific identities, credentials, private data, and configuration.

**Universal:** requirements before architecture, one canonical home, archive exclusion, verified capabilities, private recovery, machine-readable entry, health checks, provenance, and clean-room testing.

**Implementation-specific configuration:** system name, paths, accounts, tools, operating facts, autonomy boundaries, and workflow priorities.
