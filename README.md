# One Dark Calm

A personal Obsidian theme blending One Dark Pro colors, a restrained Zed-inspired interface, and iA Writer Duo S typography sourced from Serenity.

## Features

- Charcoal panels, blue accents, and understated navigation.
- Embedded iA Writer Duo S in regular, italic, bold, and bold italic.
- Warm inline-code chips and distinct blue-grey code blocks.
- Clear table headers, subtle alternating rows, and comfortable cell padding.
- Top-level tables extend beyond the readable text column toward the edges of their own note pane. Extra-wide tables retain horizontal scrolling; paragraphs keep their readable width.
- Compact Properties on desktop: type, status, and tags stay visible. Hover the section or focus a field to reveal everything. Touch devices, printing, and sidebar property panels keep all fields visible.
- Grey off switches and blue on switches.

## Install manually

1. Download `theme.css` and `manifest.json` from the latest release.
2. Create `.obsidian/themes/One Dark Calm/` inside your vault and place both files there.
3. In Obsidian, open **Settings → Appearance → Themes** and select **One Dark Calm**.

Use a current Obsidian desktop installer. The manifest requires Obsidian 1.6.0 or later; wide tables additionally require a browser engine supporting CSS container queries. Older engines retain normal table widths. No plugins are required.

The theme supplies its own note font. If you have configured a custom text font in Obsidian, clear that override or choose **iA Writer Duo S**. JetBrains Mono and SF Pro are optional system fonts with fallbacks; they are not bundled. Font size remains your choice in Obsidian.

## Behavior and limitations

Wide tables apply to top-level Markdown tables in Reading view and Live Preview. Tables inside callouts, lists, and embedded notes keep their containing layout. A small gutter remains for scrolling and editing controls. This theme does not modify note content, force smooth scrolling, or install a heading navigation plugin.

Layout checks use browser fixtures representing Obsidian's table containers. Native Obsidian interaction and performance still need checking in your own vault, particularly when other plugins or snippets modify editor layout. No scrolling performance gain is claimed.

## Credits and licenses

- [One Dark Pro for Obsidian](https://github.com/w4t4r/obsidian-one-dark-pro), by Donghang: base theme, MIT.
- [One Dark Pro](https://github.com/Binaryify/OneDark-Pro): palette and syntax colors, MIT.
- [Serenity](https://github.com/Bluemoondragon07/Obsidian-Serenity): source of the bundled font assets; Serenity's editor layout is not included.
- [iA Fonts](https://github.com/iaolo/iA-Fonts), based on IBM Plex: embedded typography, SIL OFL 1.1. See `Font License.txt`.
- [Zed JetBrains theme](https://github.com/artemevsevev/zed-theme-jetbrains): visual inspiration; no Zed theme code is bundled.

Theme code is MIT licensed. Font assets retain their separate SIL OFL license. See `LICENSE` and `THIRD_PARTY_NOTICES.md`.
