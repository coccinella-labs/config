<p align="center">
  <img src="https://raw.githubusercontent.com/Coccinella-Labs/config/main/.github/assets/thumbnail.png" alt="config" width="100%">
</p>

# gh-config

GitHub CLI extension to get configuration values from coccinella-labs/config repository.

## Purpose

Centralized configuration management for all coccinella-labs CLI extensions.

## Installation

```bash
gh extension install coccinella-labs/config
```

## Usage

### Get a config value
```bash
gh config warningsEnabled
```

### List all config keys
```bash
gh config --list
```

## Configuration

The config is stored in [coccinella-labs/config](https://github.com/coccinella-labs/config) repository.

```json
{
  "warningsEnabled": true,
  "pinRepoEnabled": false,
  "defaultOrg": "coccinella-labs",
  "features": {
    "autoPin": false,
    "autoLicense": true,
    "autoReadme": true
  }
}
```