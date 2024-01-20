# IBC Resources

## 📺 IBC Channels

| src-chain-id  | dst-chain-id              | src-channel   | dst-channel    | Note                |
|---------------|---------------------------|---------------|----------------|---------------------|
| `tabi_9789-1` | `evmos_9000-4`            | `channel-1`   | `channel-232`  | Evmos Testnet       |


## 🫰 IBC Assets

The following are all the assets currently supported by `tabi_9789-1` along with their corresponding IBC denomination.

When assets are transferred through IBC, they lose their base denomination (i.e `tevmos`) and obtain a new IBC denomination (e.g. `ibc/68EC0162ECC4C6026E85E645D3F2C44D46957F600773974AE41922EE539F91E3`).

| Token       | Base Denom | IBC Denom                                                              |
|-------------|------------|------------------------------------------------------------------------|
| tEVMOS      | `atevmos`  | `ibc/68EC0162ECC4C6026E85E645D3F2C44D46957F600773974AE41922EE539F91E3` |


## 🧑‍💻 IBC Development

### 🚰 Faucets 

| Chain       | Chain ID                  | Faucet                                                                                  |
|-------------|---------------------------|-----------------------------------------------------------------------------------------|
| Tabi        | `tabi_9789-1`             | <https://faucet.testnet.tabichain.com>                                                  |
| Evmos       | `evmos_9000-4`            | <https://faucet.evmos.dev>                                                  |


### Public Endpoints

The following table provides public endpoints for various blockchain networks. Please note that these endpoints are not managed by Tabi (except for the ones under the `*.tabichain.com` domain). 

These public endpoints are listed here solely for the purpose of simplifying development and testing of applications that interact with the respective blockchain networks. Osmosis provides no guarantee regarding the accuracy, reliability, or availability of these endpoints.

| Chain       | Chain ID                  | RPC                                                    | REST                                                |
|-------------|---------------------------|--------------------------------------------------------|-----------------------------------------------------|
| Tabi        | `tabi_9789-1`             | <https://tm.testnet.tabichain.com:443>                 | <http://rest.testnet.tabichain.com>                 |
| Evmos       | `evmos_9000-4`            | <https://evmos-testnet-rpc.polkachu.com:443>           | <https://grpc-t.evmos.nodestake.top>                |