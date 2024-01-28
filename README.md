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
|~~`thumbfast` from [MPV_lazy](https://github.com/hooke007/MPV_lazy)~~||
[thumbfast](https://github.com/po5/thumbfast) | 缩略图引擎 |
|[mpv-file-browser](https://github.com/CogentRedTester/mpv-file-browser)|借助osd实现文件浏览器操作|
|~~[chapter-make-read](https://github.com/dyphire/mpv-scripts)~~ | |
|[chapters for mpv](https://github.com/mar04/chapters_for_mpv)|视频章节(书签)|


|辅助模组|作用|
|---|---|
|[mpv-user-input](https://github.com/CogentRedTester/mpv-user-input)|借助console实现用户输入


## 附注

1. [MPV_lazy](https://github.com/hooke007/MPV_lazy) 魔改的 `thumbfast` 在 `video-rotate` 旋转视频后无法使用，故弃用。
2. [chapter-make-read](https://github.com/dyphire/mpv-scripts) 生成的 chapter 文件在修改时似乎存在异常，且相比于 simple 格式，[chapters for mpv](https://github.com/mar04/chapters_for_mpv) 生成的 ffmpeg metadata 格式文本，能够很方便的通过 ffmpeg 将章节文件写入视频元数据。
3. 上述插件未启用全部功能，仅依照个人需求进行配置。
4. 因设备条件有限，故 ~~折腾不了~~ 不折腾滤镜、着色器等 QAQ
5. 力求可兼容、可迁移，因此可直接 `git clone` 使用

