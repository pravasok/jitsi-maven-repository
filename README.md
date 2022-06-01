# <p align="center">Jitsi Meet SDK</p>

Jitsi Meet SDK

<hr />


Steps to build custom Jitsi Meet SDK

1. Clone https://github.com/jitsi/jitsi-meet.git
2. Run npm install from jitsi-meet root folder
3. If post install fails because of patch, Run patch -p1 -i patches/react-native+0.61.5-jitsi.2.patch
4. npx patch-package react-native
5. Install jq (https://stedolan.github.io/jq/download/)
6. Run ./android/scripts/release-sdk.sh D:/skilloptima/jitsi-meet-sdk/build/sdk from root folder

For more information on building own SDK check here 
https://jitsi.github.io/handbook/docs/dev-guide/dev-guide-android-sdk#build-and-use-your-own-sdk-artifactsbinaries
