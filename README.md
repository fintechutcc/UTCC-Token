# UTCC-Token


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

