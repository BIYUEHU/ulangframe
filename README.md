# ULANGFrame

[ULANGFrame文档](https://huliapi.xyz:86/ulangdoc)

[ULANGAddon-betaV0.1.0](https://github.com/BIYUEHU/ulangframe/releases/tag/ulang)

**ULANGFrame**(ULANG框架)的制作初衷为

>  创造更多方便快捷的接口以及UI部分(主要是菜单型UI)，以弥补官方脚本引擎接口的不足之处。

**ULANG**以**MinecraftBE**Addon(附加包)的Script Engine(脚本引擎)为基础,在其官方给的已有API中进行扩展开发。

[](./ULANGbe/pack_icon.png)

### ScriptEngine
即**脚本引擎**,首次加入在MinecraftBEbeta1.8.0.3中。在其刚加入时部分开发者或玩家就已抱有期望；

脚本引擎属于基岩版**Addon(附加包)**的一部分，但与其它的在本质上就有极大不同，脚本引擎是由**JavaScript**语言承载，而不是JSON文件编写

这使脚本引擎在其本质上就有较大潜力，可通过监听游戏的各种事件来触发各种内容

### 初期制作

**ULANG**制作最初是来自**Log_record**(行为记录)Addon,开始制作于2020年7月份，后期也将其Log_record的内容作为Api加入到ULANG内

在目前**ULANG**已有多达30Alpha版本，具体内核版本数量更为甚多

### 目前依赖该前置Addon列表：
| 中文名字    | 英文名字 | 图标                                                         | 作者                                                | 依赖版本         | 详细信息                                                     |
| ----------- | -------- | ------------------------------------------------------------ | --------------------------------------------------- | ---------------- | ------------------------------------------------------------ |
| 基岩版工业2 | BEic2    | <img src="https://img.imgdb.cn/item/5ffb0ec93ffa7d37b38b5097.png" alt="BEic2" style="zoom:25%;" /> | [@碧月狐dada](https://space.bilibili.com/293767574) | 自V0.6.0起       | [BEic2基岩版工业2系列](https://biyuehu.github.io/post/BEic2%E5%9F%BA%E5%B2%A9%E7%89%88%E5%B7%A5%E4%B8%9A2/) |
| 基岩版星系  | BEgc     | <img src="https://img.imgdb.cn/item/5f8bed041cd1bbb86b5543ff.png" alt="BEgc" style="zoom:25%;" /> | [@碧月狐dada](https://space.bilibili.com/293767574) | 自beta1231pre1起 | [BEgc基岩版星系](https://biyuehu.github.io/post/BEgc%E5%9F%BA%E5%B2%A9%E7%89%88%E6%98%9F%E7%B3%BB/) |

**我们欢迎也支持更多创作者使用ULANG！**

## 关于

**ULANGFrame By BIYUEU**

本文档由**BIYUEHU**编写，严禁转载

作者博客>[biyuehu.github.io](https://biyuehu.github.io)

博客ULANG记录文章[-->](https://biyuehu.github.io/post/ULANG%E6%A1%86%E6%9E%B6/)

目前ULANG仍为半成品状态，服务端与客户端API已较为完善，但两者的API处于并立状态，配置项也仍未完全搬到同一边，强迫症可能会很难受

ULANG的H5UI仅是示例的存在，后端(脚本引擎)的对接接口已具备

Alpha阶段关闭，将发布第一个beta公开版本
![](./images/1.png)
![](./images/2.png)

*⚠警告:ULANG框架基于行为包的ScriptEngine脚本引擎(SE)，而SE目前基本已被OJANG放弃，用于替代的则是基于QuickJS的Gametest(社区名:Plugin)。现在发出ULANG这个东西仅是为了发布，而非胎死腹中，虽说发了后也会死，但不发就感觉跟什么都没做一样；所以说本作品最新版本ULANGAddon-betaV0.1.0之后永不再更新*
