# Next.js 15 - next/link Unexpected Behavior in Dynamic Components

This repository demonstrates a bug encountered when using the `next/link` component within dynamically rendered components in Next.js 15.  The issue is that the link does not always function as expected, potentially causing unexpected full page reloads or incorrect routing.

The bug is reproduced in `bug.js`.  A potential solution is provided in `bugSolution.js`.

**Steps to Reproduce:**

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior of the link.