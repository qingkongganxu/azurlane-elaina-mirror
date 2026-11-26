# Mirror notice / 镜像说明

本仓库保存的是 AzurLane_Elaina（项目自称 YLN，二次开发名 Elaina）的构建分发仓库。

## 代码

- 上游构建仓：`azzzddddd/Azurlane_Elaina`，fork 自 `elaina-al/AL`；后者现已 404，本仓库因此保留一份完整副本（含全部提交历史与标签）。
- 上游更早的源仓库：`elaina-al/AL`（已删除）；另有 `ElainaAL/ElainaAL` 仍在维护。
- 本项目与 `JMBQ/azurlane`（Azur Lane MOD MENU）同源于 `Egoistically/Perseus` 与 `4pii4/PiePerseus`，但属于不同二次开发，配置方式为修改 `Elaina.json`，无游戏内悬浮菜单。

## 成品

- 来源：`azzzddddd/Azurlane_Elaina` 的 Release `3.7.2-APK`（对应游戏客户端 9.7.25）。
- 本仓库只复刻两个渠道：B 站服（`bilibili-V.9.7.25.7z.001` 800 MB + `.002` 640 MB）与应用宝（`yingyongbao-V.9.7.25.7z.001` 800 MB + `.002` 565 MB）。
- 解压：两个分卷放同一目录，用 7-Zip 打开 `.001` 合并解压，不要单独处理 `.002`。

## 同步

`.github/workflows/mirror.yml` 手动触发，参数为源码仓、发布仓、标签、资产通配符。重跑会强制对齐上游代码并覆盖同名资产。