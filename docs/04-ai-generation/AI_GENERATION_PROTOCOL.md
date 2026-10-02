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


## Production Prompt Standard — Allegory-Grade Shot Execution

Exploratory prose prompts are not sufficient for locked production shots. From the current production frontier onward, every production generation must be specified as a shot-execution document containing, where applicable:

1. **Shot ID / story function**
2. **Generation mode** — image-to-video, frames-to-video or extend; duration and aspect ratio.
3. **Reference authority** — precursor/start frame, character identities, environment master and any end-frame authority; state explicitly what each reference controls.
4. **Inherited continuity state** — exact location, character positions, physical condition, wardrobe, props, weather/wetness, lighting, screen direction and previous-shot exit state.
5. **Camera geometry** — physical placement, height, distance, lens intent, orientation, horizontal/vertical angle, 180-degree axis and foreground/midground/background relationships.
6. **Camera move / arc** — starting state, trajectory, direction, approximate arc where useful, speed, final camera position and prohibited movement.
7. **Subject blocking** — starting positions, facing direction, weight distribution, paths, physical contacts and screen-left/screen-right relationships.
8. **Timed action choreography** — action divided into explicit time windows rather than ambiguous simultaneous motion.
9. **Performance** — expression, eyeline, breathing, physical effort and character-specific behavior.
10. **Dialogue / lip sync** — exact speaker, line, voice, delivery, pace, inflection, non-speakers and reactions.
11. **Environmental motion** — rain, foliage, curtains, reflections, equipment and background activity.
12. **Lighting continuity** — existing practical sources and exposure relationship; no autonomous redesign.
13. **Audio stack** — dialogue, character Foley, object/vehicle Foley, ambience and music only when required.
14. **End-state / handoff frame** — exact final character/camera/geography/object state inherited by the next shot.
15. **Negative constraints** — no duplication, teleportation, morphing, environment redesign, invented entrances, axis violations, unrequested dialogue/text/cuts or other shot-specific failure modes.
16. **Priority order** — identity → spatial continuity → action continuity → camera → performance → environment motion → decorative detail.

### Precursor Image Rule
When a precursor image is supplied, treat it as the literal start-state and spatial authority, not merely visual inspiration. Preserve the controlled geometry, subject scale/orientation, architecture, practical-light placement and perspective unless the shot specification explicitly changes them.

### Current Arrival Performance Lock
For Mr. Okoro's supported walk, “weak” is not sufficient direction. His instability must be physically legible: compromised knee support/extension, short uncertain steps, partial downward yielding at the knees and torso, and credible counter-support from Chidi and Mrs. Okoro. Do not portray energetic independent walking, theatrical collapse or rag-doll motion.
