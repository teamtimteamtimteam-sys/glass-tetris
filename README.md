# 玻璃方块 · Pixel Edition

iPhone 上玩的经典像素风落块游戏（PWA）。Safari 打开后「分享 → 添加到主屏幕」即可全屏、离线游玩。

- 10×20、7 种方块、7-Bag、SRS 旋转；18 级渐进速度（900ms → 30ms/格）
- 操作：左下旋转，右下 ← →（DAS/ARR 可调）；游戏区下滑按住 = 加速，快速下划 = 直落，点 HOLD 区交换
- Combo、Back-to-Back、Perfect Clear；锁定延迟 300ms、最多重置 10 次
- 模式：PLAY / DAILY（每日同一种子，5 分钟）/ SURVIVAL 18（PLAY 到达 18 级后解锁）
- 输入在事件里即时生效，与重力、动画解耦；所有特效都不阻塞操作

单文件 `index.html`，字体 Press Start 2P（OFL）。改动后记得把 `sw.js` 里的 `CACHE` 版本号加一。
