# OpenDSU Releases

This repository contains pre-built bundles for the OpenDSU SDK.

## Current Release

- Version: v2.0.15
- Build Date: $(date -u +"%Y-%m-%d %H:%M:%S UTC")
- Source: [OpenDSU/opendsu-sdk](https://github.com/OpenDSU/opendsu-sdk) commit 31c06b11ec73c898207715dd04720ea7c7d2f62b

## Usage

### Clone and run

```bash
git clone https://github.com/OpenDSU/opendsu-releases.git
cd opendsu-releases
npm run start
```

### Download specific version

Use git tags to checkout a specific version:

```bash
git clone https://github.com/OpenDSU/opendsu-releases.git
cd opendsu-releases
git checkout <tag_name>
npm run start
```

## Contents

This repository contains:
- Pre-built browserify bundles in `builds/output/`
- Launcher scripts in `psknode/bin/scripts/`
- ServerlessAPI module in `modules/apihub/serverlessAPI/` (required for fork execution)
- Minimal package.json with start scripts
- Configuration files (if applicable)

## Available Scripts

- `npm run start` - Launch the API Hub
- `npm run cloud-enclave` - Launch cloud enclave
- `npm run remote-enclave` - Launch remote enclave

## Source

These bundles are built from [OpenDSU/opendsu-sdk](https://github.com/OpenDSU/opendsu-sdk)
