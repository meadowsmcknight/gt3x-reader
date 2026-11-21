# gt3x browser reader

A free, browser-only reader for ActiGraph `.gt3x` files. It exports the data as CSV, plus a JSON coverage summary.

**Open it here:** https://meadowsmcknight.github.io/gt3x-reader/

## Your data stays on your device

The reader runs entirely in your web browser. Files are read on your own computer or phone and are never uploaded anywhere. The page loads no outside scripts, ads or analytics, and its security policy blocks network requests.

## How to use it

1. Open the page and choose a `.gt3x` file.
2. Choose your export options and start the export.
3. Save the results:
   - **Desktop Chrome:** pick a folder, and the CSV parts and the JSON summary are saved straight into it.
   - **iPhone and other browsers without a folder picker:** a **Save** button appears for each CSV part and one for the JSON summary. Tap one, **wait for that file to finish saving**, then tap the next. To cancel an export partway through, reload the page.

Large recordings are split into numbered CSV parts (`..._part001.csv`, `..._part002.csv`, and so on), each up to 32 MiB, so they fit within the memory limits of phones and laptops. Open them in a spreadsheet program on a computer.

## Tested browsers

- Chrome on Linux (automated tests, including a synthetic 7-day, 100 Hz test recording)
- Chrome on iPhone (manual test: files load and the CSV parts and JSON summary save)

Safari and Firefox haven't been tested yet.

## Verify the page

The sha256 of the published `index.html` is:

```
5899373b4357c286c85a101dad4ce4f0a63fe0f91fd6741e453acdba0296cfdd
```

## How to cite

Meadows McKnight LLC (2026). *gt3x browser reader* [software]. https://github.com/meadowsmcknight/gt3x-reader

## License

Apache License 2.0. See [LICENSE](LICENSE). Small format-decoding fragments are ported from ActiGraph's MIT-licensed format documentation. See [NOTICE](NOTICE).

This project is not affiliated with or endorsed by ActiGraph.
