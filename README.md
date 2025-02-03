# JavaScript Closure Issue in Loops

This repository demonstrates a common error in JavaScript related to closures within loops.  The code appears to intend to print numbers 0-9 with a 1-second delay between each. However, due to how closures work in JavaScript, it will instead print 10 ten times.

The `bug.js` file contains the problematic code.  The solution is provided in `bugSolution.js`.