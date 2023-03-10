# rockchip-android-manifest

Tinker Board (S) R2.0 - Android 12

Latest source:

$ repo init -u https://github.com/TinkerBoard-Android/rockchip-android-manifest.git -b android12-rockchip

tinker_board-android12-0.0.3:

$ repo init -u https://github.com/TinkerBoard-Android/rockchip-android-manifest.git -b android12-rockchip -m tinker_board-android12-0.0.3.xml

tinker_board-android12-0.0.5:

$ repo init -u https://github.com/TinkerBoard-Android/rockchip-android-manifest.git -b android12-rockchip -m tinker_board-android12-0.0.5.xml

$ repo sync

$ ./docker_builder/docker-builder-run.sh

$ source build/envsetup.sh

$ lunch Tinker_Board-userdebug 

$ ./build.sh -UCKAu
