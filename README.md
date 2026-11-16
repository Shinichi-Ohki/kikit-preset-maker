# KiKit Preset Maker

[KiKit](https://github.com/yaqwsx/KiKit) の `kikit panelize -p 〜.json` 用プリセットを、画面で作るツールです。

**→ https://shinichi-ohki.github.io/kikit-preset-maker/**

## 日本語

- 面付けの設定をフォームで入力すると、KiKit のプリセット JSON ができます
- パネルのプレビュー、上限サイズからの枚数計算、文字入れのシミュレーションつき
- 設定のまずいところを警告して、ボタン 1 つで直せます
- KiKit の GUI で保存した JSON を読み込んで編集できます
- 日本語 / English / 简体中文。用語は KiCad 9 の公式翻訳に合わせています
- HTML ファイル 1 つだけで動きます。KiKit 本体のインストールは不要です

```bash
kikit panelize -p panel-preset.json board.kicad_pcb panel.kicad_pcb
```

## English

A browser tool for building presets for KiKit's `kikit panelize -p ….json`.

- Fill in a form and get a KiKit preset JSON
- Panel preview, board count fitting to a size limit, and a text preview
- Warns about problematic settings and fixes them in one click
- Import and edit JSON saved from the KiKit GUI
- 日本語 / English / 简体中文, with terms matching KiCad 9's official translations
- A single self-contained HTML file. KiKit does not need to be installed

## 简体中文

在浏览器中生成 KiKit `kikit panelize -p ….json` 预设的工具。

- 在表单中填写设置，即可得到 KiKit 预设 JSON
- 提供拼板预览、按尺寸上限计算数量、文字效果预览
- 提示有问题的设置，并可一键修正
- 可导入并编辑从 KiKit GUI 保存的 JSON
- 日本語 / English / 简体中文，术语与 KiCad 9 官方翻译一致
- 仅一个 HTML 文件即可运行，无需安装 KiKit

## Notes

- The preview is an approximation. Always check the generated panel in KiKit / KiCad.
- Default values are taken from KiKit's `kikit/resources/panelizePresets/default.json` (MIT License, Copyright (c) 2020 Jan Mrázek).
- Japanese and Simplified Chinese terms follow the KiCad 9.0 translations (`translation/pofiles`).
