# Orbital Watch: Space Situational Awareness

A live, browser-based SSA console. It shows about 16,000 tracked objects on a 3D/2D globe using live NORAD orbital data from CelesTrak, propagated in real time with SGP4.

**Live site:** https://akw12.github.io/ssa/

## Features
- Live globe (3D / 2D / 2.5D) with objects colored by orbit regime or object type
- Orbit traces, ground tracks and coverage footprints for selected and watched objects
- Watchlist with live state, next pass and alerts (saved in your browser)
- Ground-site pass predictions, a sky view and an "overhead now" list
- Conjunction screening (close-approach search) against the loaded catalog
- Time controls: pause, 1× to 3600×, ±1 h jumps, return to live

## Data & accuracy
Orbital elements come from [CelesTrak](https://celestrak.org) and are cached for 2 hours per CelesTrak's usage policy. TLE/SGP4 positions carry errors of about 1 km or more. Use the tool for awareness only, not for operational decisions.

Built with [CesiumJS](https://cesium.com/platform/cesiumjs/) and [satellite.js](https://github.com/shashwatak/satellite-js).
