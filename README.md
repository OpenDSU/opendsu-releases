# OpenDSU Releases

This repository contains pre-built bundles for the OpenDSU SDK.

## Latest Release

The `latest/` directory contains the most recent build of the OpenDSU SDK bundles.

- Version: 1.0.1
- Build Date: $(date -u +"%Y-%m-%d %H:%M:%S UTC")

## Usage

### Using the latest bundles directly

```bash
git clone https://github.com/OpenDSU/opendsu-releases.git
cd opendsu-releases/latest
npm run start
```

### Downloading a specific release

Archives for each release are available in the `releases/` directory.

## Contents

Each release contains:
- Pre-built browserify bundles in `builds/output/`
- Launcher scripts in `psknode/bin/scripts/`
- Minimal package.json with start scripts
- Configuration files (if applicable)

## Available Scripts

- `npm run start` - Launch the API Hub
- `npm run cloud-enclave` - Launch cloud enclave
- `npm run remote-enclave` - Launch remote enclave

## Source

These bundles are built from [OpenDSU/opendsu-sdk](https://github.com/OpenDSU/opendsu-sdk)
