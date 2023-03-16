#  Vits-targ
基于 VITS 训练得到的 **targ 语音模型**。目前仅支持中文/日文。

VITS モデルをベースとした **targ 音声モデル**。現在、中国語/日本語のみ対応しています。

#  本地部署

1. 下载最新的 Release 包（在Github页面的右侧）。
2. 运行 `inference.exe`, 浏览器会自动弹出窗口, 注意其所在路径不能有中文字符或者空格。
3. Have Fun XD。

# 在MoeGoe使用
0. MoeGoe以及类似其它 VITS 推理 UI 使用的 config 格式略有不同，需要下载的文件为模型`G_latest.pth`和配置文件`moegoe_config.json`。<br>
1. G_latest.pth 可在最新版 Release 包中找到，moegoe_config.json可在 code 区 MoeGoe 文件夹中找到。
2. 按照[MoeGoe](https://github.com/CjangCjengh/MoeGoe)页面的提示配置路径即可使用。
3. MoeGoe在输入句子时需要使用**相应的语言**标记包裹句子才能**正常合成**。（日语用[JA], 中文用[ZH], 英文用[EN]）<br>例如：  
[JA]こんにちわ。[JA]  
[ZH]你好！[ZH]  
[EN]Hello![EN]
