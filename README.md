[README.md](https://github.com/user-attachments/files/30123931/README.md)
<div align="center">

# ox_lib — Syntax Edition

A reskin of [ox_lib](https://github.com/overextended/ox_lib) with a cyberpunk look,
and a menu that lets **every player set up their own HUD**.

![The /oxcolour editor](./.github/images/editor.png)

</div>

> **This is a modified fork of [overextended/ox_lib](https://github.com/overextended/ox_lib).**
> Based on upstream **v3.39.0**, modified July 2026 by [Limma98](https://github.com/Limma98).
> It isn't affiliated with or endorsed by the ox_lib maintainers — please don't raise
> issues with them about anything in this fork.
>
> Everything else works exactly like ox_lib, so any resource that depends on it keeps
> working. The changes are visual, plus the player settings menu below.

## Make it yours — `/oxcolour`

Type `/oxcolour` in game to open the interface editor:

- **Move things.** Drag your notifications, progress bar and interaction prompt anywhere
  on screen. They snap neatly to the top, bottom, left or right if you want them tidy.
- **Resize things.** Each one has its own size slider, 60% to 160%.
- **Pick your colour.** Nine presets, or drag the slider for any shade you like. The whole
  interface recolours instantly.
- **Choose your sounds.** Silence, one sound for everything, or a different sound for each
  — with a preview button and a volume slider.
- **Try before you save.** Hit *Test* on any item to see and hear the real thing right
  where you've placed it.

Press **ENTER** to save, **ESC** to cancel..

## Radial menu

<div align="center">

![The radial menu](./.github/images/radial.png)

</div>

Hold **F1** to open it, let go to close. Press again and you're back at the main menu — no
clicking "back" through submenus. Up to 9 options per page, each with its own icon.

## Install

Drop it in your resources folder and start it exactly like ox_lib — it must start **before**
any resource that uses it. The built interface is already included, so there's nothing to
compile.

If you already run ox_lib, replace it. Resources that depend on ox_lib won't notice the
difference.

## Building the UI

Only needed if you change something in `web/`:

```bash
cd web
pnpm install
pnpm build
```

## Credits

ox_lib is created and maintained by [Linden](https://github.com/thelindat),
[Luke](https://github.com/LukeWasTakenn) and contributors — all of the underlying library is
their work.

Licensed under [LGPL-3.0-or-later](./LICENSE), same as upstream. See [NOTICE.md](./NOTICE.md)
for legal notices.
