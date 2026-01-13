# FPDev Index

Official index repository for [fpdev](https://github.com/dtamade/fpdev) - the FreePascal Development Environment Manager.

## Overview

This repository serves as the central index for all fpdev resources. It contains metadata pointing to sub-repositories that host the actual binary packages.

## Sub-Repositories

| Repository | Description |
|------------|-------------|
| [fpdev-bootstrap](https://github.com/dtamade/fpdev-bootstrap) | Bootstrap compilers for building FPC from source |
| [fpdev-fpc](https://github.com/dtamade/fpdev-fpc) | Pre-built FPC binary releases |
| [fpdev-lazarus](https://github.com/dtamade/fpdev-lazarus) | Pre-built Lazarus IDE releases |
| [fpdev-cross](https://github.com/dtamade/fpdev-cross) | Cross-compilation toolchains |

## Channels

- **stable**: Tested and verified version combinations
- **edge**: Latest versions, may have compatibility issues

## Mirrors

- **GitHub**: https://github.com/dtamade/fpdev-index
- **Gitee**: https://gitee.com/dtamade/fpdev-index (China)

## Usage

fpdev automatically uses this index to discover and download resources:

```bash
# Install FPC (uses stable channel by default)
fpdev fpc install 3.2.2

# Use edge channel
fpdev fpc install main --channel edge
```

## Configuration

Users can configure mirror preferences:

```bash
# China users (use Gitee)
fpdev config set mirror gitee

# Global users (use GitHub)
fpdev config set mirror github
```

## License

MIT
