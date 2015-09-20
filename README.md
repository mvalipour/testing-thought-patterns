# testing-thought-patterns

- Write code for your tests, not the other way around. 
  - tests are your spec, you satisfy your spec (test) by some (minimum required) code
  - then you start seeing everything as spec (including functional and non-functional) and avoid YAGNI codes.
  - You also will endup with a more SOLID design -- making code accessible for testing usually drives towards cleaner and more modular (hence more maintainable) code.
  - Gives rapid feedback about your design
- If it's very sophisticated to setup tests, your design is not well-composed
- If a component (class) is hard to name, it probably shouldn't exist
- Not everything you refactor-out should be mocked
- Beware of negative testing with doing TDD

Patterns:

- monitoring driven development
- property-based testing

Books:

- GOOS
