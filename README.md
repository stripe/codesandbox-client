# Bundler

Fork of [codesandbox-client](https://github.com/codesandbox/codesandbox-client) to provide a pre-built package of the Sandpack bundler for self-hosting.

For more info, see: https://sandpack.codesandbox.io/docs/guides/hosting-the-bundler

## Overview

This project provides the bundler component of CodeSandbox as:

1. A **Docker image**: `ghcr.io/librechat-ai/codesandbox-client/bundler:latest`
2. A **downloadable ZIP file** available in [Releases](https://github.com/LibreChat-AI/codesandbox-client/releases)

Self-hosting the bundler gives you:
- ✅ **Privacy**: No dependency on external services
- ✅ **Reliability**: Not affected by outages or rate limits
- ✅ **Control**: Full control over your environment

## Quick Start

### Using Docker

```bash
docker pull ghcr.io/librechat-ai/codesandbox-client/bundler:latest
docker run -p 8080:80 ghcr.io/librechat-ai/codesandbox-client/bundler:latest
```

### Using Static Files

1. Download `bundler.zip` from the [Releases page](https://github.com/LibreChat-AI/codesandbox-client/releases)
2. Extract and serve with any web server (ensure CORS headers are enabled)

### Integration

TBD