# Tatara mapper — heap allocator visualisation

Z80 / MSX memory mapper allocator (`alloc.as`) plus a browser visualisation of a
test run: allocate 8 MB, free 25%, allocate 8 MB more.

**Live simulation:** https://javilm.github.io/tatara-mapper/memmap3.html

| File | What it is |
|------|-----------|
| `alloc.as` | The allocator |
| `alloc.inc` | Public interface / equates |
| `heaptst2.as` | Test program driving the allocator |
| `make2.bat` | Build script |
| `log.txt` | Raw run log the visualisation was generated from |
| `memmap3.html` | Self-contained visualisation (no external assets) |
