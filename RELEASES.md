## Releases

# Unreleased

- Update to latest network protocol. Implement message handling for
  ClearBlockFilter, GetFullBlock, and GetBlockRange. The GetBlockHeader API has
  been removed.

### Breaking changes

- The network constants were updated during the update to support the latest
  network protocol.

# Version 0.1.0 (2019-11-14)

This marks the first release of the project. The essential features that users
need to create applications such as key generation, script building, and block
synchronization are implemented.

### Known limitations

The script engine isn't implemented so transactions and full block validation
cannot be performed. However, block headers can be validated.