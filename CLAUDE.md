# Thinking Foundry Vault

## 🚨 GitHub PM + SOT

**GitHub is the full PM system and canonical source of truth for this project. Not just an issue tracker.** Durable bugs, tasks, follow-ups, specs, decisions, governance changes, and runbook-worthy findings must land in the correct GitHub repo as issues, issue-body updates, comments, linked milestones, or umbrella records. Local `.md` files support execution and AI continuity; they do not own durable project state.

**Automatic capture rule:** when an AI discovers work that obviously needs to be remembered, tracked, or acted on later, it must create or update the relevant GitHub issue before ending the session. If a fitting milestone or umbrella already exists, attach the issue there too. Do not leave durable project state stranded only in local `.md` files.

**This is the master repository for ALL thinking sessions.** Ideas, decisions, explorations, life choices, business strategies — everything that goes through The Thinking Foundry lands here as a GitHub issue.

## How It Works

Each thinking session = one GitHub issue. No separate repos for ideas. No folder sprawl.

### Issue Structure
- **Title:** `[THINKING] Short description of the question/decision`
- **Labels:** Domain label (`life`, `business`, `product`, `strategy`, `personal`, `finance`) + status label (`active`, `parked`, `promoted`, `decided`, `abandoned`)
- **Milestone:** Quarter-based (`2026-Q2`, etc.) for time-based filtering

### What Happens to Ideas

```
90% stay here forever as GitHub issues (decided, parked, or abandoned)
  → That's fine. The vault IS the knowledge base.

~10% get promoted to growthpigs/fledgling
  → FSD Approval Gate passes (confidence >= 7)
  → User explicitly says "I want to explore building this"
  → Issue gets label: promoted, with link to fledgling folder

~2-5% get promoted to their own project repo
  → "Drop the Hammer" decision from fledgling
  → Full Software Foundry scaffold created
  → Fledgling folder archived with pointer to new repo
```

### Cross-Referencing
Ideas interact. Reference other sessions with `#123` links. The vault is a knowledge graph of your thinking over time.

### Drive Sync
FSD outputs sync to Google Drive under `Thinking Foundry/` folder:
- `Active Sessions/` — current thinking
- `Decided/` — completed decisions
- `Promoted/` — FSDs that moved to fledgling
- `Abandoned/` — parked ideas (still valuable as reference)

## Rules
1. **Every thinking session gets an issue.** No exceptions.
2. **Use labels, not folders.** Labels are filterable; folders are not.
3. **The Thinking Foundry methodology repo** (`growthpigs/thinking-foundry`) is the TOOL. This vault is where the OUTPUT lives.
4. **Don't create separate repos for ideas.** That's what the fledgling repo is for, and only after promotion.
5. **Cross-reference liberally.** Ideas that connect strengthen each other.

## Labels

### Domain Labels
- `life` — personal decisions, lifestyle, family
- `business` — revenue, partnerships, strategy
- `product` — features, products, apps
- `strategy` — long-term direction, positioning
- `personal` — career, skills, growth
- `finance` — investments, budgets, money decisions

### Status Labels
- `active` — currently being worked through
- `parked` — not now, but not dead
- `promoted` — moved to fledgling repo
- `decided` — decision made, documented
- `abandoned` — explicitly killed with reasoning

### Phase Labels
- `phase:mine`, `phase:scout`, `phase:assay`, `phase:crucible`
- `phase:auditor`, `phase:plan`, `phase:verify`, `phase:autoresearch`
