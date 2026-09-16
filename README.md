# MaaHorizonWalker - 地平线行者自动化助手

MaaHorizonWalker 是基于 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 的、适用于游戏《地平线行者》的自动化工具。界面使用 [MFAAvalonia](https://github.com/MaaXYZ/MFAAvalonia)。

仓库地址：[haneruByte/MaaHorizonWalker](https://github.com/haneruByte/MaaHorizonWalker)

当前版本：**v0.1.0**（首次面向用户公开）

## 一、免责声明

- 本项目为个人兴趣开发的第三方工具，与游戏官方无任何关联
- 仅供学习与研究使用；使用本工具可能违反游戏用户协议或相关规则
- 因使用本工具导致的账号封禁、数据异常、进度丢失或任何其他后果，均由使用者自行承担
- 作者不对任何直接或间接损失负责

## 二、如何使用

### 2.1 环境要求

- Windows，推荐 [MuMu 模拟器](https://mumu.163.com/)
- 模拟器分辨率：**2208 × 1768**
- 控制器：**Android / Adb**（MFA 连上模拟器即可）
- 若提示缺少运行库，安装 [vc_redist](https://aka.ms/vs/17/release/vc_redist.x64.exe)

### 2.2 快速上手

1. 从 [Releases](https://github.com/haneruByte/MaaHorizonWalker/releases) 下载对应系统的压缩包并解压  
   Windows 一般选 `MaaHorizonWalker-win-x64`
2. 先打开模拟器，再运行解压目录下的 `MFAAvalonia.exe`
3. 控制器选择 **Android / Adb**，确认已识别到模拟器
4. 按需勾选任务、设置选项后开始运行

请先进入游戏主界面后再执行任务。

任务按列表从上到下依次执行。默认顺序：收菜 → 讨伐 → 裂缝探索 → 愿望 → 每日活动本 → 商店 → 活动日常任务 → 日常任务 → 收件箱（主线自动推进默认不勾选）。

### 2.3 功能说明

#### 进入游戏

唤起游戏、点继续、关闭公告。模拟器已开并连上 ADB 即可，游戏本身不用预先打开。已在主界面时会直接结束。

#### 收菜

从主界面进入并领取可收取的资源。请从主界面开始。

#### 讨伐

自动进入讨伐并挑战所选目标。可在选项里指定讨伐目标，默认 **优菲特尔**。

可选目标：织遍千里的织布机、游荡世间的微风、启示录四骑士、七瓣花骑士、永恒之战、灿烂大地的触碰、亡灵的宴会、协调、优菲特尔、罪孽清算、小丑面具、黎明的庇佑、生命的链接。

#### 裂缝探索

自动进入裂缝探索（周常）。可在选项里指定层数 **8F–15F**，默认 **8F**。

#### 商店

自动购买每日商店物品。每项可单独开/关：

- 购买礼物
- 购买 B 级契约券
- 购买 A 级契约券
- 购买 S 级契约券

#### 日常任务

领取并处理日常任务列表。

#### 每日活动本

进入每日活动本：签到、跳过剧情、处理战前对话、战斗结算，以及无法出击时的提示。

#### 主线自动推进

自动推进主线关卡。过程较长，请保证体力与编队可用。遇到无法处理的弹窗或新图时可能停下，把日志和截图发到 Issue 或群里即可。

#### 愿望

自动完成愿望相关流程。可在选项里指定目标，默认 **光辉币**。也可选护卫经验值、武器经验值。

#### 活动日常任务

处理当期活动页面中的日常任务。活动改版后界面若变化，可能需要更新资源。

#### 收件箱

进入邮箱并一键领取。

## 三、反馈与贡献

- [提交 Issue](https://github.com/haneruByte/MaaHorizonWalker/issues)
- QQ 交流群：`1076630349`

反馈时请尽量附上 `debug/maa.log`。若任务卡住，再附上对应时间附近的截图。

## 四、致谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！

1. [MaaFramework](https://github.com/MaaXYZ/MaaFramework)
2. [MFAAvalonia](https://github.com/MaaXYZ/MFAAvalonia)
