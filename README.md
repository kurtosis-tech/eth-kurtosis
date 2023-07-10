# eth-testnet-index
An index of packages and examples for getting started with private Ethereum testnets using Kurtosis.

### Available Testnet Components

| Component | Type | URL | Import Statement |
| --- | --- | --- | --- |
| Geth | EL client | [Github](https://github.com/kurtosis-tech/geth-package) | `import_module("github.com/kurtosis-tech/geth-package/lib/geth.star")` |
| Lighthouse | CL client | [Github](https://github.com/kurtosis-tech/lighthouse-package) | `import_module("github.com/kurtosis-tech/lighthouse-package/lib/lighthouse.star")` |
| MEV Boost | MEV Infra | TBD | TBD |

### Composed Testnet Package Examples

| Package | URL | Import Statement |
| --- | --- | --- |
| Geth + Lighthouse | [Github](https://github.com/kurtosis-tech/geth-lighthouse-package) | `import_module(github.com/kurtosis-tech/geth-lighthouse-package)` |
| Geth + Lighthouse + MEV Infra | TBD | TBD |

### Roadmap

- [ ] Turn tables into pretty-formatted blocks so people can click-to-copy import statements
- [ ] Add README for quick start + install instructions to Kurtosis
- [ ] Fill out components with each available EL and CL client
- [ ] Add example testnet packages for flexible EL/CL pairings
- [ ] Fill out componenets with each MEV infra component
- [ ] Add example testnet package for MEV infra + EL/CL pairings
