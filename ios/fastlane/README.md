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

### ios load_asc_api_key

```sh
[bundle exec] fastlane ios load_asc_api_key
```

Load App Store Connect API Key information to use in lanes

### ios prepare_signing

```sh
[bundle exec] fastlane ios prepare_signing
```

Installs signing certificate in the keychain and downloads provisioning profiles from store

### ios fetch_and_increment_build_number

```sh
[bundle exec] fastlane ios fetch_and_increment_build_number
```

Bump build number based on most recent TestFlight build number

### ios build_release

```sh
[bundle exec] fastlane ios build_release
```

Build the iOS app for release

### ios upload_release

```sh
[bundle exec] fastlane ios upload_release
```

Upload to TestFlight / ASC

### ios upload_release_appstore

```sh
[bundle exec] fastlane ios upload_release_appstore
```

Upload to Appstore

### ios build_upload_testflight

```sh
[bundle exec] fastlane ios build_upload_testflight
```

Build and upload to TestFlight

### ios build_upload_appstore

```sh
[bundle exec] fastlane ios build_upload_appstore
```

Build and upload to AppStore

### ios beta

```sh
[bundle exec] fastlane ios beta
```

Push a new beta build to TestFlight

### ios build

```sh
[bundle exec] fastlane ios build
```

Build the app

### ios release

```sh
[bundle exec] fastlane ios release
```



----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
