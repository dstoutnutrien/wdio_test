https://the-internet.herokuapp.com/

Pick a page and write a test

### Ideas to break tests

- Not waiting for a page/component to exist before interacting with it
- ~~Broken selectors~~
- ~~Maybe a working selector, but it can be improved (like going from xpath -> id)~~
- long browser.pauses that should be removed
- not waiting for an action to be completed before asserting the result (similar to my first bullet point)
- OR, no assertion at all
- hard coding UN/PW if we want to test out that login form
- ~~console logging an entire HTML document~~
- missing async/await keywords when they are needed
- maybe just missing the await part
- If there is some infromation we want to have shared between steps, we should test to see if they know how to do that
- broken gherkin might be good
- two definitions with one expression
