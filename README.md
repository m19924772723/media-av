# 音视频 / 图形 — 媒体处理流水线

**定位**：视频合成、转码、字幕、逐帧动画、批量图片处理

**本机状态**：✅ 可直接开发

**工具链**：ffmpeg 9.0.1（full build）、ffprobe、Pillow、Playwright

**建议技术栈**：ffmpeg、Pillow、moviepy（可选）

**注意**：已有 workflows/video-pipeline（Pillow 逐帧 + ffmpeg）可复用

## 子方向索引

本方向再细分为 **7** 个应用子方向，每个子方向一个子目录（均含 README + 6 份文档）：

| 子目录 | 子方向 | 本机状态 |
|---|---|---|
| [`video-transcode`](./video-transcode/) | 视频转码与处理 | ✅ |
| [`video-generate`](./video-generate/) | 视频自动生成 | ✅ |
| [`image-process`](./image-process/) | 图像处理与批处理 | ✅ |
| [`screen-record`](./screen-record/) | 录屏与设备投屏 | ✅ |
| [`subtitle-asr`](./subtitle-asr/) | 字幕与语音转写 | ✅ |
| [`animation-render`](./animation-render/) | 动效与程序化渲染 | ✅ |
| [`audio-process`](./audio-process/) | 音频处理与合成 | ✅ |

---

**放什么**：本方向的具体项目放在对应子方向目录下（每个项目再建一个子目录）。
