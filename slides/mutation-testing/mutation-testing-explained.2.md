<h1>Mutation testing</h1>

1. <!-- .element: class="fragment" data-fragment-index="1" -->
    Production code is mutated
    * A mutation is called a `Mutant`
2. <!-- .element: class="fragment" data-fragment-index="2" -->
    Your tests are ran for each `Mutant`
    * If tests fail, the mutant is *killed*
    * If tests pass, the mutant *survived*
3. <!-- .element: class="fragment" data-fragment-index="3" -->
    The percentage of `mutant`s that got *killed* is your **mutation score**
