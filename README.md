# Web Component

Mock web application component for CloudBees Unify RO adoption journey demo.

## Overview
This is a simplified component that simulates a web application deployment without actual application infrastructure.

## Deployment
```bash
./deploy.sh
```

## Environment Variables
- `VERSION`: Component version (default: 1.0.0)
- `ENVIRONMENT`: Target environment (default: dev)

## Example
```bash
VERSION=2.0.1 ENVIRONMENT=prod ./deploy.sh
```
