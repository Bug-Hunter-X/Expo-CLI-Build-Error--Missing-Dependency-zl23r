# Expo CLI Build Error: Missing Dependency

This repository demonstrates a common Expo CLI build error caused by missing or incorrectly configured dependencies.  The `bug.js` file shows example code that might trigger the error, and `bugSolution.js` demonstrates the corrected version.

## Problem

Expo apps rely on a precise set of dependencies. If a dependency is missing, or there is a version conflict, the build process will fail.  This example highlights the issue and the solution.

## Solution

The solution usually involves carefully reviewing the `package.json` file and ensuring all dependencies are correctly listed with compatible versions.  Using `yarn` or `npm` to update or install missing dependencies is also critical. In complex cases, examining the specific error message to pinpoint the problematic dependency and its root cause is needed.