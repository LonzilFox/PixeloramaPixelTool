# Pixelorama Pixel Tool

一个用于将普通图片快速转换成像素风素材的网页工具，适合导出后继续在 **Pixelorama** 中编辑。

在线使用：

```text
https://lonzilfox.github.io/PixeloramaPixelTool/
```

## 功能

- 图片像素化
- 自定义输出尺寸
- 限制调色板颜色数量
- Bayer / Floyd-Steinberg 抖动
- 去除纯色、白色或黑色背景
- 亮度、对比度、饱和度调整
- 自动裁剪透明区域
- 1px 像素描边
- 像素网格预览
- 导出透明 PNG
- 导出放大版 PNG
- 导出 GPL 调色板

## 使用

1. 导入图片
2. 设置目标尺寸和颜色数量
3. 根据需要调整去背景、抖动和颜色参数
4. 预览处理结果
5. 导出 PNG，并在 Pixelorama 中继续编辑

## 特点

整个工具直接在浏览器中运行，无需安装、无需后端服务器。

图片仅在本地浏览器中处理，不会上传到服务器。

## 本地运行

直接打开：

```text
index.html
```

即可使用。

## 项目结构

```text
PixeloramaPixelTool/
├── index.html
└── README.md
```

本项目不是 Pixelorama 官方项目，仅作为像素素材预处理辅助工具。