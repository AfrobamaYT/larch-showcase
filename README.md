# Larch rice showcase

Short preview films of the Hyprland setups ("rices") in Larch's rice catalogue. Larch's
rice manager shows them so you can see what a rice does before you switch to it.

## How the films were made

- Each rice was fetched from its author's repository at a reviewed commit and applied in a
  disposable virtual machine running Larch, then driven with the rice's own key bindings.
- Every wallpaper, lock-screen picture, avatar and similar picture of the rice was replaced by
  Larch's own wallpaper, recoloured to the rice's palette. What you see is the rice's own
  interface: its bars, launchers, menus, terminals and animations.
- 60 frames per second, 1280×800, H.264, mostly 10 to 25 seconds, no sound.

## Files

The films and their posters are attached to the
[releases](https://github.com/AfrobamaYT/larch-showcase/releases), not stored in git.
`index.json` lists every film with its rice, author, source repository and commit, size,
duration and SHA-256:

```
https://github.com/AfrobamaYT/larch-showcase/releases/download/<tag>/<rice>.mp4
https://github.com/AfrobamaYT/larch-showcase/releases/download/<tag>/<rice>.webp
```

## Credits and removal

Each rice's design belongs to its author; `index.json` names them and links their repository.
If you made one of these rices and would like its film changed or removed, please
[open an issue](https://github.com/AfrobamaYT/larch-showcase/issues).
