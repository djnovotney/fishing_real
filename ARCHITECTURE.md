# Architecture v2.3

- Three.js renders the aquarium, fish, pig, dock, rod, lure, coral, and catch sequence.
- The gameplay state machine is: idle, ready, casting, waiting, bite, reeling, landing, done.
- Reel pointer events are isolated to the handle and require capture, hold, and clockwise rotation.
- Reel angular rate drives pressure. Valid rate retrieves line; low rate loses pressure; high rate increases pressure.
- Vite creates a static relative-path build for GitHub Pages.
