# Liquid Physics

[Wiki Home](../README.md) · [Elements](../README.md#explore-the-wiki)

Liquids are simulated as interacting particles. They flow around obstacles, collect in containers, and exchange forces with solid objects. Particle-based motion creates splashes, currents, and waves rather than a fixed water surface.

## Liquid Types

<img src="../assets/systems/liquid-physics/liquid-shapes.png" alt="Liquid particles drawn in different shapes above a basin" width="320">

*Liquid Powers draw particles into the scene; after placement, ordinary liquids flow and collect under gravity. See [Liquid Powers](../elements/powers.md#liquid-powers).*

[Water](../elements/powers.md#water) is useful for floating and cooling experiments. [Lava](../elements/powers.md#lava) supplies heat, while Oil, Petrol, and Nitro have different ignition effects. [Colored Liquid](../elements/powers.md#colored-liquid) mixes colors. Elastic Water and Elastic Lava connect particles into soft, jelly-like shapes. See [Liquid Powers](../elements/powers.md#liquid-powers) for every type and [Temperature](temperature.md) for reactions.

## Liquid Settings

| Setting | Effect |
| --- | --- |
| Liquid Particle Weight | Low values make objects sink more easily; high values make floating easier. |
| Liquid Particle Damping | Higher values make liquid motion settle faster. |
| Freeze Liquid when Simulation is paused | Controls whether liquid stops while the simulation is paused. |
| Liquid Particle Count | Shows the number of liquid particles in the scene. |
| Realistic Liquid Particles (Ultra) | An additional liquid option available where supported and unlocked. |
| Use the phone's gyroscope for gravity | Uses device orientation to control gravity on supported devices. |
| Clear all liquids | Removes the scene's liquid particles. |

Keep weight and damping unchanged when comparing designs: changing the settings can change whether the same ship floats.

## Buoyancy, Waves and Sinking

Floating depends on a construction's mass, shape, and interaction with the liquid. Add cargo gradually and observe how far the hull sinks. Uneven loading can tilt a boat and let water enter.

Moving bodies displace liquid and create waves. Obstacles redirect flow into currents. Spawners, moving walls, and expanders can sustain water movement; [Tsunami](../elements/powers.md#tsunami) creates a larger disturbance. Construction and joint strength also affect whether a ship survives rough water.

## Color Mixing and Liquid Transport

<img src="../assets/systems/liquid-physics/colored-liquids.png" alt="Red, yellow and blue liquid shapes collecting in a basin" width="320">

*Colored particles can be combined in the same scene and processed with color tools. See [Colored Liquid](../elements/powers.md#colored-liquid).*

Different colored particles can mix. The [Liquid Painter](../elements/powers.md#liquid-painter) recolors existing liquid; a [Liquid Color Changer](../elements/functional-elements.md#liquid-color-changer) recolors liquid on contact. Color filters separate particles by their selected color. These tools belong to [Machines and Automation](machines-and-automation.md).

## Try This

Build a wooden boat in a basin, add cargo, and compare still water with a wave. Repeat from the same starting scene with a different particle weight to see how liquid settings affect buoyancy.

## Related Guides

[Getting Started](../guides/getting-started.md) · [Building Tutorials](../guides/building-tutorials.md) · [FAQ and Troubleshooting](../guides/faq-and-troubleshooting.md)

## Other Gameplay Systems

[Temperature](temperature.md) · [Building and Connections](building-and-connections.md) · [Destruction, Explosions and Weapons](destruction-explosions-and-weapons.md) · [Physics and Forces](physics-and-forces.md) · [Machines and Automation](machines-and-automation.md) · [Ragdolls and Chemicals](ragdolls-and-chemicals.md)

