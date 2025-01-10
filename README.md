# JavaScript Loose Equality with null and undefined

This repository demonstrates a common pitfall in JavaScript related to loose equality (==) when comparing null and undefined values.

## Problem

The provided JavaScript code uses loose equality to check if a variable is null. While it works correctly for null, it fails when the variable is undefined, leading to unexpected NaN output.

## Solution

The solution uses strict equality (===) to correctly distinguish between null and undefined values, providing more reliable results.

## Usage

1. Clone this repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code.
4. Run the JavaScript files using Node.js or a web browser's console.