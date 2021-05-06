# Escudo  
Secure. Private. Untraceable.

Copyright (c) 2014-2021 The JupiterKeystone Project.
Portions Copyright (c) 2012-2013 The Cryptonote developers.


## Coverage
| Type      | Status |
|-----------|--------|
| Coverity  | [![Coverity Status](https://scan.coverity.com/projects/9657/badge.svg)]()
| OSS Fuzz  | [![Fuzzing Status](https://oss-fuzz-build-logs.storage.googleapis.com/badges/monero.svg)]()
| Coveralls | [![Coveralls Status](https://coveralls.io/repos/github/monero-project/monero/badge.svg?branch=master)]()
| License   | [![License](https://img.shields.io/badge/license-BSD3-blue.svg)]()

## Development resources
- Web: [google.com](https://google.com)
- Forum: [google.com](https://google.com)
- Mail: [dev@google.com](mailto:dev@google.com)
- GitHub: [https://github.com/JupiterKeystone/Escudo](https://github.com/JupiterKeystone/Escudo)
- IRC: [#Escudo](https://webchat.freenode.net/)

## Supporting the project
Escudo is a 100% community-sponsored endeavor. If you want to join our efforts, the easiest thing you can do is support the project financially. 
Escudo, Monero and Bitcoin donations can be made to:

**Privacy:** Monero uses a cryptographically sound system to allow you to send and receive funds without your transactions being easily revealed on the blockchain (the ledger of transactions that everyone has). This ensures that your purchases, receipts, and all transfers remain private by default.

**Security:** Using the power of a distributed peer-to-peer consensus network, every transaction on the network is cryptographically secured. Individual wallets have a 25-word mnemonic seed that is only displayed once and can be written down to backup the wallet. Wallet files should be encrypted with a strong passphrase to ensure they are useless if ever stolen.

**Untraceability:** By taking advantage of ring signatures, a special property of a certain type of cryptography, Monero is able to ensure that transactions are not only untraceable but have an optional measure of ambiguity that ensures that transactions cannot easily be tied back to an individual user or computer.

**Decentralization:** The utility of Monero depends on its decentralised peer-to-peer consensus network - anyone should be able to run the monero software, validate the integrity of the blockchain, and participate in all aspects of the monero network using consumer-grade commodity hardware. Decentralization of the monero network is maintained by software development that minimizes the costs of running the monero software and inhibits the proliferation of specialized, non-commodity hardware. 
**XMR:** 45bimbTXakUH8KFz7eMNrzPh8Rh6eJDeD98vWwuspTZPTWHGdUJPsmbiuZBBQq4EvAF2NPK29169MKD5bggZEK4gHxuhVmg

## Introduction
Escudo is a private, secure, untraceable, decentralised digital currency.

## License
See [LICENSE](LICENSE).

## Scheduled software upgrades
Escudo uses a fixed-schedule software upgrade (hard fork) mechanism to implement new features. This means that users of Escudo (end users and service providers) should run current versions and upgrade their software on a regular schedule. Software upgrades occur during the months of April and October. The required software for these upgrades will be available prior to the scheduled date. Please check the repository prior to this date for the proper Monero software version. Below is the historical schedule and the projected schedule for the next upgrade.
Dates are provided in the format YYYY-MM-DD.

| Software upgrade block height  | Date       | Fork version      | Minimum Escudo version | Recommended Escudo version | Details                                                                            |  
| ------------------------------ | -----------| ----------------- | ---------------------- | -------------------------- | ---------------------------------------------------------------------------------- |
|                                |            |                   |                        |                            |                                                                                    |



## Release staging schedule and protocol
Approximately three months prior to a scheduled software upgrade, a branch from master will be created with the new release version tag. Pull requests that address bugs should then be made to both master and the new release branch. Pull requests that require extensive review and testing (generally, optimizations and new features) should not be made to the release branch.
