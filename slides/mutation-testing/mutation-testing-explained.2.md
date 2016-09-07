<h2>Mutation testing process</h2>

1. <!-- .element: class="fragment" -->
   Production code is mutated
    * A mutated version of your app is called a `Mutant`
2. <!-- .element: class="fragment" -->
    Your tests are ran for each `Mutant`
    * If tests *fail*, the mutant is *killed*
    * If tests *pass*, the mutant *survived*
3. <!-- .element: class="fragment" -->
    The percentage of `mutant`s that got *killed* is your *mutation score*
