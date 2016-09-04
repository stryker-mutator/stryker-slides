## Example: Plugin a mutator

```JavaScript
import {MutatorFactory} from 'stryker-api/mutant';
class BlockStatementMutator {
  applyMutations(node, copy) {
    let nodes = [];
    let mutatedNode = copy(node);
    mutatedNode.body = [];
    nodes.push(mutatedNode);
    return nodes;
  }
}
MutatorFactory.instance()
    .register('BlockStatement', BlockStatementMutator);
```
