---
title: "🎙️ 语音助手"
slug: "voice"
draft: false
ShowToc: false
---

<style>
  .voice-card {
    background: linear-gradient(135deg, #0f0c29 0%, #1a1a3e 100%);
    border: 2px solid #e94560;
    border-radius: 16px;
    padding: 30px;
    text-align: center;
    margin: 20px 0;
    box-shadow: 0 0 30px rgba(233, 69, 96, 0.15);
  }
  .voice-card h2 { color: #e94560 !important; font-size: 26px !important; margin-bottom: 10px !important; }
  .voice-card p { color: #aaa; font-size: 14px; line-height: 1.6; }
  .voice-link {
    display: inline-block;
    padding: 16px 48px;
    font-size: 22px;
    font-weight: bold;
    color: #fff !important;
    background: linear-gradient(135deg, #4fc3f7, #29b6f6);
    border-radius: 12px;
    text-decoration: none !important;
    margin: 16px 0;
    transition: all 0.3s;
    box-shadow: 0 4px 20px rgba(79,195,247,0.4);
    animation: glow 2s infinite;
  }
  @keyframes glow { 0%,100% { box-shadow: 0 4px 20px rgba(79,195,247,0.4); } 50% { box-shadow: 0 6px 35px rgba(79,195,247,0.7); } }
  .voice-link:hover { transform: scale(1.05); }
  .features-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 10px;
    margin: 20px 0;
  }
  .features-grid .feat {
    background: rgba(255,255,255,0.04);
    padding: 14px;
    border-radius: 10px;
    text-align: center;
  }
  .features-grid .feat .icon { font-size: 28px; margin-bottom: 4px; }
  .features-grid .feat .label { color: #ccc; font-size: 13px; }
  .note-box {
    background: rgba(233,69,96,0.08);
    border-left: 3px solid #e94560;
    padding: 12px 16px;
    border-radius: 0 8px 8px 0;
    margin: 15px 0;
    font-size: 13px;
    color: #aaa;
  }
  .note-box strong { color: #e94560; }
</style>

<div class="voice-card">
  <h2>🎙️ 语音助手</h2>
  <p>打字或语音，怎么方便怎么来</p>
  <p style="font-size:13px;color:#666">文字聊天 + 语音输入 + 语音回答</p>
  
  <a href="/seat-engineering/voice-assistant.html" class="voice-link" target="_blank">▶ 打开语音助手</a>
</div>

### ✨ 特色

<div class="features-grid">
  <div class="feat">
    <div class="icon">🎤</div>
    <div class="label">语音输入<br><span style="font-size:11px;color:#666">说中文就行</span></div>
  </div>
  <div class="feat">
    <div class="icon">🔊</div>
    <div class="label">语音回答<br><span style="font-size:11px;color:#666">自动朗读回复</span></div>
  </div>
  <div class="feat">
    <div class="icon">🤖</div>
    <div class="label">智能问答<br><span style="font-size:11px;color:#666">博客内容都认识</span></div>
  </div>
  <div class="feat">
    <div class="icon">📱</div>
    <div class="label">移动端适配<br><span style="font-size:11px;color:#666">手机也能用</span></div>
  </div>
</div>

### 💬 你可以问我

- 「介绍一下这个博客」
- 「有哪些文章？」
- 「游戏怎么玩？」
- 「小黑是谁？」
- 「座椅异响怎么办」
-……或者随便聊聊天

<div class="note-box">
<strong>💡 提示：</strong> 语音识别需要 Chrome 浏览器，首次使用会请求麦克风权限，允许即可。
</div>
