# Andúril 2 UI Diagrams
User Interface diagrams for Andúril 2 - an advanced flashlight UI developed by [ToyKeeper](https://github.com/ToyKeeper)

## Simple UI
![Simple UI](https://github.com/containerfan/anduril2-diagrams/releases/latest/download/Anduril2_Simple.png "Simple UI")

## Advanced UI
![Advanced UI](https://github.com/containerfan/anduril2-diagrams/releases/latest/download/Anduril2_Advanced.png "Advanced UI")

## Download
Check the [Releases](https://github.com/containerfan/anduril2-diagrams/releases) for the files in the following formats:
- SVG - "Scalable Vector Graphics" files that are the source files that may be edited in apps like Inkscape or viewed in standard web browsers.
- PNG - "Portable Network Graphic" files that may be viewed in most image viewers (similar to GIF and JPG files).
- PDF - "Portable Document Format" files that may be viewed in Adobe Acrobat and other PDF readers/editors. These files are great for printing.
- source (zip & tar.gz) - Compressed files that contain the SVG files.

## Usage
ToyKeeper's Andúril 2 releases use a date format, e.g., 2023-12-03. There will always be one or more diagram releases corresponding with each Andúril 2 release. The diagram releases use a simple numerical format, e.g., 01, and are incremented as fixes and enhancements are applied. The latest diagram release for each Andúril 2 release will be posted [here](https://github.com/containerfan/anduril2-diagrams/releases), e.g., 2023-12-03.01. You should leverage the diagrams that match the release of Andúril 2 on your light(s) (from the 2023-12-03 release on). Please note that these diagrams are *not* manufacturer and/or model specific, but rather follow the "vanilla" Andúril 2 releases with no modifications (strictly following the [Andúril 2 text manual](https://github.com/ToyKeeper/anduril/blob/trunk/docs/anduril-manual.md)). The source SVG files are provided so that users and manufacturers can make their own modifications per their configurations and preferences directly in Inkscape. I *may* make vendor-specific diagrams in the future; however, this is something that I do in my (very little) free time as a hobby.

## Channel Modes
Multi-channel lights in particular may feature many channel modes. For example, this is the typical sequence of channel modes for Emisar and Noctigon dual-channel lights:
1. Channel 1 only
2. Channel 2 only
3. Both channels, tied together, max "200%" power (50/50)
4. Both channels, manual blend, max "100%" power (Tint Ramp)
5. Both channels, auto blend, reversible (Autotint)
6. (6+) RGB Aux LED Channels

Source: [hwdef.h for emisar-2ch](https://github.com/ToyKeeper/anduril/blob/cbfc1a13a9c9a8c08c054658ed26d2350383d209/hw/hank/emisar-2ch/hwdef.h#L39). For other multi-channel lights, you may want to check the corresponding hwdef.h file. You might also modify the diagrams to include a specific sequence of channel modes.

## Background
This was 100% inspired by [Lux-Perpetua’s Andúril 2 UI diagram on BLF](https://budgetlightforum.com/node/76941). In fact, Lux’s diagram is so good, that I would have been happy to just use it except for one thing: the source isn’t published, so you can’t modify it. I also wanted to be able to keep it up to date with [ToyKeeper’s code](https://github.com/ToyKeeper/anduril), so I created my own. I originally developed my diagrams in Microsoft Visio, and released the source file for folks to use and modify as they saw fit. However, folks were quick to point out that Visio is not open source, and not everyone has access to it. After some nudging by a colleague, I converted the diagrams to [Inkscape](https://inkscape.org/) which is multi-platform and open source.

## Credits
- The diagrams use the [Carlito font](https://fonts.google.com/specimen/Carlito) which is released under the [Open Font License](https://openfontlicense.org/). Besides downloading this font directly, the [fonts-crosextra-carlito](https://packages.ubuntu.com/fonts-crosextra-carlito) package is available for Ubuntu, for example. It is necessary to have this font installed for the source SVG files to be displayed properly; however, this is not necessary for the exported PNG and PDF files.
- *Some* of the icons used in the diagrams came from [SVG Repo](https://www.svgrepo.com/) under [various licenses](https://www.svgrepo.com/page/licensing/).
- The quality of the diagrams is *significantly* improved by the proofreading and creative input of [dirtydancing](https://github.com/dirtydancing).

## Contributing
- Open an [issue](https://github.com/containerfan/anduril2-diagrams/issues) if you have a question or feedback.
- Send me a message on [Budget Light Forum (BLF)](https://budgetlightforum.com/u/containerfan) or [Reddit](https://www.reddit.com/user/containerfan).
- If you appreciate my work, consider contributing to ToyKeeper's [Patreon](https://patreon.com/ToyKeeper). These diagrams wouldn't exist without ToyKeeper's continued dedication to making the best, most advanced flashlight user interface in existence.
