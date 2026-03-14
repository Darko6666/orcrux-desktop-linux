# ORCRUX Desktop Linux

  Official Linux desktop builds for the ORCRUX network.

  This repository contains packaged Linux releases of the ORCRUX desktop client, including node, miner, wallet
  connectivity, and synchronization tools for the ORCRUX blockchain.

  ## Included formats

  - AppImage
  - Debian package (`.deb`)
  - RPM package (`.rpm`)

  ## Current release

  Latest packaged assets are available in:

  `release/v0.1.1/`

  Included files:
  - `ORCRUX Desktop_0.1.1_amd64.deb`
  - `ORCRUX Desktop-0.1.1-1.x86_64.rpm`
  - `SHA256SUMS`

  ## Features

  - Local node and miner control
  - Wallet connection
  - Chain synchronization status
  - Local height, chain height, and lag visibility
  - Available and locked balance display
  - Workload participation for the ORCRUX network

  ## Notes

  The desktop uses the best available GPU backend depending on the machine and environment, including:
  - CUDA
  - ROCm
  - DirectML

  A lag of 0 to 1 block can be normal while the chain is actively advancing.

  ## Project

  Main ORCRUX project and infrastructure are maintained separately.
  This repository is dedicated to Linux desktop release distribution.



# ORCRUX Desktop Windows

Official Windows desktop builds for the ORCRUX network.

This repository contains packaged Windows releases of the ORCRUX desktop client, including node, miner, wallet connectivity, synchronization tools, and installer packages for the ORCRUX blockchain.

## Included formats

- Windows installer (`setup.exe`)
- Windows Installer package (`.msi`)
- Portable executable (`.exe`)

## Current release

Latest packaged assets are available in:

`release/v0.1.1/`

Included files:

- `ORCRUX Desktop_0.1.1_x64-setup.exe`
- `ORCRUX Desktop_0.1.1_x64_en-US.msi`
- `orcrux-desktop.exe`
- `SHA256SUMS`

## Features

- Local node and miner control
- Wallet connection
- Chain synchronization status
- Local height, chain height, and lag visibility
- Available and locked balance display
- Workload participation for the ORCRUX network
- Windows desktop installer with shortcut creation
- Optional runtime dependency installation for Python, Torch, and DirectML

## Notes

The desktop uses the best available GPU backend depending on the machine and environment, including:

- CUDA
- ROCm
- DirectML

A lag of 0 to 1 block can be normal while the chain is actively advancing.

On Windows, the recommended package is the `setup.exe` installer.

The installer can also help prepare required runtime dependencies used by the local node and GPU workload stack.
