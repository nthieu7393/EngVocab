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

### ios rebuild_signing

```sh
[bundle exec] fastlane ios rebuild_signing
```

Start.......

### ios load_asc_api_key

```sh
[bundle exec] fastlane ios load_asc_api_key
```



### ios upload_release

```sh
[bundle exec] fastlane ios upload_release
```

Upload to TestFlight / ASC

### ios build_upload_testflight

```sh
[bundle exec] fastlane ios build_upload_testflight
```

Build and upload to TestFlight

### ios tests

```sh
[bundle exec] fastlane ios tests
```

Run tests

### ios beta

```sh
[bundle exec] fastlane ios beta
```

Push a new beta build to TestFlight

### ios set_release_version

```sh
[bundle exec] fastlane ios set_release_version
```

Sets the version of the bundle to a RELEASE_VERSION passed in as an environment variable

### ios build_testflight

```sh
[bundle exec] fastlane ios build_testflight
```

Build and upload to TestFlight

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
