
### Remove conditionals
| Original                         | Mutated                         |
| -------------------------------- | ------------------------------- |
| for (var i = 0; i < 10; i++) { } | for (var i = 0; false; i++) { } |
| while (a > b) { }                | while (false) { }               |
| do { } while (a > b);            | do { } while (false);           |
| if (a > b) { }                   | if (true) { }                   |
| if (a > b) { }                   | if (false) { }                  |

