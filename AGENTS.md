# OSARC Help: project instructions

## About this project

- Help center for OSARC (osarc.ai), built on Mintlify. Live at help.osarc.ai.
- Pages are MDX with YAML frontmatter. Navigation and branding live in `docs.json`.
- Audience: people who use OSARC every day: owners, managers, setters, callers, closers, coaches. Not developers.

## What OSARC is

OSARC is an AI-native operating system. ARC, the AI, is the brain. Apps are the tools the brain reaches for. Never describe OSARC as a CRM, a chief of staff, or a "COO in a box". Business is one room of the house, not the house.

## Terminology (strict)

- **Opportunity**: the card in a pipeline. The sales process.
- **Deal**: the package that was sold. Many deals can hang off one opportunity.
- **Transaction**: one movement of money. Many transactions per deal.
- **Skill**: a capability an app gives ARC. **Workflow**: a multi-step automation you build. **Playbook**: instructions ARC reads. **Hook**: something that runs when an event fires. Do not merge these words.
- **Proposal**: ARC's draft of a change. Nothing changes until a person approves it.
- **Set**: a call booked by a setter. **Show**: the person attended the call. **Booked call**: an appointment on the calendar.
- Use "app", "install", "desktop", "dock", "Launchpad". Not "module" or "feature".
- Roles: Client, Setter, Caller, Closer, Coach, Manager, Owner.

## Style

- Second person, active voice, sentence case headings.
- Short sentences. One idea per sentence.
- No em dashes. Use commas, colons, or parentheses.
- Bold UI elements: click **Settings**. Code formatting for URLs, slugs, and file names.
- Plain English. No internal names for code, tables, or scripts.
- Claims must be true of the live product. If unsure, leave it out.

## Content boundaries

- Document what people see and do in OSARC. Do not document server internals, deploy steps, secrets, or debugging procedures.
- Owner-only surfaces (Finance, Brain, Autopilot) get a short page or a note, not a walkthrough.
- Experimental apps (behind Labs) are mentioned as experimental, not documented in depth.
