# Building Defcoin Core

See the platform-specific build instructions in the `doc` folder:

- [Unix/Linux Build Notes](doc/build-unix.md)
- [Windows Build Notes](doc/build-windows.md)
- [macOS Build Notes](doc/build-osx.md)
- [FreeBSD Build Notes](doc/build-freebsd.md)
- [NetBSD Build Notes](doc/build-netbsd.md)
- [OpenBSD Build Notes](doc/build-openbsd.md)

## Quick Start (Linux)

```bash
./autogen.sh
./configure
make
make install  # optional
```

## Binary Names

After building, you will have:

- `defcoind` - Daemon
- `defcoin-qt` - GUI wallet
- `defcoin-cli` - Command-line RPC client
- `defcoin-tx` - Transaction utility
- `defcoin-wallet` - Wallet utility
