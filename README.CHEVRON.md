# oniguruma (Chevron)

**Required exports:** `OnigRegExp`, `OnigScanner`, `OnigString`.

- Chevron TextMate mode: `const { OnigRegExp } = require('oniguruma')`
- first-mate (npm) also requires `OnigScanner` from this package.

Keep `findNextMatch` / `findNextMatchSync` on the scanner prototype.
Native addon is `build/Release/onig_scanner.node`.
