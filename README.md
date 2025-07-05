# ddev-deployer

A DDEV add-on to expose Deployer’s `dep` command inside your project’s web container.

## Installation

```bash
cd your-project
ddev get studioraz/ddev-deployer
ddev start
```

Once DDEV has restarted, you can run:

```bash
ddev dep
ddev dep deploy staging
```

## Uninstallation

```bash
ddev add-on remove ddev-deployer
```

This will remove the `dep` wrapper script. The `vendor/bin/dep` binary is left intact (it’s part of your project’s dependencies).
# ddev-deployer
