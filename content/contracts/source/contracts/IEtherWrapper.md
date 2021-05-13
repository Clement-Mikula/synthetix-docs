# IEtherWrapper

## Description

**Source:** [contracts/interfaces/IEtherWrapper.sol](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol)

## External Functions

### `burn`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L9)</sub>

??? example "Details"

    **Signature**

    `burn(uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `burnFeeRate`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L27)</sub>

??? example "Details"

    **Signature**

    `burnFeeRate() view returns (uint256)`

    **Visibility**

    `public`

    **State Mutability**

    `undefined`

### `calculateBurnFee`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L21)</sub>

??? example "Details"

    **Signature**

    `calculateBurnFee(uint256 amount) view returns (uint256)`

    **Visibility**

    `public`

    **State Mutability**

    `undefined`

### `calculateMintFee`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L19)</sub>

??? example "Details"

    **Signature**

    `calculateMintFee(uint256 amount) view returns (uint256)`

    **Visibility**

    `public`

    **State Mutability**

    `undefined`

### `capacity`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L13)</sub>

??? example "Details"

    **Signature**

    `capacity() view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `distributeFees`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L11)</sub>

??? example "Details"

    **Signature**

    `distributeFees()`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `getReserves`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L15)</sub>

??? example "Details"

    **Signature**

    `getReserves() view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `maxETH`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L23)</sub>

??? example "Details"

    **Signature**

    `maxETH() view returns (uint256)`

    **Visibility**

    `public`

    **State Mutability**

    `undefined`

### `mint`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L7)</sub>

??? example "Details"

    **Signature**

    `mint(uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `mintFeeRate`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L25)</sub>

??? example "Details"

    **Signature**

    `mintFeeRate() view returns (uint256)`

    **Visibility**

    `public`

    **State Mutability**

    `undefined`

### `totalIssuedSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L17)</sub>

??? example "Details"

    **Signature**

    `totalIssuedSynths() view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `weth`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.45.0-alpha/contracts/interfaces/IEtherWrapper.sol#L29)</sub>

??? example "Details"

    **Signature**

    `weth() view returns (contract IWETH)`

    **Visibility**

    `public`

    **State Mutability**

    `undefined`