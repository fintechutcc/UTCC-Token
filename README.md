# UTCC-Token

## Mnemonic
medal guard puppy mimic satisfy scene range ritual until cloth eagle bunker

## Code
โค้ดสำหรับทดลองการสร้าง UTCC Token

```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract UTCCToken is ERC20 {

   constructor() ERC20("UTCCToken", "U3C") {
     _mint(msg.sender, 1000*10**18);
   }
}
```

## Private Key
4d7972e7a846000e8459012e07af596150dba4cff8772787549c1aedde5e5610
