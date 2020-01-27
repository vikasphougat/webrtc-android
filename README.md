# WebRTC Build for Android

[![License](https://img.shields.io/badge/license-MIT%20%2F%20Apache%202.0-blue.svg)](https://github.com/threema-ch/webrtc-android)

This is a WebRTC build with Java bindings packaged for Android.

The builds are created using [webrtc-build-docker](https://github.com/threema-ch/webrtc-build-docker).


## Installing

The package is available [on
Bintray](https://bintray.com/threema/maven/webrtc-android/). It includes the
WebRTC PeerConnection build for ARM and x86, both 32 and 64 bit builds.

Gradle:

```groovy
compile 'ch.threema.webrtc:webrtc-android:78.0.0'
```

Maven:

```xml
<dependency>
  <groupId>ch.threema.webrtc</groupId>
  <artifactId>webrtc-android</artifactId>
  <version>78.0.0</version>
  <type>pom</type>
</dependency>
```


## Hashes

These are the SHA256 hashes for the published releases of this project:

- v78.0.0 `2a54022e2d8d69ce33897fddb45cec74c87413eefeebc48f81eaf548b649d200`
- v77.0.0 `24797af64d17fd195f20b264029b14ee5024b4b6fdee27bd5363bdee79a868af`
- v76.0.0 `7164372eb184e50081ab3139edf4e66c3aaa8b017b44b8fd42ef8e9f372f85a5`
- v75.0.0 `9bdf02510ab8b30506557425985584441ee712ea435db4c6cd8d11116edba5d9`
- v74.0.0 `0e61dcde1e0242db69b7798a705126c638170deac06c4dc927beea2922be1768`
- v73.0.0 `92a10a82cb18331e863ca910c333420678e6ec0022448f2e67354845c440e0dd`
- v72.0.1 `f23e9c382457fee661d232a8efb22fc4cfb90436a98785b2991af412faeaa99f`
- v72.0.0 `30da1a431dd2b97b3d8492dbdfeeaf43c30e2d177e3782c098ab9d0c54d895df`


## License

    Copyright (c) 2019-2020 Threema GmbH

    Licensed under the Apache License, Version 2.0, <see LICENSE-APACHE file>
    or the MIT license <see LICENSE-MIT file>, at your option. This file may not be
    copied, modified, or distributed except according to those terms.
