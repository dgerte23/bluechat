# bluechat
（*中文见下方*）

> A lightweight Bluetooth chat app by **YINB**. 
>一款由 **YINB** 开发的轻量级蓝牙聊天工具。

## English 

**BlueChat** lets two nearby devices chat over Bluetooth — no internet needed.
**Note:** This is a Debug build. The developer is a LazinessBro and will not continue maintaining it. 

- **UI**: Simple white & blue Material Design (Chinese UI, but minimal text — usable without knowing Chinese).
- **Features**: Small size, zero configuration, just connect & chat.
- **How to use**: Tap "waiting link" on top → tap connect → pick a paired/trusted device. If your device isn't paired, pair it in system settings first.
- **Known bugs**: Input box doesn't auto-expand; splash animation may flash green (icon was dragged straight into Android Studio, made with 画世界Pro); icon may appear small on some launchers.
- **Protocol**: Messages are wrapped in `<Chatinformation> ... </Chatinformation>`. Plain text only (no images/files). No XSS protection — but it does nothing dangerous either.
- **Disclaimer**: No Chinese ICP license (a system reminder may pop up — just ignore it). Collects **no data**. Completely **free**.

## 中文说明

这是一个蓝牙聊天工具，有着不错的 UI。开发者目前是个神人，所以目前这个 App 还是 Debug 版本，但开发者懒得做了——开发者是一个 LazinessBro，不会继续维护。

1. **UI**：白色和蓝色为主（用了谷歌自带 UI，可能出现紫色），下方输入栏 + 发送按钮，中文内容极少，不会中文也能流畅使用。
2. **特点**：连接设备后即可近距离聊天，体积小巧、不占空间，轻松使用才是优先。
3. **使用方法**：点击上方"等待链接"→ 点击右侧"连接设备"→ 在弹出窗口选择设备。前提是设备须是已绑定的信任设备，否则请先到系统设置绑定后返回操作。
4. **Bug**：输入框不会自动扩展；深色模式下界面仍为浅色；刚打开时过渡动画可能闪现绿色（图标是直接拖进 Android Studio 的，用画世界 Pro 制作，可能偏小）。
5. **发送内容**：仅支持文本，内部格式为 `<Chatinformation>（发送内容）</Chatinformation>`。没有做 XSS 防护，但基本无任何攻击作用。
6. **声明**：软件没有中国 ICP，安装时弹出的提醒忽略即可。软件不会窃取任何信息，可放心使用，完全免费。

Aww～

## Download | 下载

GitHub and China Quark Cloud Drive
Quark Cloud Drive : https://pan.quark.cn/s/a70353225438
