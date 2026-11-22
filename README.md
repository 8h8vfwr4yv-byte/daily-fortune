# 每日一签

一个 12 KB 的安卓小应用：每天抽一支签，16 支签循环，带今日宜忌、解签和幸运数字。不联网、不申请任何权限。

- 安装包：`DailyFortune.apk`（也可去 Releases 页下载）
- 要求：安卓 7.0（API 24）以上
- 包名：`com.muse.dailyfortune`
- 大小：12,631 字节

## 源码

- `MainActivity.java` — 全部逻辑（原生 Java + Canvas 绘制，无第三方库）
- `AndroidManifest.xml`
- `build.sh` — 本地打包脚本（需要 JDK 17 和 Android build-tools 34）

## 玩法

打开点「抽一签」，每天的签由日期决定，一天内抽多少次都是同一支；点「再抽一次」可以随便抽着玩。
