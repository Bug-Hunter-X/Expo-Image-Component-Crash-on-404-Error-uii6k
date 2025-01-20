# Expo Image 404 Error Handling

This repository demonstrates a bug in the Expo `Image` component where it crashes when loading an image from a remote URI that returns a 404 error.  The solution involves adding proper error handling to gracefully manage failed image loads.

## Bug
The `bug.js` file shows how the Expo `Image` component crashes without error handling.  When the image fails to load (due to a 404, for example), the app crashes.

## Solution
The `bugSolution.js` file demonstrates a solution using a custom error-handling mechanism with a fallback image. This method catches the error and displays an alternative image, preventing app crashes.

## Setup
1. Clone the repository.
2. Navigate to the directory: `cd expo-image-404`
3. Run `npm install` or `yarn install`
4. Run `expo start`