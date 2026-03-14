# ORCRUX Desktop Linux v0.1.1

  This folder contains the Linux desktop release packages for ORCRUX.

  ## Download

  Choose the package that matches your Linux distribution:

  - `ORCRUX Desktop_0.1.1_amd64.deb` for Ubuntu / Debian
  - `ORCRUX Desktop-0.1.1-1.x86_64.rpm` for Fedora / RPM-based systems

  You can also verify file integrity with:
  - `SHA256SUMS`

  ## Install

  ### Ubuntu / Debian

  ```bash
  sudo dpkg -i "ORCRUX Desktop_0.1.1_amd64.deb"
  sudo apt-get install -f -y

  ### Fedora / RPM-based systems

  sudo rpm -i "ORCRUX Desktop-0.1.1-1.x86_64.rpm"

  ## Launch

  After installation, open ORCRUX Desktop from your applications menu.

  The desktop client provides:

  - local node control
  - miner control
  - wallet connection
  - synchronization status
  - local height, chain height, and lag visibility

  ## Notes

  - A lag of 0 to 1 block can be normal while the chain is advancing
  - The desktop uses the best available GPU backend depending on the machine and environment:
      - CUDA
      - ROCm
      - DirectML

  ## Verify checksums

  sha256sum -c SHA256SUMS
