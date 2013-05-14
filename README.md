# install-mt-plugins

This tool easily installs Movable Type Plugins. This script makes symbolic links of plugins.

## Usage

Example tree

    ├── mt <= Movable Type Directories
    │   ├── mt-static
    │   │      └── plugins
    │   └── plugins
    │   └── ...
    └── mt-plugins <= Your plugins Directories
        ├── install-mt-plugins <= script
        ├── mt-static
        │   └── plugins
        │       ├── MTAppjQuery
        │       └── ...
        └── plugins
            ├── MTAppjQuery
            └── …

Login your server

    cd /path/to/your/mt-plugins
    chmod +x install-mt-plugins
    ./install-mt-plugins /path/to/your/mt

---
bit part