# macOS Installation Guide

## Available Installation Methods

### Homebrew
- Install: `brew install gh`
- Upgrade: `brew upgrade gh`

### MacPorts
- Install: `sudo port install gh`
- Upgrade: `sudo port selfupdate && sudo port upgrade gh`

### Conda
- Install: `conda install gh --channel conda-forge`
- Upgrade: `conda update gh --channel conda-forge`

### Spack
- Install: `spack install gh`
- Upgrade: `spack uninstall gh && spack install gh`

### Webi
- Install: `curl -sS https://webi.sh/gh | sh`
- Upgrade: `webi gh@stable`

### Flox
- Install: `flox install gh`
- Upgrade: `flox upgrade toplevel`

### Direct Download
You can download the macOS installer (.pkg) from the releases page.

**Note:** As of May 29th, Mac OS installer .pkg files are currently unsigned.