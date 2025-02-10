# 更新说明

本适配指南为`iMessage_For_WeChat`开源归档版本`v1.2.3`后如何自行`DIY`补充适配说明和指南。(自己从 0 制作一份主题？参考完整 [《主题适配指南》](https://github.com/AidenYang1/ThemeDocs_WeChat_For_Themebox)（请爬 🪜）。)

# 1. 下载归档版本

一切的工作都基于`v1.2.3`归档版本。请先下载[最后归档版本](https://github.com/AidenYang1/iMessageApp_WeChat_For_Themebox/releases)。

继续使用`v1.2.3`版本，自行基于正式版更新的新增命名整理适配，**但不再提供素材**。<br>
(线上版无需自行DIY，直接查看更新说明并更新即可。[打赏赞助](https://weidian.com/item.html?itemID=7385357613&spider_token=b6d5)使用线上版)


<br>

# 2.更新
- **线上版**赞助者请更新`Themebox`至`1.1.6`，直接使用插件**一键更新**到最新完整v1.2.4版本。

## v1.2.4（线上正式版）

### 优化

- 修复：网页聊天箭头方向（插件修复，请更新到 Themebox`1.1.5`及以上版本)
- 优化对方`气泡方向`、恢复我的表情的`收藏按钮`。
- 优化调整官方菜单底栏`名片`、`接龙`图标。
- 优化`朋友圈评论、点赞`、微信助手工具栏`文件图标`。
- 优化调整`多设备登录图标显示`、`红包封面打开背景高度`

### 新增

- 新增浅色模式、深色模式下`首页加号栏OLED`适配
- 新增收藏页`长按标签`图标、全局`关闭`图标、`摄像头切换`、`群聊消息置顶`、`朋友圈点赞取消` 、`刷新` 图标。
- 新增适配`聊天页长按多选菜单操作`。
- 新增适配`微信运动`、`微信游戏`映射。(更新`Themebox`到`1.1.5`及以上版本)
- 新增`群公告`-`编辑工具栏`、`网页浏览器商品分类`适配。
- 新增红包转账卡组:`10《数字货币交易所》`系列 5 张。

<img src="https://worker.imtheme.site/69RUUzH.png" alt="红包转账卡组" width="500">

### 其他

- 若未弹出更新,请更新`Themebox`到`1.1.6`版本。
- `imtheme.site`已接入`Cloudflare`CDN，并启用`Workers`代理，国内用户现可正常访问。(仍推荐使用代理访问，速度更快)
- 前`100`名赞助者已全部上`泡泡墙`,若有问题请通过`issue`反馈。

#### 开源版

- 修复`v1.2.3`开源归档版本及以往版本部分红包转账卡组在`深色模式`下显示突兀`白色边缘`问题。
- 增加`v1.2.3`开源归档版本`红色角标`替换文件。位于`01供替换的素材中`，并已打包整理。
- 修复在以往版本中漏掉的已知问题。
  （新的归档版本已上传至`release`页面）

### 已知问题

到最新版本为止，已知问题均整理在[使用指南-8.已知问题中](https://www.imtheme.site/guide)。若有新的问题请通过[issue](https://github.com/AidenYang1/iMessageApp_WeChat_For_Themebox/issues)反馈（反馈前请筛选 ALL 而非仅 Open 查看是否已有他人反馈相同问题）。**参与此部分的贡献可获赠兑换码。**

<br><br>

### 该版本新适配的命名整理

现在，轮到你动手尝试了。

|        解释        |                                                        命名                                                        |                                 说明                                 |
| :----------------: | :----------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------: |
|      微信运动      |                                               Plugins_WeSport_avatar                                               | 该部分使用原型软件导出基于 60\*60 像素的@2x,@3x 图标，以确保清晰度。 |
|      微信游戏      |                                             icons_wegame_default_icon                                              |                                 同上                                 |
|    首页+号菜单     |                              MoreFunctionFrame(浅色) <br>MoreFunctionFrame_Dark(深色)                              |                        不要做过多设计，会拉伸                        |
| 聊天页长按多选菜单 | share_regular（分享）<br>icon_outlined_download_select(下载选中) <br>trash_on_regular(删除)<br>email_regular(邮箱) |                      regular 为通用素材，会共用                      |
|     摄像头切换     |                                                icons_filled_switch                                                 |                                  /                                   |
|     群消息置顶     |                                                     icon_stick                                                     |                              使用小尺寸                              |
|        刷新        |                                                icons_filled_refresh                                                |                                  /                                   |
|     朋友圈点赞     |                                                    heart_filled                                                    |                               通用共用                               |
| 群公告-编辑工具栏  |         icons_outlined_dottedlist(换行)<br>Icons_outlined_order(有序列表)<br>Icons_outlined_item(无序列表)         |                                  /                                   |
| 网页浏览器商品分类 |                                      icons_webview_custom_menu_pdd_categories                                      |                                  /                                   |
|   收藏页长按标签   |                                                     tag_filled                                                     |                                  /                                   |
|    全局关闭按钮    |       xmark_filled<br>xmark_regular<br>icons_outlined_close<br>icons_filled_close5<br>icons_filled_close<br>       |                               全局关闭                               |

（如需图标尺寸完全按照`UIImageView`或`Layout`视图渲染显示，不出现任何尺寸**偏大偏小**问题，请使用`svg`素材。由于`svg`素材受`xml`文件影响较大，请自行结合其他方案调整。）<br>
**（仅整理在以往版本未出现的命名，且优化调整、问题修复部分命名不整理。请自行参考以往开源文件查看对应命名或使用归档的 Sketch 项目文件自行 DIY,如有问题请通过 [issue](https://github.com/AidenYang1/iMessageApp_WeChat_For_Themebox/issues)反馈）**

<br><br>

#### 自己从 0 制作一份主题？参考完整 [《主题适配指南》](https://github.com/AidenYang1/ThemeDocs_WeChat_For_Themebox)（请爬 🪜）。

<br>
