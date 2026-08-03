# HoleFoodsAdaptiveAnalyticsSample

This repo contains two versions of the HoleFoods sample for AtScale:

| Version | Location | Format | When to use |
|---|---|---|---|
| **Container (current)** | Root of this repo | AtScale YAML (container-based) | New AtScale container deployments |
| **Legacy installer** | [`legacy-installer-sample/`](legacy-installer-sample/) | AtScale XML + sample bundle | Older AtScale "Use a sample" installer workflow with InterSystems IRIS |

---

## Container Version (Current)

The YAML files at the root of this repo define the HoleFoods cube using the current AtScale container-based project format.

### Structure
```
catalog.yml          - Catalog definition
connections/         - Database connection definitions
datasets/            - Source table definitions
dimensions/          - Dimension definitions
metrics/             - Metric definitions
models/              - Model definitions
```

> **Status:** Work in progress.

---

## Legacy Installer Demo

See [`legacy-installer-sample/`](legacy-installer-sample/) for the original AtScale sample bundle approach, which imports HoleFoods data into InterSystems IRIS using the AtScale "Use a sample" installer.
