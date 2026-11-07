# Roblox 2009 Web — Project Context

## 1. Project Mission

Create a genuinely playable recreation of the Roblox 2009 client that runs directly in a web browser.

This is a real game-engine project, not just a visual mockup.

## 2. Main Features

- Authentic 2009 Roblox interface.
- Classic R6 avatars.
- Character movement and animations.
- Third-person camera.
- Classic brick-based building system.
- Physics and collisions.
- Terrain and large maps.
- Classic sounds and visual effects.
- Luau scripting, if technically feasible.
- Multiplayer as a future objective.
- Good performance, including on Chromebooks.

## 3. Repository

GitHub:
[https://github.com/nesus863-beep/Roblox-2009-Web](https://github.com/nesus863-beep/Roblox-2009-Web)

Development environment: GitHub Codespaces.

Workspace path:
`/workspaces/Roblox-2009-Web`

## 4. Development Environment

Known installed tools:

- Git 2.56.0
- G++ 13.3.0
- CMake 3.28.3
- Python 3.14.2

Emscripten: Not installed yet.

Main computer: Chromebook.

Budget: Zero. Prefer free and open-source tools.

## 5. Engine Research

### RNR

Repository:
[https://github.com/lrre-foss/rnr](https://github.com/lrre-foss/rnr)

A shallow clone was previously downloaded to:

`/tmp/rnr-review`

Known technologies include:

- C++
- OGRE
- Bullet Physics
- Qt6
- Boost
- Luau

RNR is an older project targeting Roblox compatibility up to April 2008.

Its suitability for a browser-based 2009 recreation has NOT yet been established.

Its licenses must be checked before reusing any code.

### BlxEngine

Potential browser-engine candidate.

Its actual source repository, license, current state and browser compatibility still need independent verification.

Do not assume it is suitable until verified.

## 6. AI Development Team

- ChatGPT: Project coordination, integration and planning.
- Gemini: Research and source verification.
- Claude: C++ architecture and engineering.
- Grok: Independent review and performance analysis.

All AI members should share their findings through this document and project discussions.

Do not let different AIs overwrite the same project files independently.

## 7. Important Rules

1. No paid services or tools.
2. No fake playable demonstrations.
3. Prioritize actual functionality.
4. Verify external repositories and licenses.
5. Avoid unnecessary rewrites.
6. Optimize for browser performance.
7. Keep instructions beginner-friendly.
8. Never claim code has been tested when it has not.
9. Record important architectural decisions.
10. Update this document when the project changes.

## 8. Current Development Status

- [x] GitHub repository created.
- [x] GitHub Codespaces opened.
- [x] Development tools checked.
- [x] RNR downloaded for research.
- [ ] Choose the engine architecture.
- [ ] Verify browser-compatible rendering options.
- [ ] Install and configure Emscripten if needed.
- [ ] Create the first browser-rendered 3D scene.
- [ ] Implement character movement.
- [ ] Implement physics and building.
- [ ] Develop the 2009-style interface.
- [ ] Add historical assets and sounds where legally usable.
- [ ] Optimize large maps.
- [ ] Investigate multiplayer.

## 9. Immediate Next Objective

Do not start implementing random features.

First, investigate the most realistic architecture for a playable Roblox 2009 browser client.

Compare existing open-source engines, browser rendering technologies, physics systems and scripting options.

Make decisions based on verified technical evidence.
