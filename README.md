# RPG游戏-麻将牌灵

<p align="center">
  <strong>麻将构筑 × 实时动作 Roguelite</strong><br>
  摸牌、听牌、和牌，然后把一整副麻将砸进战场。
</p>

<p align="center">
  <a href="https://zsrzzx.github.io/pai-ling-web/">
    <img src="https://img.shields.io/badge/%E2%96%B6_%E7%AB%8B%E5%8D%B3%E5%9C%A8%E7%BA%BF%E6%B8%B8%E7%8E%A9-E34263?style=for-the-badge" alt="立即在线游玩">
  </a>
  <img src="https://img.shields.io/badge/version-v0.13-8B5CF6?style=for-the-badge" alt="v0.13">
  <img src="https://img.shields.io/badge/engine-Godot_4.7-478CBF?style=for-the-badge&logo=godot-engine&logoColor=white" alt="Godot 4.7">
  <img src="https://img.shields.io/badge/platform-Desktop_Web-F59E0B?style=for-the-badge" alt="Desktop Web">
</p>

<p align="center">
  <a href="https://zsrzzx.github.io/pai-ling-web/"><strong>▶ 现在开玩</strong></a>
  ·
  <a href="https://github.com/ZSRZZX/pai-ling-web/issues">反馈问题</a>
</p>

<p align="center">
  <img src="docs/screenshots/title.jpg" alt="《RPG游戏-麻将牌灵》标题画面" width="920">
</p>

> **《RPG游戏-麻将牌灵》是一款把麻将构筑与双摇杆动作战斗揉在一起的 2D 俯视角 Roguelite。**
> 麻将在本作里不是换皮卡牌，而是你的武器、资源、成长路线和连招核心。

> [!IMPORTANT]
> 本仓库托管的是 **v0.13 HTML5 可玩构建**，不包含项目源码。推荐使用桌面版 Chrome 或 Edge 游玩，暂不支持移动端。

---

## 为什么值得玩

- **麻将真的参与战斗。** 万、饼、条与字牌会改变攻击、护盾、召唤物和特殊效果；构筑直接塑造手感。
- **听牌与和牌不是装饰。** 手牌满 13 张开始听牌，组成 14 张和牌后触发永久生效的强力奖励。
- **每一摸、每一打都在做取舍。** 每回合「摸 1 打 1」，既要追牌型，也要保住眼前这一波战斗。
- **短局循环，持续变强。** 每关 10 个回合，第 5 回合迎战小 Boss，第 10 回合迎战大 Boss，再带着牌魂进入下一轮。

---

## 核心循环

```text
选择角色与开局祝福
        ↓
进入 10 回合关卡
        ↓
实时战斗 → 摸 1 打 1 → 组成 13 张听牌
        ↓
和牌触发强化 → 宝箱 / 羁绊 / 经济构筑
        ↓
第 5 回合小 Boss → 第 10 回合大 Boss
        ↓
结算、局外成长、下一轮构筑
```

### 构筑与战斗

| 系统 | 作用 |
| --- | --- |
| 麻将牌池 | 34 种牌、每种 4 张，共 136 张；保留真实的牌张数量限制 |
| 摸与打 | 每回合摸 1 张、打 1 张，逐步把牌组推向目标牌型 |
| 听牌 | 手牌满 13 张且只差一张和牌时，获得听牌奖励 |
| 和牌 | 组成 14 张有效牌型，触发和牌效果并锁定强力构筑 |
| 羁绊 | 门派、字牌、牌型组合会提供额外的战斗能力 |
| 局外成长 | 完成挑战积累牌魂，解锁下一轮的开局优势 |

---

## 画面

<table>
  <tr>
    <td width="50%">
      <img src="docs/screenshots/loadout.jpg" alt="角色与开局构筑">
    </td>
    <td width="50%">
      <img src="docs/screenshots/battle.jpg" alt="实时战斗画面">
    </td>
  </tr>
  <tr>
    <td align="center"><sub>选择角色、武器与开局祝福</sub></td>
    <td align="center"><sub>一边走位一边把麻将打成火力</sub></td>
  </tr>
</table>

---

## 操作

| 按键 | 动作 |
| --- | --- |
| `WASD` | 移动 |
| 鼠标 | 瞄准 |
| 鼠标左键 | 攻击 / 连续挥砍 |
| `空格` | 冲刺（带无敌帧） |
| `Esc` | 暂停菜单 |

> 首次游玩建议先进入「剧情关卡」并打开游戏内「玩法说明」，会逐步介绍摸牌、听牌、和牌与回合规则。

---

## 当前版本

| 项目 | 内容 |
| --- | --- |
| 版本 | `v0.13` |
| 更新日期 | 2026-10-05 |
| 状态 | 可玩原型（Prototype） |
| 引擎 | Godot 4.7 |
| 发布形式 | HTML5 / WebAssembly |
| 托管 | GitHub Pages |
| 内容 | 章节剧情、自由对战、角色构筑、麻将牌组、Boss、商店与局外成长 |

### 已包含

- 2D 俯视角实时动作战斗
- 13 张听牌 / 14 张和牌判定
- 多角色、武器和开局祝福
- 普通、精英、限时与 Boss 关卡
- 宝箱、商店、任务 NPC 与羁绊系统
- 章节进度与局外成长
- 浏览器自动存档

---

## 关于这个仓库

这是《RPG游戏-麻将牌灵》的公开可玩版本，仓库根目录中的静态文件即 GitHub Pages 部署内容。

- **游玩地址：** https://zsrzzx.github.io/pai-ling-web/
- **问题反馈：** https://github.com/ZSRZZX/pai-ling-web/issues
- **源码状态：** 暂未公开

本仓库未附带开源许可证；游戏名称、美术、音频、玩法内容与构建产物版权归作者所有。

<p align="center">
  <sub>Made with Godot · Designed & developed by ZSRZZX</sub>
</p>
