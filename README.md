# Unexpected Return Value for Zero in JavaScript Function

This repository demonstrates a subtle bug in a JavaScript function that leads to unexpected return values when the input is zero.

## Bug Description

The `foo` function aims to classify numbers as negative, zero, or positive.  However, due to a logic error, it incorrectly classifies zero as positive.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js`.
3. Run the script. Observe the unexpected output for the input value of 0.

## Solution

The solution file `bugSolution.js` corrects the logical error to ensure the function correctly handles zero.