# Assignment 1 - IT3040 ITPM

This repository contains the Playwright automation project for Assignment 1.

## Prerequisites
- Node.js (v14 or higher)

## Installation
1. Clone the repository.
2. Open a terminal in the project folder.
3. Install dependencies:
   ```bash
   npm install
   ```
   This will install `playwright` and other required packages.
   If prompted to install Playwright browsers, run:
   ```bash
   npx playwright install
   ```

## Running the Tests
To execute the automated test suite and generate the result CSV file:

```bash
npx playwright test
```

## Output
- The test execution will generate a report file `test-results.csv` in the root directory.
- This CSV file contains the 42 test scenarios (31 Positive, 11 Negative) with their status and actual outputs.

## Project Structure
- `tests/swift_test.spec.js`: Main automation script.
- `test-inputs.js`: Input data for the test cases.
- `package.json`: Project dependencies and scripts.
- `playwright.config.js`: Playwright configuration.
