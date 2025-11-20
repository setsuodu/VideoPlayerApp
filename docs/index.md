# 不支持 Markdown？

# Welcome to MkDocs

Avalonia, MVVM, LibVLCSharp快速搭建视频播放器
你需要安装以下 NuGet 包：
- LibVLCSharp.Avalonia: 包含用于在 Avalonia 中显示视频的 VideoView 控件。
- LibVLCSharp: 核心 LibVLCSharp 库。
- VideoLAN.LibVLC.*.Platform: 根据你的目标平台，安装对应的原生 LibVLC 运行时包（例如 VideoLAN.LibVLC.Windows、VideoLAN.LibVLC.Mac、VideoLAN.LibVLC.Linux）。

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
