---
tags: 
parent docs: 
sibling docs: 
child docs: 
last updated: 2025-01-21T13:12:00
media:
---
## Subnet Mask
Separated into a network and host section, used to differentiate network class

|     |     | Network | Host |             |
| --- | --- | ------- | ---- | ----------- |
| 192 | 168 | 0       | 1    | IP 1        |
| 255 | 255 | 0       | 0    | Subnet mask |
| 192 | 168 | 15      | 0    | IP 2        |

# [[Binary]]
0,1

| Decimal | 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| ------- | --- | --- | --- | --- | --- | --- | --- | --- |
| 54      | 0   | 0   | 1   | 1   | 1   | 0   | 0   | 0   |
| 255     | 1   | 1   | 1   | 1   | 1   | 1   | 1   | 1   |
| 190     | 1   | 0   | 1   | 1   | 1   | 1   | 1   | 0   |
| 15      | 0   | 0   | 0   | 0   | 1   | 1   | 1   | 1   |

# [[Hexadecimal]] 
0,2,3,4,5,6,7,8,9,A,B,C,D,E,F

| Decimal | Binary   | 4,096 | 256 | 16  | 1   |
| ------- | -------- | ----- | --- | --- | --- |
| 100     | 11000010 | 0     | 0   | 6   | 4   |
| 255     | 11111111 | 0     | 0   | F   | F   |
|         |          |       |     |     |     |

AF -> 10101111 -> 128+32+8+4+2+1 = 175

