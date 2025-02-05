# Next.js 15 JSX Error with \n
This repository demonstrates a confusing error in Next.js 15 related to using the newline character  `\n` within JSX. The issue is that the error message is not very helpful in pinpointing the problem.

## Bug

The `pages/index.js` file contains a simple JSX structure.  Including a newline character (`\n`) after the `<p>` tag causes a build error.  The error message is misleading and doesn't clearly indicate the cause.

## Solution

The solution is to remove the newline character or, better yet, use a more consistent formatting for your JSX.

## How to reproduce

1. Clone the repository
2. Run `npm install`
3. Run `npm run dev`

Observe the error in the console.  Then, modify the `pages/index.js` file according to the solution provided to resolve the issue. 