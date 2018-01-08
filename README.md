XUEZ Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/PIVX-Project/PIVX.svg?branch=master)](https://travis-ci.org/PIVX-Project/PIVX) [![GitHub version](https://badge.fury.io/gh/PIVX-Project%2FPIVX.svg)](https://badge.fury.io/gh/PIVX-Project%2FPIVX)

PIVX is a cutting edge cryptocurrency, with many features not available in most other cryptocurrencies.
- Anonymized transactions using coin mixing technology, we call it _Obfuscation_.
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftTX_.
- Decentralized blockchain voting providing for consensus based advancement of the current Masternode
  technology used to secure the network and provide the above features, each Masternode is secured
  with a collateral of 10K PIV.

More information at [pivx.org](http://www.pivx.org) Visit our ANN thread at [BitcoinTalk](http://www.bitcointalk.org/index.php?topic=1262920)

### Coin Specs
| Algo                        | Quark |
|-----------------------------|----------------|
| Block Time                  | 60 Seconds     |
| Difficulty Retargeting      | Every Block    |
| Max Coin Supply (PoW Phase) | 43,199,500 PIV |
| Max Coin Supply (PoS Phase) | Infinite       |
| Premine                     | 60,000 PIV*    |

*60,000 PIV Premine was burned in block [279917](http://www.presstab.pw/phpexplorer/PIVX/block.php?blockhash=206d9cfe859798a0b0898ab00d7300be94de0f5469bb446cecb41c3e173a57e0)

### Reward Distribution

#### PoW Phase Mining - Approx 180 Days

|  **Block Height**       | **Reward Amount/Notes**  |
|-------------------------|--------------------------|
| 60,000 PIV              | Initial Premine 0 Days   |
| 2-151200                | 250 PIV                  |
| 151201-259200           | 50 PIV                   |

#### PoS Phase
| **Block Height**  | **Reward Amount** |
|-------------------|-------------------|
| 259201-Infinite   | Variable based on [SeeSaw Reward Mechanism](https://pivx.org/knowledge-base/see-saw-rewards-mechanism) |

### PoW Rewards Breakdown

| **Block Height**| **Masternodes** | **Miner** | **Budget** |
|---------------|---------------|---------------|------------|
| 2-43200       | 20% (50 PIV)  | 80% (200 PIV) | N/A |
| 43201-151200  | 20% (50 PIV)  | 70% (200 PIV) | 10% (25 PIV) |
| 151201-259200 | 45% (22.5 PIV)| 45% (22.5 PIV)| 10% (5 PIV) |

### PoS Rewards Breakdown
| **Phase** | **Block Height** | **Reward** | **Masternodes & Stakers** | **Budget**    |
|-----------|------------------|------------|---------------------------|---------------|
| Phase 1   | 259201-302399    | 50 PIV     | 90% (45 PIV)              | 10% (5 PIV)   |
| Phase 2   | 302400-345599    | 45 PIV     | 90% (40.5 PIV)            | 10% (4.5 PIV) |
| Phase 3   | 345600-388799    | 40 PIV     | 90% (36 PIV)              | 10% (4 PIV)   |
| Phase 4   | 388800-431999    | 35 PIV     | 90% (31.5 PIV)            | 10% (3.5 PIV) |
| Phase 5   | 432000-475199    | 30 PIV     | 90% (27 PIV)              | 10% (3 PIV)   |
| Phase 6   | 475200-518399    | 25 PIV     | 90% (22.5 PIV)            | 10% (2.5 PIV) |
| Phase 7   | 518400-561599    | 20 PIV     | 90% (18 PIV)              | 10% (2 PIV)   |
| Phase 8   | 561600-604799    | 15 PIV     | 90% (13.5 PIV)            | 10% (1.5 PIV) |
| Phase 9   | 604800-647999    | 10 PIV     | 90% (9 PIV)               | 10% (1 PIV)   |
| Phase X   | 648000-Infinite  | 5 PIV      | 90% (4.5 PIV)             | 10% (0.5 PIV) |

