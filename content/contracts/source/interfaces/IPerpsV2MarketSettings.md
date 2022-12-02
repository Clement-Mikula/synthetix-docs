# IPerpsV2MarketSettings

## Description

**Source:** [contracts/interfaces/IPerpsV2MarketSettings.sol](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol)

## Structs

### `Parameters`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L5)</sub>

| Field                          | Type      | Description |
| ------------------------------ | --------- | ----------- |
| `takerFee`                     | `uint256` | TBA         |
| `makerFee`                     | `uint256` | TBA         |
| `takerFeeDelayedOrder`         | `uint256` | TBA         |
| `makerFeeDelayedOrder`         | `uint256` | TBA         |
| `takerFeeOffchainDelayedOrder` | `uint256` | TBA         |
| `makerFeeOffchainDelayedOrder` | `uint256` | TBA         |
| `maxLeverage`                  | `uint256` | TBA         |
| `maxMarketValue`               | `uint256` | TBA         |
| `maxFundingVelocity`           | `uint256` | TBA         |
| `skewScale`                    | `uint256` | TBA         |
| `nextPriceConfirmWindow`       | `uint256` | TBA         |
| `delayedOrderConfirmWindow`    | `uint256` | TBA         |
| `minDelayTimeDelta`            | `uint256` | TBA         |
| `maxDelayTimeDelta`            | `uint256` | TBA         |
| `offchainDelayedOrderMinAge`   | `uint256` | TBA         |
| `offchainDelayedOrderMaxAge`   | `uint256` | TBA         |
| `offchainMarketKey`            | `bytes32` | TBA         |
| `offchainPriceDivergence`      | `uint256` | TBA         |

## Views

### `delayedOrderConfirmWindow`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L40)</sub>

??? example "Details"

    **Signature**

    `delayedOrderConfirmWindow(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `liquidationBufferRatio`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L68)</sub>

??? example "Details"

    **Signature**

    `liquidationBufferRatio() view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `liquidationFeeRatio`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L66)</sub>

??? example "Details"

    **Signature**

    `liquidationFeeRatio() view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `makerFee`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L28)</sub>

??? example "Details"

    **Signature**

    `makerFee(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `makerFeeDelayedOrder`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L32)</sub>

??? example "Details"

    **Signature**

    `makerFeeDelayedOrder(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `makerFeeOffchainDelayedOrder`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L36)</sub>

??? example "Details"

    **Signature**

    `makerFeeOffchainDelayedOrder(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `maxDelayTimeDelta`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L56)</sub>

??? example "Details"

    **Signature**

    `maxDelayTimeDelta(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `maxFundingVelocity`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L50)</sub>

??? example "Details"

    **Signature**

    `maxFundingVelocity(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `maxLeverage`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L46)</sub>

??? example "Details"

    **Signature**

    `maxLeverage(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `maxMarketValue`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L48)</sub>

??? example "Details"

    **Signature**

    `maxMarketValue(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `minDelayTimeDelta`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L54)</sub>

??? example "Details"

    **Signature**

    `minDelayTimeDelta(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `minInitialMargin`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L70)</sub>

??? example "Details"

    **Signature**

    `minInitialMargin() view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `minKeeperFee`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L64)</sub>

??? example "Details"

    **Signature**

    `minKeeperFee() view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `nextPriceConfirmWindow`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L38)</sub>

??? example "Details"

    **Signature**

    `nextPriceConfirmWindow(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `offchainDelayedOrderMaxAge`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L44)</sub>

??? example "Details"

    **Signature**

    `offchainDelayedOrderMaxAge(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `offchainDelayedOrderMinAge`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L42)</sub>

??? example "Details"

    **Signature**

    `offchainDelayedOrderMinAge(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `offchainMarketKey`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L60)</sub>

??? example "Details"

    **Signature**

    `offchainMarketKey(bytes32 _marketKey) view returns (bytes32)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `offchainPriceDivergence`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L62)</sub>

??? example "Details"

    **Signature**

    `offchainPriceDivergence(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `parameters`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L58)</sub>

??? example "Details"

    **Signature**

    `parameters(bytes32 _marketKey) view returns (struct IPerpsV2MarketSettings.Parameters)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `skewScale`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L52)</sub>

??? example "Details"

    **Signature**

    `skewScale(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `takerFee`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L26)</sub>

??? example "Details"

    **Signature**

    `takerFee(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `takerFeeDelayedOrder`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L30)</sub>

??? example "Details"

    **Signature**

    `takerFeeDelayedOrder(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `takerFeeOffchainDelayedOrder`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.80.0-alpha/contracts/interfaces/IPerpsV2MarketSettings.sol#L34)</sub>

??? example "Details"

    **Signature**

    `takerFeeOffchainDelayedOrder(bytes32 _marketKey) view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`