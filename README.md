# rockchip-android-manifest

For more information, please go to TinkerBoard wiki.

    https://github.com/TinkerBoard/TinkerBoard/wiki

Please refer to the following URL to install Docker Engine on Ubuntu.

    https://docs.docker.com/engine/install/ubuntu/

Please refer to the following URL to install Repo. 

    https://source.android.com/setup/develop#installing-repo

Please refer to the following URL to understand how to download the AOSP-based source.

    https://source.android.com/setup/build/downloading

To check out the specific branch:

    $ repo init -u https://github.com/TinkerBoard-Android/rockchip-android-manifest.git -b REVISION

To check out the specific release:

    $ repo init -u https://github.com/TinkerBoard-Android/rockchip-android-manifest.git -b REVISION -m NAME.xml

Here REVISON is the manifest branch or revision (use HEAD for default) and NAME.xml is the initial manifest file. Regarding the branches and manifest for each project, please refer to the following release table.

To download the Android source tree to your working directory from the repositories as specified in the default manifest, run:

    $ repo sync

|Product|Android version|Release|Branch|Manifest|
|-|-|-|-|-|
|Tinker Board (S)|Android N|latest|n-mr1-rk3288-tb||
|Tinker Board (S)|Android N|14.4.0.5|n-mr1-rk3288-tb|14.4.0.5.xml|
|Tinker Board (S)|Android N|14.4.0.14|n-mr1-rk3288-tb|14.4.0.14.xml|
|Tinker Board (S)|Android N|14.4.0.18|n-mr1-rk3288-tb|14.4.0.18.xml|
|Tinker Board (S)|Android N|14.4.0.22|n-mr1-rk3288-tb|14.4.0.22.xml|
|Tinker Board (S)|Android N|14.4.0.23|n-mr1-rk3288-tb|14.4.0.23.xml|
|Tinker Board (S) R2.0|Android N|14.4.0.22|n-mr1-rk3288-tb|14.4.0.22.xml|
|Tinker Board (S) R2.0|Android N|14.4.0.23|n-mr1-rk3288-tb|14.4.0.23.xml|
|Tinker Board (S) R2.0|Android 11|latest|android11-rockchip||
|Tinker Board (S) R2.0|Android 11|1.0.0|android11-rockchip|tinker_board-android11-1.0.0.xml|
|Tinker Board (S) R2.0|Android 12|latest|android12-rockchip||
|Tinker Board (S) R2.0|Android 12|0.0.3|android12-rockchip|tinker_board-android12-0.0.3.xml|
|Tinker Board (S) R2.0|Android 12|0.0.5|android12-rockchip|tinker_board-android12-0.0.5.xml|
|Tinker Edge R|Android P|latest|p-rk3399pro||
|Tinker Edge R|Android P|1.0.1|p-rk3399pro|tinker_edge_r-android9-1.0.1.xml|
|Tinker Edge R|Android P|1.0.2|p-rk3399pro|tinker_edge_r-android9-1.0.2.xml|
|Tinker Edge R|Android P|1.0.6|p-rk3399pro|tinker_edge_r-android9-1.0.6.xml|
|Tinker Board 2/2S|Android 10|latest|android10-rk3399||
|Tinker Board 2/2S|Android 10|0.0.3|android10-rk3399|tinker_board_2-android10-0.0.3.xml|
|Tinker Board 2/2S|Android 10|1.0.0|android10-rk3399|tinker_board_2-android10-1.0.0.xml|
|Tinker Board 2/2S|Android 11|latest|android11-rk3399||
|Tinker Board 2/2S|Android 11|2.0.1|android11-rk3399|tinker_board_2-android11-2.0.1.xml|
|Tinker Board 2/2S|Android 11|2.0.3|android11-rk3399|tinker_board_2-android11-2.0.3.xml|
|Tinker Board 2/2S|Android 11|latest|android11-rockchip||
|Tinker Board 2/2S|Android 11|2.0.5|android11-rockchip|tinker_board_2-android11-2.0.5.xml|
|Tinker Board 2/2S|Android 11|2.0.6|android11-rockchip|tinker_board_2-android11-2.0.6.xml|
|Tinker Board 2/2S|Android 11|2.0.8|android11-rockchip|tinker_board_2-android11-2.0.8.xml|
