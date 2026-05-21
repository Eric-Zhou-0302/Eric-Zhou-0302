<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Eric Zhou</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
      max-width: 860px;
      margin: 0 auto;
      padding: 40px 20px;
      line-height: 1.7;
    }
    a { color: #58a6ff; text-decoration: none; }
    a:hover { text-decoration: underline; }

    .lang-switch {
      text-align: right;
      margin-bottom: 32px;
      font-size: 14px;
    }
    .lang-switch button {
      background: none;
      border: 1px solid #30363d;
      color: #8b949e;
      padding: 4px 12px;
      border-radius: 6px;
      cursor: pointer;
      margin-left: 4px;
      transition: all 0.2s;
    }
    .lang-switch button:hover { border-color: #58a6ff; color: #c9d1d9; }
    .lang-switch button.active {
      background: #238636;
      border-color: #238636;
      color: #fff;
    }

    .section { margin-bottom: 36px; }

    h1 {
      font-size: 36px;
      margin-bottom: 12px;
      color: #f0f6fc;
    }
    .subtitle {
      font-size: 18px;
      color: #8b949e;
      margin-bottom: 24px;
    }

    h2 {
      font-size: 20px;
      color: #f0f6fc;
      margin-bottom: 12px;
      padding-bottom: 6px;
      border-bottom: 1px solid #30363d;
    }

    .project-card {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 6px;
      padding: 20px 24px;
      margin-bottom: 12px;
    }
    .project-card h3 { color: #f0f6fc; font-size: 16px; margin-bottom: 6px; }
    .project-card p { font-size: 14px; color: #8b949e; }
    .project-tags { margin-top: 10px; }
    .tag {
      display: inline-block;
      background: #1f6feb26;
      color: #79c0ff;
      font-size: 12px;
      padding: 2px 8px;
      border-radius: 12px;
      margin-right: 6px;
    }

    .footer {
      margin-top: 48px;
      font-size: 13px;
      color: #484f58;
      border-top: 1px solid #21262d;
      padding-top: 16px;
    }

    .lang-content { display: none; }
    .lang-content.active { display: block; }

    .en { direction: ltr; text-align: left; }
    .zh { direction: ltr; text-align: left; }
  </style>
</head>
<body>

<div class="lang-switch">
  <span class="lang-label">🌐</span>
  <button class="lang-btn active" data-lang="zh">中文</button>
  <button class="lang-btn" data-lang="en">English</button>
</div>

<!-- Chinese -->
<div class="lang-content zh active">
  <div class="section">
    <h1>Eric Zhou</h1>
    <p class="subtitle">量化研究 / 交易系统开发</p>
  </div>

  <div class="section">
    <h2>🛠️ 技术栈</h2>
    <p><strong>编程语言：</strong>Python</p>
    <p><strong>数据分析：</strong>Polars · NumPy · Pandas</p>
    <p><strong>专业领域：</strong>量化交易 · Walk-Forward 分析 · 均值回归策略</p>
  </div>

  <div class="section">
    <h2>📂 核心项目</h2>
    <div class="project-card">
      <h3>📊 Walk-Forward Reverse Crypto</h3>
      <p>基于 VWAP 的加密货币均值回归策略回测框架。通过 Walk-Forward 滚动优化方法进行参数寻优，严格遵循训练集 → 验证集 → 测试集的三段式 out-of-sample 验证流程，有效规避前视偏差与过拟合。</p>
      <div class="project-tags">
        <span class="tag">Python</span>
        <span class="tag">Polars</span>
        <span class="tag">NumPy</span>
        <span class="tag">多进程批量回测</span>
        <span class="tag">HTML报告</span>
      </div>
      <p style="margin-top:8px; font-size:13px;">
        🔗 <a href="https://github.com/Eric-Zhou-0302/Walk-Forward_Reverse_Crypto">Eric-Zhou-0302/Walk-Forward_Reverse_Crypto</a>
      </p>
    </div>
  </div>

  <div class="section">
    <h2>📈 研究方向</h2>
    <p>资产定价 · 因子分析 · 量化交易策略</p>
  </div>

  <div class="footer">
    最近更新：2026.05
  </div>
</div>

<!-- English -->
<div class="lang-content en">
  <div class="section">
    <h1>Eric Zhou</h1>
    <p class="subtitle">Quantitative Research & Trading System Development</p>
  </div>

  <div class="section">
    <h2>🛠️ Tech Stack</h2>
    <p><strong>Languages:</strong> Python</p>
    <p><strong>Data:</strong> Polars · NumPy · Pandas</p>
    <p><strong>Fields:</strong> Quantitative Trading · Walk-Forward Analysis · Mean Reversion Strategies</p>
  </div>

  <div class="section">
    <h2>📂 Key Projects</h2>
    <div class="project-card">
      <h3>📊 Walk-Forward Reverse Crypto</h3>
      <p>A cryptocurrency mean reversion strategy backtesting framework based on VWAP. Uses Walk-Forward rolling optimization for parameter search with strict out-of-sample validation across training / validation / test sets. Effectively avoids look-ahead bias and overfitting.</p>
      <div class="project-tags">
        <span class="tag">Python</span>
        <span class="tag">Polars</span>
        <span class="tag">NumPy</span>
        <span class="tag">Multi-process Backtesting</span>
        <span class="tag">HTML Reports</span>
      </div>
      <p style="margin-top:8px; font-size:13px;">
        🔗 <a href="https://github.com/Eric-Zhou-0302/Walk-Forward_Reverse_Crypto">Eric-Zhou-0302/Walk-Forward_Reverse_Crypto</a>
      </p>
    </div>
  </div>

  <div class="section">
    <h2>📈 Research Interests</h2>
    <p>Asset Pricing · Factor Analysis · Quantitative Trading Strategies</p>
  </div>

  <div class="footer">
    Last updated: 2026.05
  </div>
</div>

<script>
  const buttons = document.querySelectorAll('.lang-btn');
  const contents = document.querySelectorAll('.lang-content');

  buttons.forEach(btn => {
    btn.addEventListener('click', () => {
      const lang = btn.dataset.lang;

      buttons.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');

      contents.forEach(c => {
        c.classList.remove('active');
        if (c.classList.contains(lang)) c.classList.add('active');
      });
    });
  });
</script>

</body>
</html>