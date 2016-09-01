<h1>Mutation testing terminology</h1>

1. <!-- .element: class="fragment" -->
    Test your *tests*
2. <!-- .element: class="fragment" -->
    Process
    1. Production code is mutated
        * A mutation is called a `Mutant`
    2. <!-- .element: class="fragment" -->
        Your tests are ran for each `Mutant`
        * If tests *fail*, the mutant is *killed*
        * If tests *pass*, the mutant *survived*
3. <!-- .element: class="fragment" -->
    The percentage of `mutant`s that got *killed* is your *mutation score*
