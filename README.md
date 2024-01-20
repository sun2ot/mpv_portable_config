## Introduction

- 自用 mpv 配置包
- mpv 版本：Video player based on MPlayer/mplayer2 (builds by shinchiro)
- 安装来源：

    ```powershell
    scoop bucket add extras
    scoop install extras/mpv-git
    ```

## 相关目录

|插件|作用|
|---|---|
|`uosc` from [MPV_lazy](https://github.com/hooke007/MPV_lazy)|第三方ui（含右键菜单）|
|`load_plus` from [MPV_lazy](https://github.com/hooke007/MPV_lazy) | 自动加载目录下文件到播放列表 |
|`playlist_osd` from [MPV_lazy](https://github.com/hooke007/MPV_lazy) | 借助osd实现播放列表 |
|`thumbfast` from [MPV_lazy](https://github.com/hooke007/MPV_lazy) | 缩略图引擎 |
|[mpv-file-browser](https://github.com/CogentRedTester/mpv-file-browser)|借助osd实现文件浏览器操作|
|[chapter-make-read](https://github.com/dyphire/mpv-scripts)|视频章节(书签)|


|辅助模组|作用|
|---|---|
|[mpv-user-input](https://github.com/CogentRedTester/mpv-user-input)|借助console实现用户输入


## 附注

1. [MPV_lazy](https://github.com/hooke007/MPV_lazy) 魔改的 `thumbfast` 似乎在默认mpv上存在兼容问题，请屏蔽其配置文件中的 `bin` 参数。
2. 上述插件未启用全部功能，仅依照个人需求进行配置。
3. 因设备条件有限，故 ~~折腾不了~~ 不折腾滤镜、着色器等 QAQ
4. 力求可兼容、可迁移，因此可直接 `git clone` 使用

