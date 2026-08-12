# 微信二维码 / WeChat QR codes

`index.html` 里「微信公众号 · 视频号」按钮会读取本目录下的这四张图片。
文件名必须完全一致,格式为 PNG(JPG 也可,但需同步改 `index.html` 里的扩展名):

| 文件名 | 帐号 | 类型 |
| --- | --- | --- |
| `gene2h-mp.png` | 基因智健 Gene to Health | 微信公众号 |
| `gene2h-channel.png` | 基因智健 Gene to Health | 微信视频号 |
| `lane-mp.png` | 路数说 Lane No. BB | 微信公众号 |
| `lane-channel.png` | 路数说 Lane No. BB | 微信视频号 |

缺失的图片会被自动跳过;四张都缺失时,页面上的入口按钮不显示,因此不会出现裂图。

上传:在本目录点 **Add file → Upload files**,或直接打开
<https://github.com/unfated/cv/upload/main/assets/qr>
