# Video Player

### 作者：是如梦呀rumeng2233、柒忆未染.

使用前最好把证书安装到受信任的根证书颁发机构里，不然可能会导致“从服务器返回了一个参照。”、UIAccess无法正常准备等问题.

### 启动参数：

- `<urlPath>` - 初始打开的url，**若想使其生效，此启动参数必须为第一个**,
- `-full_screen <value>` - 设置是否全屏[`true`：开启，`false`：关闭],
- `-loop <loopType>` - 设置循环类型[`0`：关，`1`：循环单首，`2`：循环全部，`3`：随机播放],
- `-volume <volumeLevel>` - 设置音量大小[使用APlayer播放时有效范围为`0-1000`(0为静音，100为正常音量，1000为放大10倍)，使用Bass播放时有效范围为`0.0-100.0`(0.0为静音，100.0为正常音量)],
- `-wallpaper <value>` - 设置是否嵌入桌面[`true`：开启，`false`：关闭],
- `-hide_control <value>` - 设置是否隐藏下方播放控件[`true`：隐藏，`false`：显示],
- `-speed <playSpeed>` - 设置播放速度[有效范围为`1-400`(1%-400%播放速度)，**此设置在使用Bass播放时无效**],
- `-top_window <value>` - 设置是否总在最前[UIAccess准备失败时将置顶在一般置顶窗口上，UIAccess准备成功时将置顶在与Microsoft 屏幕放大镜同等Z序(高于开启置于顶层的任务管理器)],
- `-image_enhancement <value>` - 设置是否开启画质增强[**此设置在使用Bass播放时无效**],
- `-render_type <renderType>` - 设置视频的渲染方式[`1`：覆盖模式(Overlay)，`2`：未渲染(Renderless)，`3`：增强型(EVR)，`4`：增强自渲染(EVRCP)，`5`：AVR，**此设置在使用Bass播放时无效**],
- `-disable_video <value>` - 设置是否禁用视频[`true`：禁用，`false`：启用],
- `-disable_audio <value>` - 设置是否禁用音频[`true`：禁用，`false`：启用],
- `-auto_continue_play <value>` - 设置是否开启自动继续播放[`true`：开启，`false`：关闭],
- `-spectrum_update_speed <updateSpeed>` - 设置频谱刷新速度[有效范围为非负数，负数视作0，`0`：停止加载，`>0`：每隔多少毫秒刷新频谱，**此设置在使用APlayer播放时无效**],
- `-spectrum_colours <colourOne|colourTwo|colourThree>` - 设置频谱显示颜色[共三个十进制颜色值，用`|`分割，格式为：`频谱柱上渐变色|频谱柱下渐变色|频谱线色`，**此设置在使用APlayer播放时无效**],
- `-parentHWND <hwnd>` - 初始设置当前Video Player窗口的父窗口[需传入一个`十进制窗口句柄`],
- `/p <hwnd>` - 与`-parentHWND <hwnd>`参数相同,
- `-bass <value>` - 设置是否使用Bass播放[`true`：使用，`false`：不使用],
- `-hide_menu <value>` - 设置是否隐藏播放菜单[`true`：隐藏，`false`：显示],
- `-display_playlist <value>` - 设置是否显示播放列表[`true`：显示，`false`：隐藏].

## 视频播放功能

APlayer媒体播放引擎(http://aplayer.open.xunlei.com/index.html).

## 音频播放功能

BASS audio library(https://www.un4seen.com/).

## 特别鸣谢

柒忆未染,

上海米哈游网络科技股份有限公司(https://www.mihoyo.com/),

《原神》(https://ys.mihoyo.com/main/),

《崩坏：星穹铁道》(https://sr.mihoyo.com/),

VLC media player(https://www.videolan.org/),

深圳市迅雷网络技术有限公司(https://www.xunlei.com/),

Un4seen(https://www.un4seen.com/),

大连大有吴涛易语言软件开发有限公司(https://www.dywt.com.cn/),

《Minecraft》(https://www.minecraft.net/),

是如梦呀rumeng2233.
