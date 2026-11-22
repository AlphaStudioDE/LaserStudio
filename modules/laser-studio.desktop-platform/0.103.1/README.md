# Laser Studio desktop services

The native Windows x64 companion for the Laser Studio editor in FreedomSlicer.

This package supplies the local service adapter, serial-port driver, image workers, VTracer WASM runtime, camera helpers and support media. A separate installation of standalone Laser Studio, Node.js or npm is not required. Electron is provided by FreedomSlicer.

## Installation order

Install this native package from the official Store and restart FreedomSlicer. Then install and enable the Laser Studio workspace. The editor discovers the named desktop service provider; it cannot obtain native permissions from its browser archive alone.

Native packages require official Administrator review and are unavailable in browser Lite. This package currently targets Windows x64; the standalone Linux edition is separate.

Installing or opening the module does not connect a laser, home it, move it or enable emission. USB operation requires the user's explicit action. Physical compatibility must be tested on the selected machine. Artisan remains experimental.

Cloudflare uses the user's own account and credentials. Optional external Ollama/ComfyUI and Python/ONNX providers keep their explicit user configuration requirements; they are not silently installed by this package.
