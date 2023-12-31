fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios build

```sh
[bundle exec] fastlane ios build
```

Build pizzahutSG_dev IPA

### ios upload

```sh
[bundle exec] fastlane ios upload
```

Upload ipa to AppCenter

### ios publishDevelopment

```sh
[bundle exec] fastlane ios publishDevelopment
```

Build and upload PizzaHut DEV to App Center

### ios publishStaging

```sh
[bundle exec] fastlane ios publishStaging
```

Build and upload PizzaHut Staging to App Center

### ios publishDevelopmentFromGithubActions

```sh
[bundle exec] fastlane ios publishDevelopmentFromGithubActions
```

Build and upload PizzaHut DEV to App Center

### ios publishStagingFromGithubActions

```sh
[bundle exec] fastlane ios publishStagingFromGithubActions
```

Build and upload PizzaHut Staging to App Center

### ios setup

```sh
[bundle exec] fastlane ios setup
```

Sync certificates

----


## Android

### android build

```sh
[bundle exec] fastlane android build
```

Build development apk

### android upload

```sh
[bundle exec] fastlane android upload
```

Upload apk to AppCenter

### android publishDevelopment

```sh
[bundle exec] fastlane android publishDevelopment
```

Build and upload Android development app to App Center.

### android publishStaging

```sh
[bundle exec] fastlane android publishStaging
```

Build and upload Android stating app to App Center.

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
