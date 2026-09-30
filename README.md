# JUNGLE GENERAL

> **AI Film Production Repository & Continuity Control System**

JUNGLE GENERAL is a continuity-first AI-generated film project. This repository is the **single source of truth** for story intent, characters, environments, cinematography, shot construction, AI generation, approved assets, continuity decisions, and final assembly.

## Production Principle

**Story first. Continuity always. Generation is production—not improvisation.**

Every generated frame or clip must inherit the approved state of the story world. A visually impressive output that breaks character identity, geography, wardrobe, props, lighting, screen direction, action state, or narrative intent is not production-ready.

## Production Format

- Primary framing: **9:16 vertical**
- Visual target: **cinematic hyperrealism / photorealistic live action**
- Delivery target: **4K where supported**
- Production approach: reference-driven, shot-based, continuity-controlled AI filmmaking

## Repository Map

| Area | Purpose |
|---|---|
| `docs/00-production-bible/` | Canon, creative intent, visual language, non-negotiables |
| `docs/01-story/` | Story, sequences, scenes, beats and chronology |
| `docs/02-continuity/` | Characters, wardrobe, props, vehicles, environments and state tracking |
| `docs/03-cinematography/` | Camera grammar, framing, movement and spatial rules |
| `docs/04-ai-generation/` | Flow strategy, prompt architecture, references and generation protocol |
| `docs/05-production/` | Shot registry, generation logs, approvals and edit handoff |
| `docs/06-qc/` | Continuity and technical acceptance gates |
| `assets/` | Approved production references and generated media |
| `templates/` | Reusable production records |

## Core Workflow

`CANON → SEQUENCE → SCENE → SHOT → REFERENCE PACKAGE → GENERATION → QC → APPROVAL → EDIT`

A shot may advance only when its upstream continuity state is known.

## Status Vocabulary

- **PLANNED** — specified but not generated.
- **GENERATING** — active generation/iteration.
- **REVIEW** — candidate exists and requires QC.
- **APPROVED** — accepted as continuity canon.
- **LOCKED** — must not change without an explicit continuity revision.
- **REJECTED** — not usable; retain diagnostic generation notes where useful.

## Asset Naming

Use stable IDs rather than descriptive filenames alone:

`JG_[SEQ]_[SCENE]_[SHOT]_[ASSET-TYPE]_[VERSION]`

Example: `JG_S01_SC03_SH007_KEYFRAME_v003.png`.

When an original uploaded/generated filename already exists, preserve that filename in the Reference Registry so the production record can be traced back to the actual source asset.

## Current Production Context

The active film work includes the Arrival / Emergency / Diagnostic Laboratory continuity chain. Existing approved images and clips from production must be registered before being treated as locked repository canon.

Known locked production rules include:

- Emergency Ward: antelope family/patient remain camera-left.
- Owl Doctor remains camera-right.
- Diagnostic Laboratory tunnel remains at the rear.
- Camera remains on the established side of the 180° axis unless an intentional reorientation shot is designed.
- The approved Diagnostic Laboratory wide-view reference governs laboratory geography.
- Continuity takes priority over visually impressive but spatially inconsistent generations.

## Operating Rule

Do not silently rewrite canon. Any change affecting an approved character, environment, geography, prop, wardrobe state, lighting state, screen direction, action or story event must be recorded as a continuity decision.

Start with the [Production Bible](docs/00-production-bible/PRODUCTION_BIBLE.md), [Continuity System](docs/02-continuity/CONTINUITY_SYSTEM.md), [Camera Bible](docs/03-cinematography/CAMERA_BIBLE.md), [AI Generation Protocol](docs/04-ai-generation/AI_GENERATION_PROTOCOL.md), and [Master Shot Registry](docs/05-production/SHOT_REGISTRY.md).
