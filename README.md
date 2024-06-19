### Odd or Even Tests HTML

This HTML file sets up a testing environment for determining if numbers are odd or even using Mocha and Chai.

- **Meta Tags:** Define character encoding, viewport settings, and compatibility with IE.
- **Title:** Sets the document title to "Odd or Even Tests".
- **Styles and Scripts:**
  - **Mocha CSS:** Styles the test results output.
  - **Mocha JS:** Loads the Mocha testing framework.
  - **Chai JS:** Loads the Chai assertion library.
- **Body:**
  - **Mocha Div:** Container for displaying test results.
  - **Mocha Setup:** Configures Mocha to use the BDD interface.
  - **Script Loading:**
    - `odd-or-even.js`: Contains functions to determine if numbers are odd or even.
    - `odd-or-even.test.js`: Contains tests for the odd-or-even functions.
  - **Mocha Run:** Executes the Mocha tests.

This setup ensures a comprehensive and functional test environment for the odd-or-even functions.

### Odd or Even Function

This JavaScript function determines if a given number is odd or even:

- **oddOrEven(num):** 
  - Takes a single argument `num`.
  - Returns `"even"` if `num` is divisible by 2.
  - Returns `"odd"` if `num` is not divisible by 2.

This function uses the modulus operator `%` to check the divisibility of the number by 2 and returns the appropriate string based on the result.
