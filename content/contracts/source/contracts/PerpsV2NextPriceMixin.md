# PerpsV2NextPriceMixin

## Description

**Source:** [contracts/PerpsV2NextPriceMixin.sol](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol)

## Variables

### `nextPriceOrders`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L20)</sub>

**Type:** `mapping(address => struct IPerpsV2BaseTypes.NextPriceOrder)`

## Internal Functions

### `_confirmationWindowOver`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L230)</sub>

??? example "Details"

    **Signature**

    `_confirmationWindowOver(uint256 currentRoundId, uint256 targetRoundId) view returns (bool)`

    **Visibility**

    `internal`

    **State Mutability**

    `view`

### `_exchangeRates`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L236)</sub>

??? example "Details"

    **Signature**

    `_exchangeRates() view returns (contract IExchangeRates)`

    **Visibility**

    `internal`

    **State Mutability**

    `view`

### `_nextPriceCommitDeposit`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L241)</sub>

??? example "Details"

    **Signature**

    `_nextPriceCommitDeposit(struct PerpsV2MarketBase.TradeParams params) view returns (uint256)`

    **Visibility**

    `internal`

    **State Mutability**

    `view`

### `_submitNextPriceOrder`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L41)</sub>

??? example "Details"

    **Signature**

    `_submitNextPriceOrder(int256 sizeDelta, bytes32 trackingCode)`

    **Visibility**

    `internal`

    **State Mutability**

    ``

    **Requires**

    * [require(..., "previous order exists")](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L43)

    **Emits**

    * [PositionModified](#positionmodified)

    * [NextPriceOrderSubmitted](#nextpriceordersubmitted)

## External Functions

### `cancelNextPriceOrder`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L104)</sub>

??? example "Details"

    **Signature**

    `cancelNextPriceOrder(address account)`

    **Visibility**

    `external`

    **State Mutability**

    ``

    **Requires**

    * [require(..., "no previous order")](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L108)

    **Emits**

    * [NextPriceOrderRemoved](#nextpriceorderremoved)

### `executeNextPriceOrder`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L163)</sub>

??? example "Details"

    **Signature**

    `executeNextPriceOrder(address account)`

    **Visibility**

    `external`

    **State Mutability**

    ``

    **Requires**

    * [require(..., "no previous order")](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L167)

    * [require(..., "target roundId not reached")](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L171)

    * [require(..., "order too old, use cancel")](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L178)

    **Emits**

    * [PositionModified](#positionmodified)

    * [NextPriceOrderRemoved](#nextpriceorderremoved)

### `submitNextPriceOrder`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L31)</sub>

??? example "Details"

    **Signature**

    `submitNextPriceOrder(int256 sizeDelta)`

    **Visibility**

    `external`

    **State Mutability**

    ``

### `submitNextPriceOrderWithTracking`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L37)</sub>

??? example "Details"

    **Signature**

    `submitNextPriceOrderWithTracking(int256 sizeDelta, bytes32 trackingCode)`

    **Visibility**

    `external`

    **State Mutability**

    ``

## Events

### `NextPriceOrderRemoved`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L262)</sub>

**Signature**: `NextPriceOrderRemoved(address account, uint256 currentRoundId, int256 sizeDelta, uint256 targetRoundId, uint256 commitDeposit, uint256 keeperDeposit, bytes32 trackingCode)`

### `NextPriceOrderSubmitted`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.76.1/contracts/PerpsV2NextPriceMixin.sol#L253)</sub>

**Signature**: `NextPriceOrderSubmitted(address account, int256 sizeDelta, uint256 targetRoundId, uint256 commitDeposit, uint256 keeperDeposit, bytes32 trackingCode)`
