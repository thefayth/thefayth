# THEFAYTH

![THEFAYTH hero](assets/hero/hero-image.png)

THEFAYTH is a protected public project surface for a memory-centered forum, archive, and project gateway. It presents the public face of Faith's world-building, recall work, multilingual discussion, and AI-assisted forum lanes while keeping the private engine, operational workflows, prompts, credentials, and unpublished materials out of the repository.

This repository is a protected public project surface. It is not the full source code, operational system, private workflow, or data room.

![GitHub banner](assets/banners/github-banner.png)

## Why It Matters

THEFAYTH gives memory work a public architecture: rooms, threads, source-backed discussion, project spokes, and a boundary-aware relationship between a public website and protected private systems. It is designed for stories that need context, provenance, language nuance, and human review instead of flattened content feeds.

## Who It Is For

- Readers and collaborators who need a clear public overview of THEFAYTH.
- Visitors coming from FaithCheltenham.com or thefayth.net.
- Supporters who need to understand the public mission without accessing private systems.
- Future contributors who need boundaries before asking for source, strategy, or operational access.

## How It Works

THEFAYTH has a public surface and a private engine.

```mermaid
flowchart LR
  visitor[Visitor] --> publicSite[thefayth.net]
  publicSite --> rooms[Forum rooms]
  publicSite --> archive[Archive and project pages]
  rooms --> review[Human review]
  review --> publicOutputs[Public threads and pages]
  privateEngine[Private engine] -. protected .-> review
  privateEngine -. not released .-> prompts[Prompts, workflows, credentials]
```

![Workflow overview](assets/diagrams/workflow-overview.svg)

## Public Materials

This repository includes:

- Project brief, status, roadmap, FAQ, and public-private boundary notes.
- Workflow diagrams for the forum/archive/review model.
- WordPress page and metadata drafts for FaithCheltenham.com.
- Public-safe visual assets selected from the project folder.
- Ownership, trademark, security, and commercial use policies.

## What Remains Private

The source code, WordPress deployment, credentials, prompts, private workflows, customer or family information, unpublished creative work, legal/admin material, medical or benefits records, and operational infrastructure are not included.

## Current Status

Public surface package: ready for review.

Live public site: https://thefayth.net

Faith ecosystem connection: https://faithcheltenham.com

## Visual System

![Social card](assets/social/social-card.png)

The selected visual language is ethereal, archival, strategic, and human: memory, signal, world-building. It uses existing project visuals instead of generic templates.

## Ownership

All rights reserved. No public license is granted. No redistribution, commercial reuse, training use, or source-code use is permitted without written permission from Faith Cheltenham.

## Learn More

- Public site: https://thefayth.net
- FaithCheltenham.com: https://faithcheltenham.com
- WordPress draft: [wordpress/page.md](wordpress/page.md)
- Project brief: [docs/PROJECT_BRIEF.md](docs/PROJECT_BRIEF.md)
- Boundary notes: [docs/PUBLIC_PRIVATE_BOUNDARY.md](docs/PUBLIC_PRIVATE_BOUNDARY.md)
