# Nuclei Counter

Browser-based tool for batch counting cell nuclei in fluorescence microscopy images (TIFF). No install, no upload — everything runs locally in your browser.

在浏览器中批量统计荧光显微图像（TIFF）细胞核数量的工具。无需安装、无需上传，全部在本机浏览器运行。

## Live tools / 在线工具

- **English:** https://hengbingao.github.io/cell_counter/tools/NucleiCounter_English_version.html
- **version2：** https://hengbingao.github.io/cell_counter/tools/NucleiCounter_English_version_V2.html
- **中文:** https://hengbingao.github.io/cell_counter/tools/NucleiCounter_Chinese_version.html

add this label, run 在页面上按 Ctrl + F5（Mac 是 Cmd + Shift + R）。

## Features / 功能

- Batch process a whole folder of TIFFs / 批量处理整个文件夹的 TIFF 图片
- Adjustable channel, background removal, threshold (Otsu or manual), min area, watershed splitting / 可调节通道、背景去除、阈值（Otsu 或手动）、最小面积、分水岭拆分
- Live preview with red nucleus outlines / 实时预览，红色核轮廓叠加
- Export results to CSV (filename, count) / 结果导出为 CSV（文件名、核数量）
- Multi-threaded (Web Workers) for smooth, fast processing / 多线程（Web Worker）后台运行，流畅高效

## Usage / 使用方法

1. Open one of the links above in your browser (Chrome/Edge recommended). / 用浏览器打开上方任一链接（推荐 Chrome/Edge）。
2. Click **Select Folder / Multiple TIFFs** or drag files in. / 点击选择文件夹/多选图片，或直接拖入。
3. Adjust the sliders while watching the live preview. / 拖动滑块并观察实时预览。
4. Click **Count All & Download CSV**. / 点击批量计数并下载 CSV。
5，version2 with calculating nuclei concentration.
6. version2 for decode muti-samples from secondary files.


## Notes / 说明

- Supports uncompressed RGB/grayscale TIFF. For compressed TIFF, re-save as uncompressed in ImageJ. / 支持未压缩的 RGB/灰度 TIFF；压缩 TIFF 请先在 ImageJ 另存为未压缩格式。
- Images are never uploaded; all processing is local. / 图片不会上传，全部本地处理。
