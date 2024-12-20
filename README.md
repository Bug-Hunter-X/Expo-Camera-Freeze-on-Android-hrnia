# Expo Camera Freeze on Android

This repository demonstrates a bug in the Expo `Camera` API where the camera preview freezes on some Android devices after prolonged use. The preview becomes unresponsive and requires a full application restart to resolve. This issue is particularly apparent during long recording sessions or when the camera is active for extended periods. The solution offered focuses on implementing a mechanism to proactively manage and release camera resources to mitigate this issue. 

## Reproduction

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app on an affected Android device. 
4. Observe the camera preview for extended use.