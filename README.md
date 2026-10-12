# Swift Pro issue tracker

This is the public issue tracker for **Swift Pro**, the Swift development plugin for JetBrains IDEs.
The commercial plugin's source code is maintained separately and is not published in this repository.

## Report a problem or suggest an improvement

- [Report a bug](https://github.com/Jetplugins/intellij-swift-pro-plugin/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/Jetplugins/intellij-swift-pro-plugin/issues/new?template=feature_request.yml)
- [Browse existing issues](https://github.com/Jetplugins/intellij-swift-pro-plugin/issues)

Before opening an issue, please search for an existing report and update Swift Pro to the latest available version. Include the Swift Pro version, IDE name and full build, operating system, project type, reproducible steps, and a minimal Swift example. For compiler, build, or Apple workflow issues, include your Swift toolchain and Xcode versions and the relevant destination.

Swift source files, package manifests, build output, and IDE logs can contain confidential project information. Remove credentials, proprietary code, personal information, and other sensitive data before attaching examples, screenshots, or logs to a public issue.

For security vulnerabilities, use [GitHub's private vulnerability reporting](https://github.com/Jetplugins/intellij-swift-pro-plugin/security/advisories/new) instead of creating a public issue. See the [security policy](SECURITY.md).

## About Swift Pro

Swift Pro combines native IntelliJ editors, toolbars, run configurations, and tool windows with your installed Swift development tools:

- Swift editing, compiler completion and documentation, navigation, inlay hints, inspections, formatting, and refactoring.
- SwiftPM package imports and native executable and test configurations.
- Xcode project, workspace, scheme, and destination discovery, with application and XCTest workflows.
- Native debugging through LLDB-DAP, including macOS and iOS Simulator application debugging.
- SwiftUI preview builds and captured simulator images, Apple device controls, and compiler macro expansion inspection.

Basic editing works without a Swift toolchain. Compiler assistance and execution features require compatible installed tools and a trusted project. Apple workflows require macOS and Xcode; simulator workflows also require an installed runtime. SwiftUI previews are compiled apps with captured images. Physical-device debugging and signing/provisioning management are not implemented.
