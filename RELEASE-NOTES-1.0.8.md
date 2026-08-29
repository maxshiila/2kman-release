# MAN 1.0.8

## 新功能

- 篮球27街球之王新增第二场地「山谷公园」：在正式端「场地」选择器直接切换，无需更换配置包；山谷公园没有底线白线，随场配备专门的人群线+绿色油漆起始识别与攻防标定，定位稳定。
- 篮球27开放球场新增「左底角beta」投篮档位：近投走左底角斜边路线，接近向带中心收敛、按距离与速度分档横向回中，停位更稳；原远投/近投两档不变。
- 街球之王传球收尾方式可选：传球链收尾支持三角/闪传/空接；传球风格在对局运行中实时切换、立即生效。
- 渠道邀请码上线：新增 2KC-XXXXX 渠道码（与个人 2KM 码并行），仅首次激活可用、与安装绑定；激活弹窗支持一键复制推广文案。

## 修复与优化

- Windows 安装器老用户一键升级：检测到已安装的 MAN 自动跳过许可、目录等页面，一键装回原目录；开始菜单与桌面快捷方式默认创建。
- 连接问题自愈+诊断：串流 UDP 被防火墙拦截时自动补放行规则并重试；连接彻底失败时直接给出根因；新增双击即用的 Xbox 连接诊断工具（自动保存诊断报告）。
- 街球传球循环更合理：传球循环只在攻守转换时结束；传球与走位的回拉动作改为一次脉冲后等待位置回读，不再互相打断。
- 更新弹窗体验修正：更新检查优先走自托管镜像线路；公告区更高、按钮悬停反馈修正。
- 激活提示更明确：首单卡在已激活过任意卡密的设备上使用时，直接提示「首单卡仅限未在本设备激活过任何卡密时使用」。
- 界面细节：参数区数值框单列网格对齐、单位紧贴数字；延迟输入框方向键调整后自动释放焦点。
- 安装包更干净：投篮测试链等源码态调参工具退出正式包；裁剪随包无用构建文件约 3.3MB。

## 配置包更新

- 篮球27街球之王（0.0.32）：新增山谷公园场地；传球区域按实机反馈上移 110px。
- 篮球27开放球场（0.0.29）、篮球26开放球场（0.0.7）、篮球26街球之王（0.0.9）随包更新。

## New features

- **Basketball 27 Streetball King: new "Valley Park" court** — switch directly from the court selector, no package change needed. Valley Park has no baseline line; it ships with dedicated crowd-line + green-paint top-row detection and possession calibration.
- **Basketball 27 Open Court: new "左底角beta" (left-corner beta) shot tier** — near shots route through the left-corner sideline, converging on the band center with distance/speed-scaled lateral taps. The existing far/near tiers are unchanged.
- **Streetball pass finisher options** — end the pass chain with triangle / flash pass / alley-oop; pass style is live-tunable mid-session.
- **Channel invite codes** — 2KC-XXXXX codes alongside personal 2KM codes, first-activation only, install-bound, with one-click promo copy in the activation popup.

## Fixes

- One-click upgrade for existing installs in the Windows installer; start-menu and desktop shortcuts are now created by default.
- Firewall self-heal when streaming UDP is blocked, root-cause messages on terminal reconnect failures, and a double-click Xbox connection diagnostic.
- Pass loops now end only on possession change; pull-back pulses wait for a fresh position read instead of interrupting each other.
- Clearer first-order-card eligibility error; update prompt improvements (self-hosted mirror first, taller notes area).
- Cleaner installer: source-only tuning tools removed from frozen builds and ~3.3MB of wheel build artifacts stripped.
