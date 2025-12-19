## What's Changed in application-hub v0.0.18-beta

Base version (stripped): 0.0.18
- Added a new flow for the user when they have a application that requires credentials, fix #106
- Fixed an issue where a modal error was showing in the wrong place #105
- Fixed some minor issues with the UI, fix #109 
- rebranded the application hub to the new Capsule Hub, fixes #102 
- Implement a notification modal system, triggered by backend network errors or anything else
- Added debug controls, with a centralized modal size definition.
- Added specialized message for specific no local network error fixes #96
- Added a retry process for the install script if it fails first time #93
- Added a `Report Issue` button in the splashscreen in case of errors to share info #97
- Fixed a bug where the initialization script was run a second time with no need #95
- Fixed some issues with initialization variables

### Installation

Download the appropriate package for your platform from the [release assets](https://github.com/Parallels/capsule-application-hub/releases/tag/v0.0.18-beta).

### Links
- **Public Repository**: [github.com/Parallels/capsule-application-hub](https://github.com/Parallels/capsule-application-hub)
- **Monorepo Release**: [application-hub-v0.0.18-beta](https://github.com/Parallels-Corp/capsule-manager/releases/tag/application-hub-v0.0.18-beta)
