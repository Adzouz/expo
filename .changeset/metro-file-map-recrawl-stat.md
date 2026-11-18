---
'@expo/metro-file-map': patch
---

Fix a recrawl while watching missing changes to files, and retargeted symlinks, that the file map hadn't stat'd yet, e.g. under a directory moved into place on macOS.
