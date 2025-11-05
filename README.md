# FireFoundry CLI

Official binary releases for the FireFoundry CLI - a Rust-based tool for scaffolding and managing AI agent bundle projects.

## Installation

### macOS (Universal - Intel & Apple Silicon)

```bash
curl -L https://github.com/firebrandanalytics/ff-cli-releases/releases/latest/download/ff-cli-universal-apple-darwin.tar.gz | tar xz
sudo mv ff-cli /usr/local/bin/
```

### macOS (Homebrew)

```bash
brew tap firebrandanalytics/ff-cli
brew install ff-cli
```

**Note:** Homebrew formula coming soon.

### Windows

Download the latest `ff-cli-x86_64-pc-windows-msvc.zip` from [Releases](https://github.com/firebrandanalytics/ff-cli-releases/releases/latest), extract, and add to your PATH.

### Linux (x86_64)

```bash
curl -L https://github.com/firebrandanalytics/ff-cli-releases/releases/latest/download/ff-cli-x86_64-unknown-linux-gnu.tar.gz | tar xz
sudo mv ff-cli /usr/local/bin/
```

## Verify Installation

```bash
ff-cli --version
ff-cli ops doctor  # Check prerequisites
```

## Documentation

For documentation and usage examples, visit [FireFoundry Documentation](https://github.com/firebrandanalytics/ff-public-docs/blob/main/docs/README.md).

## Support

- Report issues: [GitHub Issues](https://github.com/firebrandanalytics/ff-cli-releases/issues)
- Contact: support@firebrandanalytics.com

## License

© 2025 Firebrand Analytics, LLC. All rights reserved.

This software and its source code are the property of Firebrand Analytics, LLC.
Unauthorized copying, modification, distribution, or use of this software,
via any medium, is strictly prohibited.

This code is confidential and proprietary.

