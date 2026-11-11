# BMMV — 篮球经理

BMMV（Basketball Manager Mobile Vibe）的官方 Android 安装包发布仓库。

## 下载

- [全部版本与下载](https://github.com/as7er/bmmv-releases/releases)
- [当前测试版：BMMV Android v1.0.0 build7 universal](https://github.com/as7er/bmmv-releases/releases/tag/v1.0.0-preview.7)
- [直接下载 APK](https://github.com/as7er/bmmv-releases/releases/download/v1.0.0-preview.7/BMMV-Android-v1.0.0-build7-universal.apk)
- [SHA-256 校验文件](https://github.com/as7er/bmmv-releases/releases/download/v1.0.0-preview.7/SHA256SUMS.txt)

无需 GitHub 账号即可下载。Release 附件不依赖 Expo 临时构建链接；只要仓库及附件保留，版本下载地址可继续使用。GitHub 服务可用性和本地网络情况可能影响访问。

APK文件名采用“应用名-平台-v版本-build构建号-CPU架构”。`universal`为多架构通用包，本版包含arm64-v8a、armeabi-v7a、x86、x86_64；旧版文件名及链接保留。

## 安装与更新

1. 在 Android 手机浏览器下载 APK。
2. 打开文件；系统提示时，仅为用于下载的浏览器或文件管理器允许“安装未知应用”。
3. 安装后直接打开 BMMV，不需要 Expo Go、开发服务器或电脑。
4. 更新时使用同包名、同签名的官方 APK 覆盖安装；不要先卸载，卸载或清除应用数据会丢失本地存档。

独立 APK 与 Expo Go、网页版的存档不共享，不会自动导入旧进度。建议首次安装创建测试联盟，保留原应用的数据。

## 当前状态

当前版本为预发布测试版。包含球队管理、自动排阵、赛季推进、2D 比赛直播、临场换人和战术、比赛进度保存恢复。

构建号7新增完整存档导出/导入与覆盖前备份，改善坏档恢复、保存失败重试、终场提交和经理操作反馈；修复手动换阵操纵签权报价，并增加自由球员新签后30个游戏推进日禁交易、AI实际补强需求与自由市场替代选择判断。等待期跨季保留，提前开季不能跳过；旧档无等待记录的合同不追溯。保留build5的横屏球场、沉浸模式、解说字幕和观赛常亮。沿用存档格式，可覆盖安装旧版，不要先卸载；新版导出文件不保证可回导旧APK。

当前版本为预发布测试版，原生存档文件选择/分享、独立APK的真机冷启动、后台/强退恢复和长时间运行仍待验收。请不要将测试版作为重要存档的唯一副本。

建议检查：断网冷启动 → 开赛 → 保存离开并继续 → 切后台/锁屏 → 强退重开 → 终场保存 → 下一场。突然退出允许重播当前片段，不能整场丢失或重复累计赛果。

## 发布范围

本仓库仅公开安装包、校验文件与使用/版本说明，不包含 BMMV 应用源码、开发提交历史、签名密钥或构建凭据。公开下载不等于开放源码，也不授予 BMMV 原创代码的开源许可。应用所包含的第三方组件仍受各自许可证约束，其权利与声明不因本说明改变。

## 问题反馈

请在 [Issues](https://github.com/as7er/bmmv-releases/issues) 附上应用版本、手机型号、Android 版本、操作步骤、比赛节次/时间/比分，以及截图或录屏。不要上传账号凭据或个人敏感信息。
