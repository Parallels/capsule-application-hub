## What's Changed in application-hub v0.0.13-canary

Base version (stripped): 0.0.13
- Introduced constants for various feedback colors.
- Created FeedbackFormData interface to structure feedback submissions.
- Defined FeedbackPayload and FeedbackPayloadField interfaces for detailed feedback data.
- Started refactoring on the UI for the new controls
- Added the new feedback modal
- Improved the Modal engine
- Lots of UI tweaks
- Removed unnecessary calls to configService.init() in various components.
- Updated config fetching logic to use DEFAULT_CONFIG as fallback.
- Simplified debug tab management in Home component.
- Enhanced memoization in ConfigService for improved performance.
- Added application ready listener in SSEService for better connection handling.
- Improved logging throughout the application for better traceability.
- Cleaned up unused code and comments in ConfigService.
- Adjusted AuthService to dynamically construct login URLs based on configuration.
- Removed tenant_id from LoginCredentials interface as it was not used.
- Move the internet check to a curl instead of a ping

### Installation

Download the appropriate package for your platform from the [release assets](https://github.com/Parallels/capsule-application-hub/releases/tag/v0.0.13-canary).

### Links
- **Public Repository**: [github.com/Parallels/capsule-application-hub](https://github.com/Parallels/capsule-application-hub)
- **Monorepo Release**: [application-hub-v0.0.13-canary](https://github.com/Parallels-Corp/capsule-manager/releases/tag/application-hub-v0.0.13-canary)
