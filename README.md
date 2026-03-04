# IoT Part 3 - GitOps with Argo CD

This repository contains Kubernetes manifests for the IoT project Part 3.

## Structure
- `dev/` - Application manifests deployed to dev namespace

## Application
- **Image**: wil42/playground
- **Versions**: v1, v2
- **Port**: 8888

## Usage
Argo CD automatically syncs changes from this repository.
