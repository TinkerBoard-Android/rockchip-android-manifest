# rockchip-android-manifest

$ repo init -u https://github.com/TinkerBoard-Android/rockchip-android-manifest.git -b android12-rockchip
$ repo sync
$ ./docker_builder/docker-builder-run.sh
$ source build/envsetup.sh
$ lunch Tinker_Board-userdebug 
$ ./build.sh -UCKAu
