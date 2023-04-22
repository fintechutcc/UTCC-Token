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

## การทดสอบ
การทดสอบอย่างง่าย สามารถทำได้บน Testnet อย่างเช่น Sepolia โดยกำหนด RPC ใน Metamask เป็นดังนี้
```
https://purple-proud-lake.ethereum-sepolia.discover.quiknode.pro/12475d343ad214dabaf2abab5730ebddc466d29b/
```

## การนำเข้าโทเคน
การนำเข้าโทเคนใน Metamask สามารถทำได้โดยใช้ Address ตัวอย่างต่อไปนี้
```
0x17EAb41709Dc940CfA1E200ea53408e444B58E7b
```
