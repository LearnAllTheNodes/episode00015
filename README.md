# Learn All The Nodes Episode 15

## Testing in Node.js

[View the episode](http://www.learnallthenodes.com/episodes/15-testing-in-nodejs)

A lot has been said about test-driven development over the years, and that has ranged from a deep understanding of it to simply repeating slogans.  Writing tests, and especially writing them first, can have a lot of benefits, but testing is just a tool, and tools are no substitute for proper software design.  Regardless, we can’t use tools without knowing how to use them, so in this week’s episode we dive into testing using Mocha.

Mocha is a testing framework that provides us with a way to organize tests and group them together logically.  Paired up with the `assert` module that's built right into Node, Mocha quite nearly takes care of all the framework we need to write tests.

We won't get into testing our route handlers here, but this episode will give us the core that we need to start testing our domain layer.

### Notes

[Test-driven development](http://en.wikipedia.org/wiki/Test-driven_development)

[Mocha homepage](http://mochajs.org/)

`./node_modules/mocha/bin/mocha path/to/test/file.js`

[Node assert module](http://nodejs.org/api/assert.html)

    describe(__filename, function() {
      it("should be a test", function(done) {
        assert(true)
        done()
      }
    }

[Episode code](https://github.com/LearnAllTheNodes/episode00015)
