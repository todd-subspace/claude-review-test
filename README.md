# claude-review-test

A test repository for validating the Claude Code Review GitHub Action.

## Example function

Here is a simple JavaScript function with an intentional bug for testing:

```javascript
function calculateAverage(numbers) {
  let sum = 0;
  for (let i = 0; i <= numbers.length; i++) {
    sum += numbers[i];
  }
  return sum / numbers.length;
}
```

## Usage

This repo is used to verify that commenting `@claude` on a PR triggers a review.
