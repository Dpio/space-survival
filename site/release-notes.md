# SpaceSurvival 0.3.0

The visual clarity release.

## Player-visible highlights

- New white/cyan player hull and a cohesive mechanical enemy fleet, retaining visible weapon upgrades, damage feedback, engine exhaust and dash echoes.
- Clearer hostile-shot preparation: sparse direction guides, source arrows, locked-target brackets, steady charge indicators and accurate guardian volley spokes.
- Faceted gray asteroids with craters and solid silhouettes, distinct from dim scenery and pointed hostile shots.
- Stationary segmented gold ion emitters with a damage-radius boundary, steady charge and a brief contained electrical discharge. Reduced effects retain the same danger and timing information.
- A spherical colony planet with terrain, cloud bands, atmospheric shading and a soft night boundary; detailed broken orbital rails, damaged transports and restrained peripheral nebulae.
- Readable localized help, upgrades, full builds and run summaries; brighter menu/HUD text, larger story copy, dark instrument panels and a dash recharge meter.
- Bounded enemy health markers fix the long purple strips caused by very high-health enemies in stress scenes.

## Compatibility and validation scope

Combat damage, timing, hitboxes, progression and the existing save format are unchanged. English, German, Polish, Spanish, Brazilian Portuguese, Japanese, Simplified Chinese and French remain supported; translations still await native-speaker review.

The presentation uses original code-generated graphics and existing approved assets. Planet, hull and rock textures are cached; each backdrop releases its temporary nebula texture on destruction. No external asset or dependency was added.

The release is exercised by unit tests, browser gameplay/localization/journey checks and full/reduced desktop/touch stress scenes. Headless captures use software rendering and do not certify real GPU/phone performance or a final sound-mix review.

The public artifact includes `release.json` identifying the exact committed private-source revision. Private source, source maps, local captures, telemetry and quarantined assets are excluded from deployment.
