---
title: "🎮 跑酷射击小游戏"
slug: "game"
draft: false
ShowToc: false
---

<style>
  .game-card {
    background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
    border: 2px solid #e94560;
    border-radius: 16px;
    padding: 30px;
    text-align: center;
    margin: 20px 0;
    box-shadow: 0 0 30px rgba(233, 69, 96, 0.2);
  }
  .game-card h2 {
    color: #e94560 !important;
    font-size: 28px !important;
    margin-bottom: 10px !important;
  }
  .game-card p {
    color: #aaa;
    font-size: 15px;
    line-height: 1.6;
  }
  .play-btn {
    display: inline-block;
    padding: 16px 48px;
    font-size: 22px;
    font-weight: bold;
    color: #fff !important;
    background: linear-gradient(135deg, #e94560, #ff6b81);
    border-radius: 12px;
    text-decoration: none !important;
    margin: 20px 0;
    transition: all 0.3s;
    box-shadow: 0 4px 20px rgba(233, 69, 96, 0.4);
  }
  .play-btn:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 30px rgba(233, 69, 96, 0.6);
  }
  .controls-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 10px;
    margin: 20px 0;
    text-align: left;
  }
  .controls-grid .key-item {
    background: rgba(255,255,255,0.05);
    padding: 10px 15px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .controls-grid kbd {
    background: #333;
    padding: 4px 12px;
    border-radius: 5px;
    color: #fff;
    font-size: 14px;
    font-weight: bold;
    min-width: 40px;
    text-align: center;
    display: inline-block;
  }
  .game-tips {
    background: rgba(233, 69, 96, 0.08);
    border-left: 3px solid #e94560;
    padding: 12px 18px;
    border-radius: 0 8px 8px 0;
    margin: 15px 0;
    font-size: 14px;
    color: #ccc;
  }
</style>

<div class="game-card">
  <h2>🏃 跑酷射击</h2>
  <p>跳过障碍，射爆敌人，跑得更远！</p>
  <p>赛博朋克风格 · 二段跳 · 连击加分 · 难度递增</p>
  
  <a href="/seat-engineering/game.html" class="play-btn" target="_blank">▶ 开始游戏</a>
  
  <div class="game-tips">
    💡 新窗口打开体验更佳&nbsp;&nbsp;|&nbsp;&nbsp;⚡ 最高连击越高，单次得分越多
  </div>
</div>

### 🎮 操作说明

<div class="controls-grid">
  <div class="key-item"><kbd>←</kbd><kbd>→</kbd> 左右移动</div>
  <div class="key-item"><kbd>↑</kbd> / <kbd>Space</kbd> 跳跃（支持二段跳）</div>
  <div class="key-item"><kbd>J</kbd> / 点击画面 射击</div>
</div>

### 👾 敌人

| 类型 | 外观 | 特性 |
|------|------|------|
| 跑者 | 🔴 红色 | 地面冲刺，速度快 |
| 飞行怪 | 🟣 紫色 | 空中飘浮，两翼扇动 |
| 跳跃怪 | 🟢 绿色 | 2 条命，会跳起来砸你 |

### 🧱 障碍物
木箱、尖刺、铁桶——碰上去都会掉血！

---

<p style="text-align:center;color:#666;font-size:13px;margin-top:30px">
  用 Hugo + Canvas 做的纯前端小游戏 · 无需加载任何外部资源
</p>
