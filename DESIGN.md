# Fiji Pig Fishing v3.0 — Intent and design requirements

## Core goal
Catch five virtual Fiji-inspired fish in four minutes.

## Interaction requirements
- Cast and jig a reflective spoon lure with treble hook.
- Full-reel bite overlay appears during bite and disappears after hook-set.
- Reel requires clockwise circular pointer motion using one knob and one attached arm.
- RPM is calculated from angular displacement across a rolling 420 ms window.
- Valid reel range is 170–235 RPM, centered at 200 RPM.
- Only valid-rate clockwise radians retrieve line.
- Retrieval distance is directly tied to accumulated valid revolutions.
- Slow reeling drops pressure; fast reeling raises pressure.

## Visual requirements
- Stylized voxel pig on three-leg stool above water.
- Stool rests on a wood dock with four support posts.
- Defined aquarium frame, coral, fish eyes, triangular dorsal fins, lure, rod, and metal bucket.
