# AI Generation Protocol

## Goal
Minimize identity drift, geometry drift, unwanted action, temporal instability and model improvisation.

## Reference Priority
1. immediately preceding approved shot/end frame
2. canonical character reference
3. canonical environment/geography reference
4. scene-specific wardrobe/prop reference
5. look/style reference

Use the smallest package that fully constrains the shot.

## Prompt Architecture
### A — Continuity Lock
What cannot change.

### B — Camera
Placement, height, angle, framing, lens intent and movement.

### C — Action Timeline
Ordered actions. Avoid ambiguous simultaneous choreography.

### D — Environmental Motion
Rain, foliage, smoke, practical lights and other secondary motion.

### E — End State
The exact composition/action state needed for editorial continuity.

### F — Exclusions
Likely generation errors that would break the shot.

## Action Budget
If a shot requires too many independent actions, split it. Shot design is preferable to hoping the model solves excessive choreography.

## Generation Loop
1. validate shot spec
2. select references
3. establish start state
4. define necessary motion
5. generate candidate
6. inspect motion
7. inspect continuity
8. approve/reject
9. register output
10. promote approved end state downstream

## Flow Working Model
Treat Flow as a shot-generation environment, not an autonomous director. Use reference-driven shots, constrained actions, explicit camera instructions, short controllable motion units and approved outputs as anchors.

Do not assume the model remembers prior clips, knows off-screen geography, preserves unseen props, understands “same” without references, or reliably infers the intended final pose.

## Empirical Production Knowledge
Record repeated successes/failures in the Generation Log. Prompt and reference strategy should evolve from observed model behavior.
