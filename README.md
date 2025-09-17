[elizabeth_club_index.html](https://github.com/user-attachments/files/22396080/elizabeth_club_index.html)
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elizabeth 美股俱乐部</title>
  <style>
    body {font-family: Arial, sans-serif; margin:0; padding:0; background:#f9fafb; color:#111;}
    header, footer {background:#fff; border-bottom:1px solid #e5e7eb; padding:1rem 2rem; display:flex; align-items:center; justify-content:space-between; position:sticky; top:0;}
    header h1 {font-size:1.2rem; margin:0;}
    nav a {margin-left:1rem; text-decoration:none; color:#2563eb;}
    .hero {padding:3rem 2rem; text-align:center;}
    .hero h2 {font-size:2rem; margin-bottom:1rem;}
    .links {display:grid; grid-template-columns:repeat(auto-fit, minmax(220px,1fr)); gap:1rem; padding:2rem; max-width:900px; margin:0 auto;}
    .card {background:#fff; border:1px solid #e5e7eb; border-radius:0.5rem; padding:1rem; text-align:center; transition:box-shadow 0.3s;}
    .card:hover {box-shadow:0 2px 8px rgba(0,0,0,0.1);}
    .card a {display:inline-block; margin-top:0.5rem; color:#2563eb; text-decoration:none;}
    section {padding:2rem; max-width:900px; margin:0 auto;}
    h3 {margin-bottom:0.5rem;}
    footer {border-top:1px solid #e5e7eb; border-bottom:none; justify-content:center;}
    footer p {font-size:0.8rem; color:#6b7280; margin:0;}
  </style>
</head>
<body>
  <header>
    <h1>Elizabeth 美股俱乐部</h1>
    <nav>
      <a href="#links">快速入口</a>
      <a href="#about">关于</a>
      <a href="#disclaimer">免责声明</a>
    </nav>
  </header>

  <section class="hero">
    <h2>欢迎加入 Elizabeth 美股俱乐部</h2>
    <p>专注美股教育与社区交流：盘前要点、日内节奏、支撑/阻力、风险管理与合规提醒。</p>
  </section>

  <section id="links" class="links">
    <div class="card">
      <h3>Discord 社区</h3>
      <p>加入讨论和交流。</p>
      <a href="https://discord.gg/your-server" target="_blank">进入 Discord</a>
    </div>
    <div class="card">
      <h3>Patreon 会员</h3>
      <p>获取独家内容和支持。</p>
      <a href="[https://patreon.com/your-page](https://www.patreon.com/xxxHolicEliza?utm_campaign=creatorshare_creator)" target="_blank">访问 Patreon</a>
    </div>
    <div class="card">
      <h3>YouTube 频道</h3>
      <p>观看教学视频与市场解读。</p>
      <a href="https://youtube.com/@your-channel" target="_blank">前往 YouTube</a>
    </div>
  </section>

  <section id="about">
    <h3>关于俱乐部</h3>
    <p>我们专注美股市场的教育内容与交流，涵盖指数节奏、技术关口、宏观日程，以及社区成员的经验分享。欢迎新手与进阶交易者共同学习。</p>
    <p>平台为学习型社区，不提供个股或衍生品的买卖建议。请根据自身风险承受能力，独立做出决策。</p>
  </section>

  <section id="disclaimer">
    <h3>免责声明</h3>
    <p>本网站与社区所提供的所有信息仅用于学习与交流，不构成任何投资建议或买卖推荐。证券与期权交易具有高风险，可能导致资金部分或全部损失。请谨慎评估并自行承担责任。</p>
  </section>

  <footer>
    <p>© <span id="year"></span> Elizabeth US Stocks Club. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
