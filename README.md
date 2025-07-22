
<p align="center">
  <div><img src="https://dirkwhoffmann.github.io/vAmiga/images/va-net-banner-1.png"></div>
</p>

# About 

vAmiga.net is a web-based port of [vAmiga](https://dirkwhoffmann.github.io/vAmiga/), built with WebAssembly (WASM), SvelteKit, TypeScript, and Tailwind CSS. It emulates a Commodore Amiga 500, 1000, or 2000 — directly in your browser.

This repository contains version 1.0 of vAmiga.net. It will be removed once version 2.0 reaches a stable release.

# Deployment

[https://vamiganet.github.io](https://vamiganetV1.github.io)

# Installation istructions

```bash
# Clone the project
git clone https://github.com/dirkwhoffmann/vAmigaNet.git

# Install components
cd vAmigaNet 
npm install

# Setup a build directory
mkdir wasm
emcmake cmake -S cpp -B build

# Build the WASM part
cd build
make -j

# Option 1: Run a local build
cd ..
npm run dev

# Option 2: Deploy
npm run build
```
