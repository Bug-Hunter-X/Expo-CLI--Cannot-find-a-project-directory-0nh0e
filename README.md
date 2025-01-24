# Expo CLI: Project Directory Not Found Error

This repository demonstrates a common error encountered when using the Expo CLI: the failure to find a project directory.  This occurs when attempting to execute Expo commands outside a valid Expo project or when the project's configuration files (`package.json`, `expo.json`) are corrupted.

## Steps to Reproduce

1.  Clone this repository.
2. Open your terminal and navigate to the root directory.
3. Attempt to run an Expo command such as `expo start` (without navigating to the 'project' folder first) or by corrupting the project files for the 'project' folder.

## Solution

The solution involves ensuring you're in the correct directory and that your `package.json` and `expo.json` files are properly configured and not corrupted.  See `expoBugSolution.js` for a demonstration of correctly setting up a project.