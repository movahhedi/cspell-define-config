# cspell-define-config

Provides a simple `defineConfig()` function to ease the creation of `cspell.config.js` files for spell checking in your projects.

## Installation

You can install `cspell-define-config` using npm:

```bash
npm install -D cspell-define-config
```

## Usage

Here's a basic example of how to use `defineConfig()`:

```javascript
import { defineConfig } from "cspell-define-config";

export default defineConfig({
	version: "0.2",
	ignorePaths: ["node_modules/**", "**/vendor/**", "temp/**", "dist/**", "build/**"],
	minWordLength: 4,
	allowCompoundWords: true,
	words: [],
	ignoreWords: [],
	import: [],
});
```

## License

This project is licensed under the MIT License.
