# evan testcore network

## Installation

Install [Parity](https://github.com/paritytech/parity/releases) from Parity's official website. Download the [evan.network testcore config file](https://raw.githubusercontent.com/evannetwork/testcore-config/master/testcore.json). Run Parity with `parity --chain testcore.json`.

```
parity --chain "/path/to/testcore.json" --config "path/to/contractus_test_chain.toml"
```


The config *.toml most likely will have to be adjusted for individual and local requirements, and only serves as an example and starting point. In backend development you may not even need it at all.
