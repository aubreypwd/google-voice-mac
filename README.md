# {APPNAME}

![](screenshot.png)

An (unofficial) native MacOS App for {APPNAME}.

# Install

Navigate over to the [releases](https://github.com/aubreypwd/{app-slug}/releases) and download the latest version, or install via:

## Homebrew Cask

```bash
brew tap aubreypwd/homebrew-cask
brew update
brew install {app-slug}
```

# Development

1. Clone repo
2. `npm install`
3. `npm run build`

`npm run build` will built the application to `build/` and  `npm run dist` to generate a `.dmg` in `dist/` for distribution and installation.
