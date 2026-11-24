---
layout: home
---

<style>
.game-library { margin: 0 0 2.5rem; color: #eef2ff; background: #141b2b; padding: clamp(1rem, 4vw, 2rem); border-radius: 1rem; }
.game-library h1 { margin: 0 0 .35rem; color: #fff; font-size: clamp(1.6rem, 5vw, 2.25rem); line-height: 1.25; }
.game-library > p { margin: 0 0 1.4rem; color: #cbd5e1; }
.game-grid { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: .75rem; }
.game-library .game-card { display: flex; flex-direction: column; padding: 1rem; border: 1px solid #43516a; border-radius: .75rem; background: #202a3d; color: #f8fafc; text-decoration: none; }
.game-library .game-card:hover, .game-library .game-card:focus-visible { border-color: var(--accent); background: #29364d; color: #fff; text-decoration: none; }
.game-library .game-card:focus-visible { outline: 3px solid var(--accent); outline-offset: 3px; }
.game-card h2 { font-size: 1.2rem; line-height: 1.4; margin: 0 0 .5rem; color: inherit; }
.game-card p { margin: 0 0 1rem; color: #cbd5e1; font-size: .9375rem; }
.game-icon, .game-action { color: var(--accent); }
.game-icon { font-size: 1.5rem; margin-bottom: .65rem; }
.game-action { margin-top: auto; font-size: .9rem; font-weight: bold; }
@media (max-width: 620px) { .game-grid { grid-template-columns: 1fr; } }
</style>

<section class="game-library" lang="zh-CN" aria-labelledby="game-library-title">
  <h1 id="game-library-title">我的网页游戏</h1>
  <p>选一款游戏，直接在浏览器里玩。</p>
  <div class="game-grid">
    <a class="game-card" href="/50days/" style="--accent: #f4c785">
      <span class="game-icon" aria-hidden="true">🔥</span>
      <h2>五十日坚守</h2>
      <p>回合制生存策略。分配资源，应对危机，撑过五十天。</p>
      <span class="game-action" aria-hidden="true">开始游戏</span>
    </a>
    <a class="game-card" href="/sologame/" style="--accent: #9fe0cf">
      <span class="game-icon" aria-hidden="true">🎲</span>
      <h2>桌游收藏家</h2>
      <p>收集和管理桌游，体验从玩家到桌游设计师的经营过程。</p>
      <span class="game-action" aria-hidden="true">开始游戏</span>
    </a>
    <a class="game-card" href="/castle_rush/" style="--accent: #c6bcff">
      <span class="game-icon" aria-hidden="true">🏰</span>
      <h2>城堡突袭</h2>
      <p>单人策略卡牌游戏。调配手牌与物资，逐层攻破城堡。</p>
      <span class="game-action" aria-hidden="true">开始游戏</span>
    </a>
  </div>
</section>
