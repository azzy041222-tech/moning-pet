# Good莫宁 · 晨间团子桌宠

![晨间团子](morning-dango-pet-transparent.png)

本仓库保存桌宠素材及动画配置。包含九种动画状态：待机、向右跑、向左跑、挥手、跳跃、失败、等待、奔跑和检查，以及十六个注视方向。

## 文件

- `pet.json`：桌宠 v2 配置，与同目录的 `spritesheet.webp` 配套使用。
- `spritesheet.webp`：包含动作和注视方向的透明动画精灵图。
- `spritesheet.png`：同一精灵图的 PNG 版本。
- `spritesheet-layout.json`：精灵图网格和十六个注视方向的位置。
- `animations.json`：九种动画的行号及有效帧数。
- `morning-dango-pet-transparent.png`：透明角色原图。

精灵图为 8 列 × 11 行，每格 192 × 208 像素。前九行对应动作，最后两行对应注视方向；配置行号从 0 开始。

## 使用

将 `pet.json` 和 `spritesheet.webp` 保持在同一目录，供支持此桌宠 v2 格式的客户端导入。其他桌宠程序可按网格和动作配置读取精灵图，导入方式取决于程序支持的格式。

本仓库是桌宠素材包，不包含独立桌面程序。
