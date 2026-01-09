# Defcoin Core 2.0.0 Release Notes

## Major Upgrade

Defcoin Core 2.0.0 is a major upgrade that rebases Defcoin on Litecoin 0.21.x,
bringing modern features while maintaining full compatibility with the existing
Defcoin blockchain.

## What's New

### Modern Codebase
- Based on Litecoin 0.21.2 (which is based on Bitcoin Core 0.21)
- Improved performance and memory usage
- Better peer-to-peer networking
- Enhanced wallet functionality

### Security Improvements
- All security fixes from Bitcoin Core through 0.21
- Updated cryptographic libraries
- Improved input validation

### New Features
- Descriptor wallets (optional)
- SQLite wallet storage option
- Improved RPC interface
- Better fee estimation

### GUI Improvements
- Modern Qt-based interface
- New dark and light themes
- Improved transaction display
- Better error messages

## Upgrading

### From Defcoin Core 1.x

1. **Backup your wallet** before upgrading
2. Close Defcoin Core 1.x
3. Install Defcoin Core 2.0.0
4. Start the new version - it will reindex the blockchain automatically
5. Your existing wallet and addresses will work without changes

### Data Directory

Your data directory location remains unchanged:
- Windows: `%APPDATA%\Defcoin\`
- Linux: `~/.defcoin/`
- macOS: `~/Library/Application Support/Defcoin/`

## Consensus Changes

There are NO consensus changes in this release. Defcoin Core 2.0.0 will sync
with the existing Defcoin network without issues.

## Known Issues

- First startup after upgrade requires blockchain reindex
- Some RPC commands have changed parameters (see RPC documentation)

## Credits

Defcoin Core 2.0.0 is based on:
- Litecoin Core developers
- Bitcoin Core developers
- Original Defcoin developers (mspicer)
