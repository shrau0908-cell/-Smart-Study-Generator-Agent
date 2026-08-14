
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Smart Study Generator Agent</title>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #ffffff;
      --surface: #f7f8fa;
      --border: #e5e7eb;
      --text: #1f2328;
      --muted: #57606a;
      --accent: #3b82d4;
      --secondary: #7c5cd8;
      --accent-light: #eff6ff;
      --secondary-light: #f5f0ff;
      --radius: 12px;
      --font: -apple-system, "Segoe UI", system-ui, sans-serif;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: var(--font);
      font-size: 15px;
      line-height: 1.6;
      color: var(--text);
      background: var(--bg);
    }

    /* ── NAV ── */
    nav {
      position: sticky;
      top: 0;
      z-index: 100;
      background: var(--bg);
      border-bottom: 1px solid var(--border);
      padding: 0 32px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      height: 60px;
    }
    .nav-brand {
      display: flex;
      align-items: center;
      gap: 10px;
      font-weight: 700;
      font-size: 17px;
      color: var(--text);
      text-decoration: none;
    }
    .nav-brand .brand-icon {
      width: 32px; height: 32px;
      background: var(--accent);
      border-radius: 8px;
      display: flex; align-items: center; justify-content: center;
    }
    .nav-brand .brand-icon svg { width: 18px; height: 18px; fill: #fff; }
    .nav-links {
      display: flex;
      gap: 24px;
      list-style: none;
    }
    .nav-links a {
      text-decoration: none;
      color: var(--muted);
      font-size: 14px;
      font-weight: 500;
    }
    .nav-links a:hover { color: var(--accent); }
    .nav-cta {
      background: var(--accent);
      color: #fff;
      border: none;
      padding: 8px 18px;
      border-radius: 8px;
      font-size: 14px;
      font-weight: 600;
      cursor: pointer;
      text-decoration: none;
    }
    .nav-cta:hover { background: #2563c0; }

    /* ── HERO ── */
    .hero {
      max-width: 760px;
      margin: 0 auto;
      padding: 72px 24px 56px;
      text-align: center;
    }
    .hero-badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: var(--accent-light);
      color: var(--accent);
      border: 1px solid #bfdbfe;
      border-radius: 20px;
      padding: 4px 14px;
      font-size: 12px;
      font-weight: 600;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      margin-bottom: 20px;
    }
    .hero h1 {
      font-size: clamp(28px, 5vw, 44px);
      font-weight: 800;
      line-height: 1.2;
      color: var(--text);
      margin-bottom: 16px;
    }
    .hero h1 span { color: var(--accent); }
    .hero p {
      font-size: 16px;
      color: var(--muted);
      max-width: 560px;
      margin: 0 auto 32px;
    }
    .hero-actions {
      display: flex;
      gap: 12px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .btn-primary {
      background: var(--accent);
      color: #fff;
      padding: 12px 28px;
      border-radius: 10px;
      font-weight: 700;
      font-size: 15px;
      text-decoration: none;
      border: none;
      cursor: pointer;
      display: inline-flex;
      align-items: center;
      gap: 8px;
    }
    .btn-primary:hover { background: #2563c0; }
    .btn-outline {
      background: var(--bg);
      color: var(--text);
      padding: 12px 28px;
      border-radius: 10px;
      font-weight: 600;
      font-size: 15px;
      text-decoration: none;
      border: 1px solid var(--border);
      cursor: pointer;
      display: inline-flex;
      align-items: center;
      gap: 8px;
    }
    .btn-outline:hover { border-color: var(--accent); color: var(--accent); }

    /* ── STATS STRIP ── */
    .stats-strip {
      background: var(--surface);
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
      padding: 20px 24px;
    }
    .stats-inner {
      max-width: 760px;
      margin: 0 auto;
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      gap: 16px;
    }
    .stat { text-align: center; }
    .stat-value {
      font-size: 22px;
      font-weight: 800;
      color: var(--accent);
    }
    .stat-label {
      font-size: 12px;
      color: var(--muted);
      margin-top: 2px;
    }

    /* ── SECTION WRAPPER ── */
    .section {
      max-width: 760px;
      margin: 0 auto;
      padding: 56px 24px;
    }
    .section-header {
      text-align: center;
      margin-bottom: 36px;
    }
    .section-header h2 {
      font-size: 26px;
      font-weight: 800;
      margin-bottom: 8px;
    }
    .section-header p {
      color: var(--muted);
      font-size: 15px;
    }

    /* ── FEATURES GRID ── */
    .features-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 16px;
    }
    .feature-card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 24px 20px;
      transition: border-color 0.2s;
    }
    .feature-card:hover { border-color: var(--accent); }
    .feature-icon {
      width: 44px; height: 44px;
      border-radius: 10px;
      display: flex; align-items: center; justify-content: center;
      margin-bottom: 14px;
      font-size: 20px;
    }
    .feature-card h3 {
      font-size: 15px;
      font-weight: 700;
      margin-bottom: 6px;
    }
    .feature-card p {
      font-size: 13px;
      color: var(--muted);
      line-height: 1.5;
    }

    /* ── HOW IT WORKS ── */
    .steps {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .step {
      text-align: center;
      padding: 28px 20px;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius);
    }
    .step-num {
      width: 40px; height: 40px;
      border-radius: 50%;
      background: var(--accent);
      color: #fff;
      font-weight: 800;
      font-size: 16px;
      display: flex; align-items: center; justify-content: center;
      margin: 0 auto 14px;
    }
    .step h3 { font-size: 14px; font-weight: 700; margin-bottom: 6px; }
    .step p { font-size: 13px; color: var(--muted); }

    /* ── PROMPT CHIPS ── */
    .prompt-section {
      background: var(--surface);
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
    }
    .prompt-section .section { padding: 48px 24px; }
    .chips-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
    }
    .chip {
      background: var(--bg);
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: 8px 16px;
      font-size: 13px;
      color: var(--text);
      cursor: pointer;
      transition: border-color 0.2s, color 0.2s;
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }
    .chip:hover { border-color: var(--accent); color: var(--accent); }
    .chip-prefix { font-weight: 600; color: var(--accent); }

    /* ── AGENT SECTION ── */
    .agent-section {
      background: var(--bg);
    }
    .agent-wrapper {
      max-width: 760px;
      margin: 0 auto;
      padding: 56px 24px;
    }
    .agent-card {
      border: 1px solid var(--border);
      border-radius: 16px;
      overflow: hidden;
    }
    .agent-card-header {
      background: var(--accent);
      padding: 20px 24px;
      display: flex;
      align-items: center;
      gap: 14px;
    }
    .agent-avatar {
      width: 44px; height: 44px;
      background: rgba(255,255,255,0.2);
      border-radius: 50%;
      display: flex; align-items: center; justify-content: center;
      font-size: 20px;
      flex-shrink: 0;
    }
    .agent-card-header-text h3 {
      color: #fff;
      font-size: 16px;
      font-weight: 700;
    }
    .agent-card-header-text p {
      color: rgba(255,255,255,0.8);
      font-size: 12px;
      margin-top: 2px;
    }
    .agent-status {
      margin-left: auto;
      display: flex;
      align-items: center;
      gap: 6px;
      color: rgba(255,255,255,0.9);
      font-size: 12px;
      font-weight: 600;
    }
    .status-dot {
      width: 8px; height: 8px;
      background: #4ade80;
      border-radius: 50%;
    }
    .agent-embed-container {
      background: #fff;
      min-height: 520px;
      position: relative;
      display: flex;
      flex-direction: column;
    }
    /* watsonx chat widget lands inside #root */
    #root {
      flex: 1;
      min-height: 520px;
      width: 100%;
    }
    .agent-loading {
      position: absolute;
      inset: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 14px;
      color: var(--muted);
      font-size: 14px;
      pointer-events: none;
    }
    .spinner {
      width: 36px; height: 36px;
      border: 3px solid var(--border);
      border-top-color: var(--accent);
      border-radius: 50%;
      animation: spin 0.8s linear infinite;
    }
    @keyframes spin { to { transform: rotate(360deg); } }

    /* ── TIPS SECTION ── */
    .tips-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 16px;
    }
    .tip-card {
      border-left: 3px solid var(--accent);
      background: var(--accent-light);
      border-radius: 0 var(--radius) var(--radius) 0;
      padding: 16px 18px;
    }
    .tip-card.purple {
      border-left-color: var(--secondary);
      background: var(--secondary-light);
    }
    .tip-card h4 {
      font-size: 13px;
      font-weight: 700;
      margin-bottom: 4px;
    }
    .tip-card p {
      font-size: 12px;
      color: var(--muted);
      line-height: 1.5;
    }

    /* ── FOOTER ── */
    footer {
      border-top: 1px solid var(--border);
      background: var(--surface);
      padding: 32px 24px 24px;
      text-align: center;
    }
    .footer-brand {
      font-weight: 700;
      font-size: 15px;
      color: var(--text);
      margin-bottom: 8px;
    }
    .footer-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-bottom: 16px;
    }
    .footer-links a {
      text-decoration: none;
      font-size: 13px;
      color: var(--muted);
    }
    .footer-links a:hover { color: var(--accent); }
    .footer-copy {
      font-size: 12px;
      color: var(--muted);
      border-top: 1px solid var(--border);
      padding-top: 16px;
      margin-top: 8px;
    }

    /* ── RESPONSIVE ── */
    @media (max-width: 600px) {
      nav { padding: 0 16px; }
      .nav-links { display: none; }
      .hero { padding: 48px 16px 40px; }
      .section { padding: 40px 16px; }
    }
  </style>
</head>
<body>

  
  <nav>
    <a href="#" class="nav-brand">
      <span class="brand-icon">
        <svg><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2zm1 14.93V15a1 1 0 0 0-2 0v1.93A8 8 0 0 1 4.07 11H6a1 1 0 0 0 0-2H4.07A8 8 0 0 1 11 4.07V6a1 1 0 0 0 2 0V4.07A8 8 0 0 1 19.93 11H18a1 1 0 0 0 0 2h1.93A8 8 0 0 1 13 16.93z"></path></svg>
      </span>
      SmartStudy AI
    </a>
    <ul class="nav-links">
      <li><a href="#features">Features</a></li>
      <li><a href="#how-it-works">How it Works</a></li>
      <li><a href="#agent">Study Agent</a></li>
      <li><a href="#tips">Study Tips</a></li>
    </ul>
    <a href="#agent" class="nav-cta">Start Studying</a>
  </nav>

  
  <section class="hero">
    <div class="hero-badge">
      <svg width="10" height="10" fill="currentColor"><circle cx="5" cy="5" r="5"></circle></svg>
      Powered by IBM watsonx Orchestrate
    </div>
    <h1>Your AI-Powered<br /><span>Smart Study Generator</span></h1>
    <p>
      Generate summaries, flashcards, quizzes, concept explanations, personalized study plans,
      and exam prep guidance — all in one intelligent assistant.
    </p>
    <div class="hero-actions">
      <a href="#agent" class="btn-primary">
        <svg width="16" height="16" fill="none" stroke="#fff" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20h9"></path><path d="M16.5 3.5a2.121 2.121 0 0 1 3 3L7 19l-4 1 1-4L16.5 3.5z"></path></svg>
        Chat with Agent
      </a>
      <a href="#features" class="btn-outline">
        <svg width="16" height="16" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
        Explore Features
      </a>
    </div>
  </section>

  
  <div class="stats-strip">
    <div class="stats-inner">
      <div class="stat"><div class="stat-value">6+</div><div class="stat-label">Study Modes</div></div>
      <div class="stat"><div class="stat-value">AI</div><div class="stat-label">Powered Agent</div></div>
      <div class="stat"><div class="stat-value">24/7</div><div class="stat-label">Always Available</div></div>
      <div class="stat"><div class="stat-value">100%</div><div class="stat-label">Personalized</div></div>
    </div>
  </div>

  
  <section id="features" class="section">
    <div class="section-header">
      <h2>Everything You Need to Excel</h2>
      <p>Six powerful study tools — all driven by your AI agent.</p>
    </div>
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon" style="background:#eff6ff">📄</div>
        <h3>Study Summaries</h3>
        <p>Paste any text or topic and get a concise, exam-ready summary instantly.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:#f5f0ff">🃏</div>
        <h3>Flashcard Generator</h3>
        <p>Auto-generate question-and-answer flashcard sets from your notes or topics.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:#fff7ed">✅</div>
        <h3>Quiz Builder</h3>
        <p>Create multiple-choice or short-answer quizzes to test your understanding.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:#f0fdf4">💡</div>
        <h3>Concept Explainer</h3>
        <p>Get clear, simple breakdowns of complex topics — from any subject or level.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:#fef9c3">📅</div>
        <h3>Study Plan Builder</h3>
        <p>Receive a personalized day-by-day study schedule tailored to your goals.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:#fee2e2">🎯</div>
        <h3>Exam Preparation</h3>
        <p>Get targeted exam strategies, predicted questions, and revision checklists.</p>
      </div>
    </div>
  </section>

  
  <div style="background:var(--surface);border-top:1px solid var(--border);border-bottom:1px solid var(--border)">
    <section id="how-it-works" class="section">
      <div class="section-header">
        <h2>How It Works</h2>
        <p>Three simple steps to smarter studying.</p>
      </div>
      <div class="steps">
        <div class="step">
          <div class="step-num">1</div>
          <h3>Enter Your Topic</h3>
          <p>Type a subject, paste your notes, or describe what you need help with.</p>
        </div>
        <div class="step">
          <div class="step-num">2</div>
          <h3>Choose a Study Mode</h3>
          <p>Ask for a summary, flashcards, quiz, explanation, study plan, or exam prep.</p>
        </div>
        <div class="step">
          <div class="step-num">3</div>
          <h3>Study Smarter</h3>
          <p>Review AI-generated content, ask follow-up questions, and master your material.</p>
        </div>
      </div>
    </section>
  </div>

  
  <div class="prompt-section">
    <div class="section">
      <div class="section-header">
        <h2>Try These Prompts</h2>
        <p>Click a suggestion or type your own in the agent below.</p>
      </div>
      <div class="chips-grid">
        <span class="chip"><span class="chip-prefix">Summary</span> Summarize the French Revolution</span>
        <span class="chip"><span class="chip-prefix">Flashcards</span> Create flashcards on Photosynthesis</span>
        <span class="chip"><span class="chip-prefix">Quiz</span> Quiz me on World War II</span>
        <span class="chip"><span class="chip-prefix">Explain</span> Explain Newton's Laws simply</span>
        <span class="chip"><span class="chip-prefix">Plan</span> Build a 2-week study plan for Calculus</span>
        <span class="chip"><span class="chip-prefix">Exam</span> Help me prepare for a Biology exam</span>
        <span class="chip"><span class="chip-prefix">Summary</span> Summarize Macbeth Act 1</span>
        <span class="chip"><span class="chip-prefix">Explain</span> What is Machine Learning?</span>
        <span class="chip"><span class="chip-prefix">Quiz</span> Test me on the Periodic Table</span>
        <span class="chip"><span class="chip-prefix">Plan</span> Study schedule for final exams</span>
      </div>
    </div>
  </div>

  
  <div class="agent-section">
    <div class="agent-wrapper">
      <div class="section-header" id="agent">
        <h2>Your Smart Study Agent</h2>
        <p>Ask anything — your AI tutor is ready to help right now.</p>
      </div>
      <div class="agent-card">
        <div class="agent-card-header">
          <div class="agent-avatar">🎓</div>
          <div class="agent-card-header-text">
            <h3>SmartStudy AI Agent</h3>
            <p>Powered by IBM watsonx Orchestrate</p>
          </div>
          <div class="agent-status">
            <span class="status-dot"></span>
            Online
          </div>
        </div>
        <div class="agent-embed-container">
          <div class="agent-loading" id="agent-loading">
            <div class="spinner"></div>
            <span>Loading your study agent…</span>
          </div>
          
          <div id="root"></div>
        </div>
      </div>
    </div>
  </div>

  
  <div style="background:var(--surface);border-top:1px solid var(--border);border-bottom:1px solid var(--border)">
    <section id="tips" class="section">
      <div class="section-header">
        <h2>Study Tips &amp; Best Practices</h2>
        <p>Maximize the results you get from your AI study sessions.</p>
      </div>
      <div class="tips-grid">
        <div class="tip-card">
          <h4>Be Specific</h4>
          <p>Instead of "explain history," try "explain the causes of World War I for a Year 10 exam."</p>
        </div>
        <div class="tip-card purple">
          <h4>Iterate &amp; Ask Follow-ups</h4>
          <p>After a summary, ask "now turn this into 10 flashcards" to build on the response.</p>
        </div>
        <div class="tip-card">
          <h4>Use Active Recall</h4>
          <p>Generate a quiz after reading your summary to reinforce memory through self-testing.</p>
        </div>
        <div class="tip-card purple">
          <h4>Spaced Repetition</h4>
          <p>Ask for a study plan that spaces topics across days — the most effective memorization method.</p>
        </div>
        <div class="tip-card">
          <h4>Set a Clear Goal</h4>
          <p>Tell the agent your exam date and subject list so it can tailor the study plan precisely.</p>
        </div>
        <div class="tip-card purple">
          <h4>Review &amp; Refine</h4>
          <p>If an explanation is too advanced, ask the agent to "explain it like I'm a beginner."</p>
        </div>
      </div>
    </section>
  </div>

  
  <footer>
    <div class="footer-brand">SmartStudy AI</div>
    <div class="footer-links">
      <a href="#features">Features</a>
      <a href="#how-it-works">How it Works</a>
      <a href="#agent">Study Agent</a>
      <a href="#tips">Study Tips</a>
    </div>
    <div class="footer-copy">
      Powered by IBM watsonx Orchestrate  |  Smart Study Generator Agent<br />
      <span style="font-size:11px;color:#aaa">© 2025 SmartStudy AI. All rights reserved.</span>
    </div>
    <p style="text-align:center;font-size:12px;color:#aaa;border-top:1px solid var(--border);margin-top:16px;padding-top:12px">Made with IBM Bob</p>
  </footer>

  
  

</body>
</html>
