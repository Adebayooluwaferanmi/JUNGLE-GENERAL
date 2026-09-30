# Reference Registry

**Storage architecture:** Google Drive stores production media; GitHub stores canonical metadata, continuity authority and production relationships.

| Ref ID | Type | Subject / Authority | Status | Actual Filename | Drive File ID | Drive Folder |
|---|---|---|---|---|---|---|
| JG-REF-CHAR-MRS-OKORO-001 | character | Mrs. Okoro identity; civilian family wardrobe baseline | LOCKED | `Mrs Okoro.webp` | `19Oq2ExO_mNDL4kPT2bjC06X303FTko-_` | `01_CHARACTERS` |
| JG-REF-CHAR-MR-OKORO-001 | character | Mr. Okoro identity; Episode 1 patient | LOCKED | `Mr Okoro.webp` | `1L4MmrnHkyAPw9gTHYStKKLRWkrsTG0xb` | `01_CHARACTERS` |
| JG-REF-CHAR-CHIDI-001 | character | Chidi Okoro identity; young adult son; civilian | LOCKED | `Chidi Okoro.webp` | `1-yEAiO-jO_10gaRnBlm_7SDG4dk6uh10` | `01_CHARACTERS` |
| JG-REF-ENV-LAB-MASTER-001 | environment | Diagnostic Laboratory master look/geography | LOCKED | `LOCATION_MASTER_DIAGNOSTIC_LAB.webp` | `139GcJOXctGpZwdDZGgCrzchqDk-7cFlB` | `02_ENVIRONMENTS` |
| JG-REF-ENV-LAB-A-001 | environment | Lab A — Specimen Reception | LOCKED | `LAB_A_SPECIMEN_RECEPTION.webp` | `1VFcWJ0q8fV5DVPvfp0QDTXBm0irkf7hh` | `02_ENVIRONMENTS` |
| JG-REF-ENV-LAB-B-001 | environment | Lab B — Obinna Analytical Workstation | LOCKED | `LAB_B_OBINNA_ANALYTICAL_WORKSTATION.webp` | `1zVzXXXuaJdZ69CAaHXtsWpQ74i3-2JGJ` | `02_ENVIRONMENTS` |
| JG-REF-ENV-LAB-C-001 | environment | Lab C — Result Validation | LOCKED | `LAB_C_RESULT_VALIDATION.webp` | `1clnovN03y6v13s5nmqKE2Rkchpsg3-Vi` | `02_ENVIRONMENTS` |
| JG-REF-ENV-EXTERIOR-001 | environment | Jungle General exterior/storm/driveway world reference | LOCKED | `EXTERIOR REFERENCE.webp` | `1osGeMbGxaSSN15YoUTJpfe3f8rsY2AiM` | `02_ENVIRONMENTS` |
| JG-REF-ENV-EMERG-REV-001 | environment/keyframe | Emergency reverse driveway: camera inside behind bed looking outward to SUV/driveway | LOCKED | `EMERGENCY_REVERSE_DRIVEWAY_01.jpg` | `1aaD6zN4o1uWgrXfP49KKiQ_zq1Ly7EWC` | `02_ENVIRONMENTS` |

## Google Drive Root
- Folder: `JUNGLE GENERAL`
- Folder ID: `1t5-Wgqf2xFkFhwhb8_i9Nz2fRgbKEFVq`

## Canonical Laboratory Geography
The laboratory reference family is organized as:

`LOCATION_MASTER_DIAGNOSTIC_LAB → LAB_A_SPECIMEN_RECEPTION → LAB_B_OBINNA_ANALYTICAL_WORKSTATION → LAB_C_RESULT_VALIDATION`

These images define different production zones within the same diagnostic-laboratory world. They are not interchangeable shot backgrounds.

## Character Rules
### Mrs. Okoro
- family member / wife
- civilian
- never convert to nurse, doctor, laboratory worker or other clinical staff without an explicit story revision

### Mr. Okoro
- Episode 1 patient
- identity must remain stable from arrival through Emergency treatment

### Chidi Okoro
- young adult son
- civilian
- may interact at the public/specimen-reception boundary but must not be visually converted into laboratory or clinical staff

## Environment Rules
### Exterior Reference
Controls the larger Jungle General exterior visual world: storm, jungle/root-integrated hospital architecture, driveway and approach atmosphere.

### Emergency Reverse Driveway
Controls the reverse spatial relationship from inside Emergency: bed foreground/interior → Emergency entrance → exterior driveway/SUV. It is a geography reference, not permission to redesign the exterior.

## Status Vocabulary
- CANDIDATE
- APPROVED
- LOCKED
- SUPERSEDED
- REJECTED

## Filename Rule
Preserve the **actual uploaded/generated filename**. Stable JG reference IDs are metadata identifiers and must not replace source traceability.

## Storage Rule
Google Drive file ID is the persistent media locator. Do not duplicate large production binaries in GitHub merely to make them accessible.

## Canon Rule
Presence in Drive does not make an asset canonical. Canon status is explicit in this registry.
