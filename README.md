﻿# Rollercoaster Simulation API v1.0
![Title](Pictures/titleImage.png)

A toolset for creating and operating realistic rollercoasters in Unity. Includes a full integration into the Unity Editor.

### What this is not
- A replacement for more professional software, like No limits 2. The current physical simulation is very simple, but works for games and other applications.
- It not a standalone coaster editor for games, but it includes one for the Unity Editor to be simulated in standalone mode.
- Apart from example assets, there are no tracks or cars being delivered (for the moment). This is up to you to model your custom cars, tracks and scenery.

### Wiki
The Wiki contains a lot of information about how the system works and how to build a simple rollercoaster.

### Features
- Spline based track editor
- Custom track and car models (Procedural track generation)
- Block sections for multi train operation
- On track event triggering
- Full integration into Unity (Terrain system, programming, HDRP / URP, ...)
- Superior graphics capabilities compared to other coaster simulators (Baked Lighting, GI, Ray Tracing (HDRP), ...)

### Future work
- Improved physics
- Different spline types (NURBS, ...)
- Lightmap integration for track pieces (For now use light probes or [Probe Volumes](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@14.0/manual/probevolumes.html))
- Support generation
- ...
