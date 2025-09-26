<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Celeste (Claire) Wang — Data & Business Analytics</title>
  <meta name="description" content="Portfolio of Celeste (Claire) Wang — Data & Business Analyst. SQL, Python, Power BI, Tableau. Growth & KPI dashboards, churn analysis, funnel analytics." />
  <meta name="author" content="Celeste (Claire) Wang" />
  <link rel="canonical" href="https://alnx.tech/" />
  
  <!-- Open Graph -->
  <meta property="og:title" content="Celeste (Claire) Wang — Data & Business Analytics" />
  <meta property="og:description" content="SQL · Python · Power BI · Tableau | Growth & KPI Insights | Portfolio & Contact" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://alnx.tech/" />
  <meta property="og:image" content="https://alnx.tech/og-image.jpg" />

  <!-- JSON-LD: Person -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Celeste (Claire) Wang",
    "jobTitle": "Data & Business Analyst",
    "url": "https://alnx.tech/",
    "sameAs": [
      "https://www.linkedin.com/in/",
      "https://github.com/"
    ]
  }
  </script>

  <style>
    :root {
      --bg: #0b0b0c;         /* black-gold aesthetic */
      --panel: #121214;
      --text: #e8e6e3;
      --muted: #b3aea6;
      --gold: #d4af37;
      --accent: #8dc6ff;
      --card: #161618;
      --shadow: 0 10px 30px rgba(0,0,0,0.35);
      --radius: 16px;
    }
    * { box-sizing: border-box; }
    html, body { margin: 0; padding: 0; font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji"; }
    body { background: linear-gradient(180deg, var(--bg), #0e0e10 60%, #0b0b0c); color: var(--text); }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .container { max-width: 1040px; margin: 0 auto; padding: 28px 20px 80px; }

    /* Header */
    header { display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 12px 0 24px; position: sticky; top: 0; background: rgba(11,11,12,0.7); backdrop-filter: blur(8px); z-index: 10; }
    .brand { display: flex; align-items: center; gap: 14px; }
    .logo { width: 40px; height: 40px; border-radius: 50%; background: radial-gradient(circle at 30% 30%, var(--gold), #8e793e 60%, #403617); box-shadow: inset 0 0 20px rgba(0,0,0,0.4), var(--shadow); }
    .title { font-size: 18px; letter-spacing: 0.4px; font-weight: 600; }
    nav { display: flex; gap: 18px; }
    nav a { color: var(--text); opacity: 0.9; }

    /* Hero */
    .hero { display: grid; grid-template-columns: 1.1fr 0.9fr; gap: 28px; align-items: center; padding: 14px 0 28px; }
    .hero h1 { font-size: clamp(28px, 4vw, 44px); line-height: 1.15; margin: 0 0 14px; }
    .hero p { color: var(--muted); font-size: 18px; margin: 0 0 20px; }
    .badge { display: inline-block; padding: 6px 12px; border: 1px solid rgba(212,175,55,0.4); color: var(--gold); border-radius: 999px; font-size: 12px; letter-spacing: .6px; text-transform: uppercase; margin-bottom: 14px; }
    .card { background: linear-gradient(180deg, var(--card), #151418); border: 1px solid rgba(255,255,255,0.06); border-radius: var(--radius); box-shadow: var(--shadow); padding: 20px; }
    .hero .card { min-height: 220px; }
    .kpilist { display: grid; grid-template-columns: repeat(3, 1fr); gap: 14px; }
    .kpi { background: #141418; border: 1px solid rgba(255,255,255,0.06); border-radius: 14px; padding: 14px; }
    .kpi h3 { margin: 2px 0 4px; font-size: 22px; color: var(--gold); }
    .kpi p { margin: 0; color: var(--muted); font-size: 12px; }

    /* Sections */
    section { margin-top: 48px; }
    h2 { font-size: 22px; letter-spacing: .5px; margin: 0 0 14px; }
    .grid { display: grid; grid-template-columns: repeat(12, 1fr); gap: 16px; }
    .col-6 { grid-column: span 6; }
    .col-4 { grid-column: span 4; }
    .pill { display: inline-block; padding: 8px 12px; border: 1px solid rgba(255,255,255,0.08); border-radius: 999px; margin: 6px 8px 0 0; font-size: 12px; color: var(--muted); }
    .proj { padding: 18px; border: 1px solid rgba(255,255,255,0.08); border-radius: var(--radius); background: #141418; }
    .proj h3 { margin: 0 0 8px; font-size: 18px; }
    .proj p { margin: 0 0 10px; color: var(--muted); }
    .proj a.btn { display:inline-block; padding: 8px 12px; border: 1px solid rgba(255,255,255,0.15); border-radius: 10px; }

    /* Footer */
    footer { margin-top: 56px; padding-top: 24px; border-top: 1px solid rgba(255,255,255,0.08); color: var(--muted); font-size: 13px; display:flex; justify-content: space-between; align-items: center; }
    .social { display:flex; gap: 10px; }
    .social a { color: var(--text); opacity: 0.9; border: 1px solid rgba(255,255,255,0.12); padding: 6px 10px; border-radius: 999px; }

    @media (max-width: 860px) {
      .hero { grid-template-columns: 1fr; }
      .kpilist { grid-template-columns: 1fr; }
      .grid { grid-template-columns: 1fr; }
      .col-6, .col-4 { grid-column: span 1; }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden="true"></div>
        <div class="title">Celeste (Claire) Wang</div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div>
        <span class="badge">Data & Business Analytics</span>
        <h1>SQL · Python · Power BI · Tableau — Turning data into growth & clear decisions.</h1>
        <p>
          I build KPI & funnel dashboards, churn models, and automated reporting that help teams
          spot bottlenecks fast and act with confidence. Previously at Baidu (商业分析) and now at Nurex Link LLC (SaaS/BI), integrating 180+ data sources and improving tracked conversion by ~35%.
        </p>
        <div class="kpilist">
          <div class="kpi"><h3>180+</h3><p>Integrated data sources</p></div>
          <div class="kpi"><h3>~35%</h3><p>Conversion lift tracked</p></div>
          <div class="kpi"><h3>&lt; 2h</h3><p>Refresh latency (BI)</p></div>
        </div>
      </div>
      <div class="card">
        <h2 style="margin-top:0">Highlights</h2>
        <ul>
          <li>Built growth KPI dashboard (MAU, DAU, funnel, anomaly alerts) — reduced weekly prep from 6h to 10m.</li>
          <li>Designed SQL models with CTEs & window functions for cohorts, retention, and incremental loads.</li>
          <li>Partnered with Marketing/BD to translate insights into experiments and wins.</li>
        </ul>
        <p style="margin-top:10px;color:var(--muted)">Resume available on request.</p>
      </div>
    </section>

    <section id="about">
      <h2>About</h2>
      <div class="grid">
        <div class="col-6 card">
          <p>
            我专注把<span style="color:var(--gold)">复杂数据 → 清晰指标 → 可执行方案</span>。
            在百度做商业分析时支持广告与增长，在 Nurex 负责 BI 数据模型与仪表盘；
            熟悉自上而下的 KPI 设计、跨部门协作与指标落地。
          </p>
          <p>
            近期关注：自动化数据质量监控、转化漏斗归因、留存与分群、及 AI 辅助分析。
          </p>
        </div>
        <div class="col-6 card">
          <h3 style="margin-top:0">Focus Areas</h3>
          <ul>
            <li>Growth analytics (acquisition, activation, retention, revenue)</li>
            <li>Funnel & cohort analysis, churn modeling</li>
            <li>Power BI/Tableau dashboards & automated refresh</li>
            <li>SQL data modeling, data quality checks, documentation</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="card">
        <span class="pill">SQL (Postgres/MySQL)</span>
        <span class="pill">Python (Pandas, NumPy)</span>
        <span class="pill">Power BI</span>
        <span class="pill">Tableau</span>
        <span class="pill">Excel (Pivot, PowerQuery)</span>
        <span class="pill">Data Modeling</span>
        <span class="pill">Cohort/Retention</span>
        <span class="pill">Funnel Analytics</span>
        <span class="pill">A/B basics</span>
        <span class="pill">Stakeholder Comms</span>
      </div>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="grid">
        <div class="col-4 proj">
          <h3>Growth KPI Dashboard</h3>
          <p>MAU/DAU, funnel steps, anomaly alerts. Scheduled refresh &lt; 2h.</p>
          <a class="btn" href="#" aria-disabled="true">Screenshot (on request)</a>
        </div>
        <div class="col-4 proj">
          <h3>Churn Analysis (MBA)</h3>
          <p>Python + SQL 合并 5 个数据集，训练逻辑回归，输出可执行分群。</p>
          <a class="btn" href="#" aria-disabled="true">Notebook summary</a>
        </div>
        <div class="col-4 proj">
          <h3>Attribution Funnel</h3>
          <p>CTE + window functions 计算 7/30 天转化与归因，驱动 ~35% 提升。</p>
          <a class="btn" href="#" aria-disabled="true">Key SQL (redacted)</a>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="card">
        <p style="margin:0 0 8px">Email: <a href="mailto:clairesiwang@alphalink.com">clairesiwang@alphalink.com</a></p>
        <p style="margin:0 0 8px">GitHub: <a href="https://github.com/clairesiwang" target="_blank" rel="noopener">github.com/clairesiwang</a></p>
        <p style="margin:0">LinkedIn: <a href="https://www.linkedin.com/in/" target="_blank" rel="noopener">linkedin.com/in/</a></p>
      </div>
    </section>

    <footer>
      <div>© <span id="y"></span> Celeste (Claire) Wang · alnx.tech</div>
      <div class="social">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </footer>
  </div>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>

