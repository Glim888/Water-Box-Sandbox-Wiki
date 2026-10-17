# FAQ and Troubleshooting

[Wiki Home](../README.md) · [Elements and Gameplay Systems](../README.md#explore-the-wiki)

Start by pausing and checking the selected element, its configuration, and the connections around it. Change one setting at a time so you can see what affects the result.

## Boats and Liquids

**Why does my boat sink?** Check its cargo, hull gaps, material mass, and liquid particle weight. A boat that floats in one setup may sink with different liquid settings. See [Liquid Physics](../systems/liquid-physics.md#liquid-settings) and the [boat tutorial](building-tutorials.md#build-a-floating-boat).

**Why do liquids move while the simulation is paused?** Check **Freeze Liquid when Simulation is paused** in Liquid Settings.

**Why does the same design behave differently?** Compare gravity, particle weight, damping, cargo, and the surrounding scene. Start from the same saved Simulation when comparing designs.

## Connections and Machines

<img src="../assets/systems/building-and-connections/powered-wheel-joint.png" alt="The supporting body and wheel used to illustrate joint selection" width="260">

*The supporting body is selected first; the moving wheel is selected second.*

**Why can I not place a building part or joint?** Pause the simulation and read the game's message. Some tools require pause, while other actions require the simulation to run.

**Why does my wheel or motor not work?** Check that it uses a powered connection, that Element 1 and Element 2 are correct, and that speed and power are sufficient. Make sure the wheel has clearance and touches the ground. See [Building and Connections](../systems/building-and-connections.md).

**Why does a connection break?** Loads and impacts can exceed its resistance. Reduce the load or motor power, or adjust supported resistance settings.

**Why can I not move or zoom the camera?** Deselect the active placement or tool first. Some tools capture gestures or mouse input. See [Controls and Tools](controls-and-tools.md).

## Reactions and Ragdolls

**Why does a material burn or explode?** Heat sources, burning neighbors, or a detonation setting may trigger it. Oil burns; Petrol and Nitro explode. See [Temperature](../systems/temperature.md) and [Explosives](../elements/explosives.md).

**Why does a ragdoll stop walking?** Injuries, broken joints, missing parts, ground contact, cold, drowning, or chemical effects can change movement. See [Ragdolls and Chemicals](../systems/ragdolls-and-chemicals.md).

## Workshop and Saves

<img src="../assets/guides/save.png" alt="Save icon" width="48"> <img src="../assets/guides/workshop.png" alt="Online Workshop icon" width="64">

*Local saving and Workshop publishing are separate actions.*

**Where are my creations?** Local Objects are under **My Created Objects**; downloaded content is under **My Downloaded Creations**; published listings are under **My Creations**. Complete scenes use **Save/Load Simulations**.

**Why is a creation locked or priced in coins?** Check its coin price and Creative-Pack or element requirements. Download access does not necessarily unlock every element used in the creation.

**Why can I not browse, download, or publish?** Check the connection and read the game's message. Follow any version-update or wait instruction. For submission validation, check the title, description, price, and required agreement.

**Does saving publish my creation?** No. Use **Submit to Workshop** after saving and testing it. Editing a local build also does not automatically update listing details.

See [Saving and Loading](saving-and-loading.md) and [Online Workshop](online-workshop.md) for the full procedures.

## Other Guides

[Getting Started](getting-started.md) · [Controls and Tools](controls-and-tools.md) · [Saving and Loading](saving-and-loading.md) · [Online Workshop](online-workshop.md) · [Building Tutorials](building-tutorials.md)

