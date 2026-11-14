> **Moved to uno-lab.** This project now lives in the `Aware/` folder of [noknowscode/uno-lab](https://github.com/noknowscode/uno-lab/tree/main/Aware) (private). This repository is archived and kept for its history.

# Aware

A spatial app that recognises the rooms you have been in: rooms get a spatial fingerprint, and each room has explore, measure, memories, objects, motion and privacy views. Room capture uses ARCore on Android.

## What's inside

- **Screens:** Spatial Room.

## Built with

- Uno Platform single project, `Uno.Sdk` 6.6.42 (pinned in `global.json`).
- Targets: Android, iOS, WebAssembly, Desktop (net10.0).
- Material theme, Hosting and dependency injection, Uno Toolkit, MVVM (CommunityToolkit), Kiota HTTP client, localization, Navigation extensions, SkiaSharp, Skia renderer.

## Run it

You need the .NET 10 SDK. Run `uno-check` first on a fresh machine.

```bash
dotnet run --project Aware/Aware.csproj -f net10.0-desktop
```

## Design docs

- [`SPEC.md`](SPEC.md)

## License

MIT. See [LICENSE](LICENSE).
