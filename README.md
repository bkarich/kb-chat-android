[![Buildkite](https://badge.buildkite.com/ad0065c1b70f557cd3b1d3d68f9c2154010f83c4d6f71706a9.svg?branch=develop)](https://buildkite.com/matrix-dot-org/element-android/builds?branch=develop)
[![Weblate](https://translate.element.io/widgets/element-android/-/svg-badge.svg)](https://translate.element.io/engage/element-android/?utm_source=widget)
[![Element Android Matrix room #element-android:matrix.org](https://img.shields.io/matrix/element-android:matrix.org.svg?label=%23element-android:matrix.org&logo=matrix&server_fqdn=matrix.org)](https://matrix.to/#/#element-android:matrix.org)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=vector-im_element-android&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=vector-im_element-android)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=vector-im_element-android&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=vector-im_element-android)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=vector-im_element-android&metric=bugs)](https://sonarcloud.io/summary/new_code?id=vector-im_element-android)

# Element Android

Element Android is an Android Matrix Client. The app can be run on every Android devices with Android OS Lollipop and more (API 21).

It is a total rewrite of [Riot-Android](https://github.com/vector-im/riot-android) with a new user experience.


# New Android SDK

Element is based on a new Android SDK fully written in Kotlin (like Element). In order to make the early development as fast as possible, Element and the new SDK currently share the same git repository.

At each Element release, the SDK module is copied to a dedicated repository: https://github.com/matrix-org/matrix-android-sdk2. That way, third party apps can add a regular gradle dependency to use it. So more details on how to do that here: https://github.com/matrix-org/matrix-android-sdk2.

# Roadmap

The version 1.0.0 of Element still misses some features which was previously included in Riot-Android.
The team will work to add them on a regular basis.

# Releases to app stores

There is some delay between when a release is created and when it appears in the app stores (Google Play Store and F-Droid). Here are some of the reasons:

* Not all versioned releases that appear on GitHub are considered stable. Each release is first considered beta: this continues for at least two days. If the release is stable (no serious issues or crashes are reported), then it is released as a production release in Google Play Store, and a request is sent to F-Droid too.
* Each release on the Google Play Store undergoes review by Google before it comes out. This can take an unpredictable amount of time. In some cases it has taken several weeks.
* In order for F-Droid to guarantee that the app you receive exactly matches the public source code, they build releases themselves. When a release is considered stable, Element staff inform the F-Droid maintainers and it is added to the build queue. Depending on the load on F-Droid's infrastructure, it can take some time for releases to be built. This always takes at least 24 hours, and can take several days.


## Contributing

Please refer to [CONTRIBUTING.md](https://github.com/kbarich/kb-chat-android/blob/develop/CONTRIBUTING.md) if you want to contribute on Matrix Android projects!

