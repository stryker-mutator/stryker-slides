
### Reverse conditional
| Original | Mutated  ||||| Original | Mutated  |
| -------- | -------- |||||----------| ---------|
| a == b   | a != b   ||||| a >= b   | a < b    |
| a != b   | a == b   ||||| a < b    | a >= b   |
| a === b  | a !== b  ||||| a > b    | a <= b   |
| a !== b  | a === b  ||||| a && b   | a &#124;&#124; b |
| a <= b   | a > b    ||||| a &#124;&#124; b | a && b   |
