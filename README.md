# 简介
这个SKETCH插件可以帮助设计师实施预览画板内容到手机上。

 (⌘P) 调整画板显示尺寸到实际的设备尺寸 
 (⌘⌥P) a画板的内容投影到[Skala
Preview](http://bjango.com/mac/skalapreview)上.

# 安装

*提示: 插件目前升级到 `v0.8.0`版本.如果之前安装过老版本，请在路径下移除旧文件并粘贴新文件

[Download](https://github.com/marcisme/sketch-preview/archive/master.zip) or
clone the latest version of this project, and open the
`SketchPreview.sketchplugin` file.

# 使用方法

* 确保你已经选中了一个图层
* 选择 `Preview` 插件菜单或快捷键（⌘P )
* 选择 `Preview Setup...` 在插件菜单或点击快捷键（⌘⌥P )t去配置快捷键


## 缩放模式

目前的iOS已经有多个设备分辨率. These modes either
change the output size to *2x* or *3x* based on Artboard dimensions, or they
attempt to scale the preview up to simulate the Display Zoom or compatibility
modes available on the iPhones 6. The simulated modes are not currently
accurate, and the final image will be 1 to 2 pixels off in the smaller
dimension.

As of `v0.6.0`, Artboards that are larger in one dimension should be scaled
correctly, allowing preview of mockups of scrollable content.

# Compatibility

This plugin has been used successfully with the following versions of software.
Not all combinations of each application have been tested, but this should give
you some idea of the latest versions that have worked for other people. Feel
free to submit a [pull request](https://github.com/marcisme/sketch-preview/compare/)
if you've used the plugin with a newer version of any of these applications.

* Sketch 3.3.2 (12043)
* Skala Preview 2.0 (205)
* Skala View for iOS 2.0
* Skala View for Android 1.2.2

# Troubleshooting

If you find any issues, you can try to reproduce them with `PreviewTest.sketch`,
found in the test directory of this repository. You can also check the `Enable
debug logging` option in the `Preview Setup` and look at the output in
`Console.app` to get a better idea of what is going on. Please open an
[issue](https://github.com/marcisme/sketch-preview/issues/new) if there is still
a problem.

# Author

[Marc Schwieterman](https://github.com/marcisme) ([@mschwieterman](https://twitter.com/mschwieterman) / [@mbs](https://app.net/mbs))

# Contributors

Big thanks to these people for their contributions.

* [Jacob Elias](https://github.com/jelias) ([@\_jelias\_](https://twitter.com/_jelias_))
* [David Klawitter](https://github.com/davidklaw)
* [Tomas Linhart](https://github.com/TomasLinhart)

# License

MIT License
