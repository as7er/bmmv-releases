# BMMV — 篮球经理

BMMV（Basketball Manager Mobile Vibe）的官方 Android 安装包发布仓库。

## 下载

- [全部版本与下载](https://github.com/as7er/bmmv-releases/releases)
- [当前预发布版：BMMV Android 1.0.0 build23 · ARM64](https://github.com/as7er/bmmv-releases/releases/tag/v1.0.0-preview.23)
- [直接下载 APK](https://github.com/as7er/bmmv-releases/releases/download/v1.0.0-preview.23/BMMV-Android-v1.0.0-build23-arm64-v8a.apk)
- [SHA-256 校验文件](https://github.com/as7er/bmmv-releases/releases/download/v1.0.0-preview.23/SHA256SUMS.txt)
- [上一公开正式包：build20](https://github.com/as7er/bmmv-releases/releases/tag/v1.0.0-preview.20)

无需 GitHub 账号即可下载。Release 附件不依赖 Expo 临时构建链接；只要仓库及附件保留，版本下载地址可继续使用。GitHub 服务可用性和本地网络情况可能影响访问。

APK 文件名采用“应用名-平台-v版本-build构建号-CPU架构”。本版仅提供 `arm64-v8a`，最低 Android 7.0（API 24），设备系统需支持 ARM64。旧 Universal APK 的文件名和链接保留。

## 安装与更新

1. 在 Android 手机浏览器下载 APK。
2. 打开文件；系统提示时，仅为用于下载的浏览器或文件管理器允许“安装未知应用”。
3. 安装后直接打开 BMMV，不需要 Expo Go、开发服务器或电脑，也不要求手机与电脑同一局域网。
4. 更新前在旧版“存档管理”中导出备份，再使用同包名、同签名的官方 APK 覆盖安装；不要先卸载，卸载或清除应用数据会丢失本地存档。

独立 APK 与 Expo Go、网页版的存档不共享，不会自动导入旧进度。建议首次安装创建测试联盟，保留原应用的数据。

## 当前状态

当前为预发布版，包含球队管理、自动排阵、赛季推进、2D 比赛直播、临场换人和战术、比赛进度保存恢复。

build23 放大竖屏观战：球场根据可用空间纵向展开，号码和名字保持正向，边缘标签防裁切；比分栏和底部控制区更紧凑，解说可点开查看全部记录。也包含 build20 之后的赛前快速模拟、赛后继续赛程、财务／交易／阵容界面整理及发球退防、战术转换修复。

包名 `com.as7er.bmmv`，`versionCode=23`，沿用原正式签名，可覆盖正式 build20 或本地 build22。localtest 为独立应用，其存档需要手动导出／导入。联赛存档格式仍为 v7；新版导出文件不保证可回导旧 APK。

本地 lint、类型检查、59 个套件／801 项应用测试与 13 项签名回归通过。APK 的签名、ARM64、非调试配置、Hermes 与音效资源均已核验；公开附件经匿名下载后复核。没有新增 Android 真机覆盖安装、旧档读取或原生竖屏验收记录，请保留外部存档备份。

建议检查：导出存档 → 覆盖安装 → 断网冷启动 → 竖屏观战 → 切换横竖屏 → 保存离开并继续 → 切后台／锁屏 → 强退重开 → 终场保存 → 继续赛程。

## 发布范围

本仓库仅公开安装包、校验文件与使用/版本说明，不包含 BMMV 应用源码、开发提交历史、签名密钥或构建凭据。公开下载不等于开放源码，也不授予 BMMV 原创代码的开源许可。应用所包含的第三方组件仍受各自许可证约束，其权利与声明不因本说明改变。

## 问题反馈

请在 [Issues](https://github.com/as7er/bmmv-releases/issues) 附上应用版本、手机型号、Android 版本、操作步骤、比赛节次/时间/比分，以及截图或录屏。不要上传账号凭据或个人敏感信息。
