# PixelWall-Engine

A game engine includes isometric graphic by glfw library, level-by-level gameplay, simple physics for rect-shaped objects, point-and-click characters' manipulations and two editor apps for objects and structures.

![Project structure](demo%20references/Component%20diagram.png "Project structure")
![Use-case diagram](demo%20references/Usecase%20diagram.png "Use-case diagram")

Some classes diagrams:

![Classes diagram](demo%20references/classes.png "Classes diagram")

I prefer GLFW as graphic library and [FMOD-Audio-Engine](https://github.com/rosshoyt/FMOD-Audio-Engine) because of simple implementation and due to the amount of reference material.

You can track this with [Kanban board](https://evstropov.kaiten.ru/space/538381/boards).

### Content: 

1. Developing progress;
2. Features done;
3. Versioning rules.

## Developing progress

- [ ] Graphic's implementation with GLFW
- [ ] Objects' classes
- [ ] Physics
- [ ] Sprites and animation support
- [ ] Level class
- [ ] Structures constructor GUI app
- [ ] Objects and items editor GUI app

## Features done:

## Demo references:

![Structures constructor](demo%20references/11_02_редактор_структур.png "Structures constructor")
![Objects editor](demo%20references/11_02_редактор_объектов.png "Objects editor")
![Engine test demo](demo%20references/11_02_демо_движка.png "Engine test")

## Info for developers/contributors:
- Release versions contained in *master*;
- Stable versions merging to *stable*;
- Unstable versions/in development branching from *stable*;
- Only pull requests to *stable* are considered;
- Versions are named in *x.xx.xx* format
  (global release - stable version - fixes/patches);
- Dev's discord contact: nekichnet.
