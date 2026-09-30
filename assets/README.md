# Production Assets

Recommended organization:

- `characters/`
- `environments/`
- `wardrobe/`
- `props/`
- `vehicles/`
- `storyboards/`
- `keyframes/`
- `generated/stills/`
- `generated/video/`
- `audio/`
- `edit/`

## Rules
1. Preserve original filenames where they already exist.
2. Register production-critical assets in the Reference Registry.
3. Add stable JG IDs without destroying source traceability.
4. Avoid uncontrolled duplicate binaries.
5. Presence in this directory does not equal approval.
6. LOCKED assets should not be replaced silently.

Large media may later use Git LFS or an external media store if repository size becomes operationally inefficient.
