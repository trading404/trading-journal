<!doctype html>
<html lang="de" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=10.0, user-scalable=yes, interactive-widget=resizes-content">
  <title>Trading Journal Pro</title>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
body{box-sizing:border-box;-webkit-text-size-adjust:100%}
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#0a0e1a;--card:#151b2e;--border:#1f2937;--text:#e5e7eb;--muted:#6b7280;--primary:#3b82f6;--success:#10b981;--danger:#ef4444;--warning:#f59e0b}
html,body{height:100%;width:100%}
body{font-family:'Inter',-apple-system,sans-serif;background:var(--bg);color:var(--text);line-height:1.6}
.wrapper{width:100%;height:100%;overflow-y:auto}
.mobile-header{display:none;position:fixed;top:0;left:0;right:0;background:var(--card);border-bottom:1px solid var(--border);padding:1rem 1.5rem;z-index:200;align-items:center;justify-content:space-between}
.mobile-menu-btn{background:var(--primary);border:none;color:white;width:2.5rem;height:2.5rem;border-radius:0.5rem;font-size:1.5rem;cursor:pointer;display:flex;align-items:center;justify-content:center;touch-action:manipulation}
.mobile-menu-btn:active{transform:scale(0.95)}
.mobile-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.7);z-index:150}
.mobile-overlay.show{display:block}
.sidebar{position:fixed;left:0;top:0;bottom:0;width:240px;background:var(--card);border-right:1px solid var(--border);padding:1.5rem 1rem;overflow-y:auto;z-index:200;transition:transform 0.3s ease}
.main-content{margin-left:240px;padding:1.5rem}
.logo{font-size:1.25rem;font-weight:700;color:var(--primary);margin-bottom:2rem;display:flex;align-items:center;gap:0.5rem}
.lang-selector{margin-bottom:1.5rem;width:100%}
.lang-selector select{width:100%;padding:0.625rem;border-radius:0.5rem;border:1px solid var(--border);background:var(--bg);color:var(--text);font-size:0.875rem;cursor:pointer;touch-action:manipulation}
.nav-item{display:flex;align-items:center;gap:0.75rem;padding:0.75rem 1rem;margin-bottom:0.25rem;border-radius:0.5rem;cursor:pointer;transition:all 0.2s;color:var(--muted);font-size:0.9rem;touch-action:manipulation;min-height:48px}
.nav-item:hover{background:rgba(59,130,246,0.1);color:var(--text)}
.nav-item:active{transform:scale(0.98)}
.nav-item.active{background:var(--primary);color:white}
.section{display:none}
.section.active{display:block;animation:fadeIn 0.3s}
@keyframes fadeIn{from{opacity:0}to{opacity:1}}
.card{background:var(--card);border:1px solid var(--border);border-radius:0.75rem;padding:1.5rem;margin-bottom:1.5rem}
.card-title{font-size:1.125rem;font-weight:600;margin-bottom:1rem;display:flex;align-items:center;gap:0.5rem}
.grid{display:grid;gap:1.5rem}
.grid-2{grid-template-columns:repeat(auto-fit,minmax(300px,1fr))}
.stat-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:1rem;margin-bottom:1.5rem}
.stat{background:linear-gradient(135deg,rgba(59,130,246,0.05),rgba(59,130,246,0.02));border:1px solid var(--border);border-radius:0.75rem;padding:1rem}
.stat-label{font-size:0.75rem;color:var(--muted);text-transform:uppercase;letter-spacing:0.05em;margin-bottom:0.5rem}
.stat-value{font-size:1.75rem;font-weight:700}
.profit{color:var(--success)}
.loss{color:var(--danger)}
.form-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:1rem}
label{display:block;font-size:0.875rem;font-weight:500;color:var(--muted);margin-bottom:0.5rem;margin-top:0.75rem}
input,select,textarea{width:100%;padding:0.75rem 0.875rem;border-radius:0.5rem;border:1px solid var(--border);background:var(--bg);color:var(--text);font-size:1rem;transition:border-color 0.2s;-webkit-appearance:none;appearance:none;touch-action:manipulation;-webkit-user-select:text;user-select:text;-webkit-tap-highlight-color:transparent}
input:focus,select:focus,textarea:focus{outline:none;border-color:var(--primary);background:var(--card)}
input:active,select:active,textarea:active{border-color:var(--primary);background:var(--card)}
input[type="date"],input[type="number"]{font-size:1rem}
input[type="text"],input[type="number"],input[type="date"],select,textarea{-webkit-user-select:text !important;user-select:text !important;pointer-events:auto !important}
textarea{resize:vertical;min-height:100px;font-size:1rem;line-height:1.5}
.btn{padding:0.75rem 1.5rem;border:none;border-radius:0.5rem;font-weight:600;font-size:1rem;cursor:pointer;transition:all 0.2s;touch-action:manipulation;min-height:44px}
.btn-primary{background:var(--primary);color:white;width:100%;margin-top:1rem;padding:0.875rem}
.btn-primary:hover{background:#2563eb}
.btn-primary:active{transform:scale(0.98)}
.btn-primary:disabled{opacity:0.5;cursor:not-allowed}
.btn-sm{padding:0.5rem 0.875rem;font-size:0.875rem;min-height:40px}
.btn-danger{background:var(--danger);color:white}
.btn-danger:hover{background:#dc2626}
.btn-danger:active{transform:scale(0.98)}
.btn-secondary{background:#374151;color:var(--text)}
.btn-secondary:hover{background:#475569}
.btn-secondary:active{transform:scale(0.98)}
.table-container{overflow-x:auto;margin-top:1rem}
table{width:100%;border-collapse:collapse;font-size:0.875rem;min-width:600px}
th,td{padding:0.75rem;text-align:left;border-bottom:1px solid var(--border)}
th{background:rgba(59,130,246,0.05);font-weight:600;color:var(--muted);text-transform:uppercase;font-size:0.75rem}
.chart{height:300px;margin:1rem 0}
.chart-sm{height:250px}
.empty{text-align:center;padding:3rem 1rem;color:var(--muted)}
.empty-icon{font-size:3rem;margin-bottom:1rem;opacity:0.5}
.toast{position:fixed;bottom:2rem;right:2rem;background:var(--card);border:1px solid var(--border);padding:1rem 1.5rem;border-radius:0.5rem;box-shadow:0 10px 40px rgba(0,0,0,0.5);z-index:1000;animation:slideIn 0.3s;max-width:90%}
@keyframes slideIn{from{transform:translateX(400px);opacity:0}to{transform:translateX(0);opacity:1}}
.toast.success{border-left:4px solid var(--success)}
.toast.error{border-left:4px solid var(--danger)}
.modal{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.8);z-index:1000;align-items:center;justify-content:center;padding:1rem}
.modal.show{display:flex}
.modal-content{background:var(--card);border:1px solid var(--border);border-radius:0.75rem;padding:1.5rem;max-width:500px;width:100%;max-height:90%;overflow-y:auto}
.modal-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:1.5rem}
.modal-close{background:#374151;color:var(--text);border:none;width:2.5rem;height:2.5rem;border-radius:0.5rem;cursor:pointer;font-size:1.25rem;display:flex;align-items:center;justify-content:center;touch-action:manipulation}
.modal-close:hover{background:#475569}
.modal-close:active{transform:scale(0.95)}
.emotion-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:0.75rem;margin-top:1rem}
.emotion-btn{background:var(--bg);border:2px solid var(--border);border-radius:0.75rem;padding:1rem;cursor:pointer;transition:all 0.2s;text-align:center;font-size:0.875rem;color:var(--text);touch-action:manipulation;min-height:60px}
.emotion-btn:hover{border-color:var(--primary);transform:translateY(-2px)}
.emotion-btn:active{transform:translateY(0)}
.emotion-btn.selected{border-color:var(--primary);background:rgba(59,130,246,0.1)}
.emotion-icon{font-size:2rem;display:block;margin-bottom:0.5rem}
.goal-card{background:rgba(59,130,246,0.03);border:1px solid var(--border);border-radius:0.75rem;padding:1.25rem;margin-bottom:1rem}
.goal-header{display:flex;justify-content:space-between;align-items:start;margin-bottom:1rem;gap:1rem}
.progress-bar{width:100%;height:6px;background:var(--border);border-radius:3px;overflow:hidden;margin:0.75rem 0}
.progress-fill{height:100%;background:linear-gradient(90deg,var(--primary),#60a5fa);transition:width 0.3s}
.status-badge{display:inline-flex;align-items:center;gap:0.5rem;padding:0.5rem 1rem;border-radius:0.5rem;font-weight:600;font-size:0.85rem;margin-top:0.75rem}
.status-ahead{background:rgba(16,185,129,0.1);border:1px solid var(--success);color:var(--success)}
.status-behind{background:rgba(239,68,68,0.1);border:1px solid var(--danger);color:var(--danger)}
.loading{display:inline-block;width:1rem;height:1rem;border:2px solid rgba(255,255,255,0.3);border-radius:50%;border-top-color:white;animation:spin 0.6s linear infinite;margin-left:0.5rem}
@keyframes spin{to{transform:rotate(360deg)}}

@media(max-width:768px){
  .mobile-header{display:flex}
  .mobile-menu-btn{width:3rem;height:3rem;min-height:48px}
  .sidebar{transform:translateX(-100%)}
  .sidebar.open{transform:translateX(0)}
  .main-content{margin-left:0;padding:1rem;padding-top:4.5rem}
  .logo{font-size:1rem;margin-bottom:1.5rem}
  .stat-value{font-size:1.5rem}
  .stat-grid{grid-template-columns:repeat(2,1fr);gap:0.75rem}
  .form-grid{grid-template-columns:1fr}
  .grid-2{grid-template-columns:1fr}
  .card{padding:1rem;border-radius:0.5rem}
  .card-title{font-size:1rem}
  .chart{height:250px}
  .chart-sm{height:200px}
  table{font-size:0.75rem}
  th,td{padding:0.5rem 0.25rem}
  .emotion-grid{grid-template-columns:repeat(2,1fr)}
  .emotion-btn{padding:0.875rem 0.5rem;font-size:0.85rem;min-height:72px}
  .emotion-icon{font-size:1.75rem}
  .toast{bottom:1rem;right:1rem;left:1rem;max-width:none}
  .btn-sm{padding:0.625rem 0.875rem;font-size:0.875rem;min-height:48px}
  input,select,textarea{font-size:16px !important;padding:0.875rem;min-height:50px}
  input[type="date"],input[type="number"]{font-size:16px !important}
  input[type="range"]{min-height:32px;padding:0}
  input[type="text"],input[type="number"],input[type="date"],select{-webkit-user-select:text !important;user-select:text !important;-webkit-touch-callout:default !important;pointer-events:auto !important}
  textarea{min-height:120px;font-size:16px !important;-webkit-user-select:text !important;user-select:text !important;-webkit-touch-callout:default !important}
  label{font-size:0.95rem;margin-bottom:0.625rem;margin-top:0.875rem}
  .btn{font-size:1rem;padding:0.875rem 1.5rem;min-height:52px}
  .btn-primary{padding:1rem;min-height:56px;font-size:1.05rem}
  .modal-close{width:3rem;height:3rem;min-height:48px}
  .lang-selector{margin-bottom:1rem}
}

@media(max-width:480px){
  .stat-grid{grid-template-columns:1fr}
  .stat-value{font-size:1.25rem}
  .emotion-grid{grid-template-columns:1fr}
  .emotion-btn{min-height:64px}
  table{font-size:0.7rem}
  th,td{padding:0.4rem 0.2rem}
}
</style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="/_sdk/element_sdk.js" type="text/javascript"></script>
  <script src="https://cdn.tailwindcss.com" type="text/javascript"></script>
 </head>
 <body class="h-full">
  <div class="wrapper">
   <div class="mobile-header">
    <div style="font-size:1.25rem;font-weight:700;color:var(--primary)">
     📊 <span id="mobileHeaderTitle">Trading Pro</span>
    </div>
    <div style="display:flex;gap:0.5rem;align-items:center"><select id="mobileLanguageSelector" style="padding:0.5rem;border-radius:0.5rem;border:1px solid var(--border);background:var(--bg);color:var(--text);font-size:0.875rem;cursor:pointer;min-height:44px"> <option value="de">🇩🇪 DE</option> <option value="en">🇬🇧 EN</option> <option value="es">🇪🇸 ES</option> </select> <button class="mobile-menu-btn" id="mobileMenuBtn">☰</button>
    </div>
   </div>
   <div class="mobile-overlay" id="mobileOverlay"></div>
   <aside class="sidebar" id="sidebar">
    <div class="logo">
     📊 <span id="sidebarTitle">Trading Pro</span>
    </div>
    <div class="lang-selector"><select id="languageSelector" style="min-height:44px"> <option value="de">🇩🇪 Deutsch</option> <option value="en">🇬🇧 English</option> <option value="es">🇪🇸 Español</option> </select>
    </div>
    <nav id="navigation">
     <div class="nav-item active" data-section="dashboard">
      <span class="nav-icon">📊</span> <span class="nav-text">Dashboard</span>
     </div>
     <div class="nav-item" data-section="trade">
      <span class="nav-icon">➕</span> <span class="nav-text">Neuer Trade</span>
     </div>
     <div class="nav-item" data-section="history">
      <span class="nav-icon">📜</span> <span class="nav-text">Historie</span>
     </div>
     <div class="nav-item" data-section="performance">
      <span class="nav-icon">📊</span> <span class="nav-text">Performance</span>
     </div>
     <div class="nav-item" data-section="emotions">
      <span class="nav-icon">🎭</span> <span class="nav-text">Emotionen</span>
     </div>
     <div class="nav-item" data-section="goals">
      <span class="nav-icon">🧮</span> <span class="nav-text">Zinseszins</span>
     </div>
     <div class="nav-item" data-section="withdrawals">
      <span class="nav-icon">💸</span> <span class="nav-text">Auszahlungen</span>
     </div>
    </nav>
   </aside>
   <main class="main-content" id="mainContent"><!-- Content will be dynamically updated based on language -->
   </main>
  </div>
  <div id="editModal" class="modal">
   <div class="modal-content">
    <div class="modal-header">
     <h3 id="editModalTitle">Trade bearbeiten</h3><button class="modal-close" onclick="closeEditModal()">✕</button>
    </div>
    <form id="editTradeForm"><!-- Form content will be dynamically updated -->
    </form>
   </div>
  </div>
  <script>
// Translations
const translations = {
  de: {
    appTitle: "Trading Pro",
    nav: {
      dashboard: "Dashboard",
      newTrade: "Neuer Trade",
      history: "Historie",
      performance: "Performance",
      emotions: "Emotionen",
      compound: "Zinseszins",
      withdrawals: "Auszahlungen"
    },
    dashboard: {
      title: "Dashboard",
      capitalSetup: "Kapital Setup",
      startCapital: "Startkapital (€)",
      saveCapital: "Startkapital speichern",
      overview: "Übersicht",
      currentCapital: "Aktuelles Kapital",
      trades: "Trades",
      winrate: "Winrate",
      totalPL: "Gesamt P/L",
      financialOverview: "Finanzübersicht",
      wins: "Gewinne",
      losses: "Verluste",
      withdrawals: "Auszahlungen",
      cashflowSummary: "Cashflow Zusammenfassung",
      incomeVsExpenses: "Einnahmen vs. Ausgaben",
      totalIncome: "Gesamt Einnahmen",
      totalExpenses: "Gesamt Ausgaben",
      netResult: "Netto Ergebnis",
      equityCurve: "Equity Curve",
      maxDrawdown: "Max Drawdown",
      profitFactor: "Profit Factor"
    },
    trade: {
      title: "Neuer Trade",
      date: "Datum",
      asset: "Asset",
      select: "-- auswählen --",
      lotSize: "Lot Size",
      result: "Ergebnis",
      win: "Gewinn",
      loss: "Verlust",
      breakeven: "Break Even",
      profitLoss: "Gewinn/Verlust (€)",
      entryPrice: "Entry Price",
      exitPrice: "Exit Price",
      strategy: "Strategie",
      strategyPlaceholder: "z.B. Trend Following",
      emotion: "Emotion beim Trade",
      noEmotion: "-- keine Emotion --",
      notes: "Notizen",
      notesPlaceholder: "Deine Gedanken zum Trade...",
      addTrade: "Trade hinzufügen",
      required: "* Pflichtfeld - alle anderen Felder sind optional"
    },
    history: {
      title: "Trade Historie",
      date: "Datum",
      asset: "Asset",
      lot: "Lot",
      result: "Ergebnis",
      emotion: "Emotion",
      actions: "Aktionen",
      edit: "Edit",
      delete: "Löschen",
      noTrades: "Noch keine Trades"
    },
    performance: {
      title: "Performance Analyse",
      metrics: "Performance Metriken",
      totalPL: "Gesamt P/L",
      avgWin: "Ø Gewinn",
      avgLoss: "Ø Verlust",
      winrate: "Winrate",
      profitFactor: "Profit Factor",
      trades: "Trades",
      bestTrade: "Bester Trade",
      worstTrade: "Schlechtester Trade",
      currentStreak: "Aktueller Streak",
      assetDistribution: "Asset Verteilung",
      assetPerformance: "Asset Performance (P/L)",
      monthlyPerformance: "Monatliche Performance",
      streaksTitle: "Winning & Losing Streaks",
      longestWinStreak: "Längster Winning Streak",
      longestLossStreak: "Längster Losing Streak",
      consecutiveWins: "aufeinanderfolgende Gewinne",
      consecutiveLosses: "aufeinanderfolgende Verluste",
      currentlyIn: "Du befindest dich gerade in einem",
      winningStreak: "Winning Streak",
      losingStreak: "Losing Streak",
      noData: "Keine Daten"
    },
    emotions: {
      title: "Emotionen Tracking",
      date: "Datum",
      selectEmotion: "Emotion wählen",
      confident: "Selbstsicher",
      anxious: "Ängstlich",
      excited: "Aufgeregt",
      frustrated: "Frustriert",
      calm: "Gelassen",
      greedy: "Gierig",
      intensity: "Intensität (1-10)",
      notes: "Notizen",
      notesPlaceholder: "Wie fühlst du dich heute beim Trading?",
      save: "Emotion speichern",
      noEmotions: "Noch keine Emotionen getrackt",
      fromHistory: "Aus Trade Historie"
    },
    compound: {
      title: "Zinseszinseffekt Rechner",
      currentPerformance: "Deine aktuelle Performance",
      currentCapital: "Aktuelles Kapital",
      avgMonthlyReturn: "Ø Monatliche Rendite",
      tradingSince: "Trading seit",
      months: "Monate",
      calculate: "Zinseszins berechnen",
      startCapital: "Startkapital (€)",
      monthlyReturn: "Monatliche Rendite (%)",
      timeframe: "Zeitraum (Monate)",
      monthlyWithdrawal: "Monatliche Auszahlung (€)",
      optional: "Optional - 0 für keine Auszahlungen",
      yourCurrent: "Deine aktuelle",
      calculateBtn: "Berechnen",
      results: "Berechnungsergebnis",
      finalCapital: "Endkapital nach",
      totalGrowth: "Gesamt Wachstum",
      totalReturn: "Gesamt Return",
      totalWithdrawn: "Gesamt ausgezahlt",
      capitalGrowth: "Kapitalwachstum"
    },
    withdrawals: {
      title: "Auszahlungen",
      newWithdrawal: "Neue Auszahlung",
      date: "Datum",
      amount: "Betrag (€)",
      notes: "Notizen",
      notesPlaceholder: "Grund für die Auszahlung...",
      add: "Auszahlung hinzufügen",
      total: "Gesamt Auszahlungen",
      count: "Anzahl",
      noWithdrawals: "Keine Auszahlungen"
    },
    modals: {
      editTrade: "Trade bearbeiten",
      deleteTrade: "Trade löschen?",
      deleteEmotion: "Emotion löschen?",
      deleteWithdrawal: "Auszahlung löschen?",
      confirm: "Löschen",
      cancel: "Abbrechen",
      update: "Trade aktualisieren"
    },
    messages: {
      capitalSaved: "Startkapital gespeichert!",
      tradeAdded: "Trade erfolgreich hinzugefügt!",
      tradeUpdated: "Trade aktualisiert!",
      tradeDeleted: "Trade gelöscht",
      emotionSaved: "Emotion gespeichert!",
      emotionDeleted: "Emotion gelöscht",
      withdrawalAdded: "Auszahlung hinzugefügt!",
      withdrawalDeleted: "Auszahlung gelöscht",
      calculationSuccess: "Berechnung erfolgreich!",
      selectEmotion: "Bitte wähle eine Emotion",
      fillAllFields: "Bitte alle Felder korrekt ausfüllen",
      validCapital: "Bitte gültiges Startkapital eingeben"
    }
  },
  en: {
    appTitle: "Trading Pro",
    nav: {
      dashboard: "Dashboard",
      newTrade: "New Trade",
      history: "History",
      performance: "Performance",
      emotions: "Emotions",
      compound: "Compound",
      withdrawals: "Withdrawals"
    },
    dashboard: {
      title: "Dashboard",
      capitalSetup: "Capital Setup",
      startCapital: "Starting Capital (€)",
      saveCapital: "Save Starting Capital",
      overview: "Overview",
      currentCapital: "Current Capital",
      trades: "Trades",
      winrate: "Win Rate",
      totalPL: "Total P/L",
      financialOverview: "Financial Overview",
      wins: "Wins",
      losses: "Losses",
      withdrawals: "Withdrawals",
      cashflowSummary: "Cashflow Summary",
      incomeVsExpenses: "Income vs. Expenses",
      totalIncome: "Total Income",
      totalExpenses: "Total Expenses",
      netResult: "Net Result",
      equityCurve: "Equity Curve",
      maxDrawdown: "Max Drawdown",
      profitFactor: "Profit Factor"
    },
    trade: {
      title: "New Trade",
      date: "Date",
      asset: "Asset",
      select: "-- select --",
      lotSize: "Lot Size",
      result: "Result",
      win: "Win",
      loss: "Loss",
      breakeven: "Break Even",
      profitLoss: "Profit/Loss (€)",
      entryPrice: "Entry Price",
      exitPrice: "Exit Price",
      strategy: "Strategy",
      strategyPlaceholder: "e.g. Trend Following",
      emotion: "Trade Emotion",
      noEmotion: "-- no emotion --",
      notes: "Notes",
      notesPlaceholder: "Your thoughts about the trade...",
      addTrade: "Add Trade",
      required: "* Required field - all other fields are optional"
    },
    history: {
      title: "Trade History",
      date: "Date",
      asset: "Asset",
      lot: "Lot",
      result: "Result",
      emotion: "Emotion",
      actions: "Actions",
      edit: "Edit",
      delete: "Delete",
      noTrades: "No trades yet"
    },
    performance: {
      title: "Performance Analysis",
      metrics: "Performance Metrics",
      totalPL: "Total P/L",
      avgWin: "Avg Win",
      avgLoss: "Avg Loss",
      winrate: "Win Rate",
      profitFactor: "Profit Factor",
      trades: "Trades",
      bestTrade: "Best Trade",
      worstTrade: "Worst Trade",
      currentStreak: "Current Streak",
      assetDistribution: "Asset Distribution",
      assetPerformance: "Asset Performance (P/L)",
      monthlyPerformance: "Monthly Performance",
      streaksTitle: "Winning & Losing Streaks",
      longestWinStreak: "Longest Win Streak",
      longestLossStreak: "Longest Loss Streak",
      consecutiveWins: "consecutive wins",
      consecutiveLosses: "consecutive losses",
      currentlyIn: "You are currently in a",
      winningStreak: "Winning Streak",
      losingStreak: "Losing Streak",
      noData: "No data"
    },
    emotions: {
      title: "Emotions Tracking",
      date: "Date",
      selectEmotion: "Select Emotion",
      confident: "Confident",
      anxious: "Anxious",
      excited: "Excited",
      frustrated: "Frustrated",
      calm: "Calm",
      greedy: "Greedy",
      intensity: "Intensity (1-10)",
      notes: "Notes",
      notesPlaceholder: "How do you feel about trading today?",
      save: "Save Emotion",
      noEmotions: "No emotions tracked yet",
      fromHistory: "From Trade History"
    },
    compound: {
      title: "Compound Interest Calculator",
      currentPerformance: "Your Current Performance",
      currentCapital: "Current Capital",
      avgMonthlyReturn: "Avg Monthly Return",
      tradingSince: "Trading Since",
      months: "Months",
      calculate: "Calculate Compound",
      startCapital: "Starting Capital (€)",
      monthlyReturn: "Monthly Return (%)",
      timeframe: "Timeframe (Months)",
      monthlyWithdrawal: "Monthly Withdrawal (€)",
      optional: "Optional - 0 for no withdrawals",
      yourCurrent: "Your current",
      calculateBtn: "Calculate",
      results: "Calculation Results",
      finalCapital: "Final Capital after",
      totalGrowth: "Total Growth",
      totalReturn: "Total Return",
      totalWithdrawn: "Total Withdrawn",
      capitalGrowth: "Capital Growth"
    },
    withdrawals: {
      title: "Withdrawals",
      newWithdrawal: "New Withdrawal",
      date: "Date",
      amount: "Amount (€)",
      notes: "Notes",
      notesPlaceholder: "Reason for withdrawal...",
      add: "Add Withdrawal",
      total: "Total Withdrawals",
      count: "Count",
      noWithdrawals: "No withdrawals"
    },
    modals: {
      editTrade: "Edit Trade",
      deleteTrade: "Delete trade?",
      deleteEmotion: "Delete emotion?",
      deleteWithdrawal: "Delete withdrawal?",
      confirm: "Delete",
      cancel: "Cancel",
      update: "Update Trade"
    },
    messages: {
      capitalSaved: "Starting capital saved!",
      tradeAdded: "Trade successfully added!",
      tradeUpdated: "Trade updated!",
      tradeDeleted: "Trade deleted",
      emotionSaved: "Emotion saved!",
      emotionDeleted: "Emotion deleted",
      withdrawalAdded: "Withdrawal added!",
      withdrawalDeleted: "Withdrawal deleted",
      calculationSuccess: "Calculation successful!",
      selectEmotion: "Please select an emotion",
      fillAllFields: "Please fill all fields correctly",
      validCapital: "Please enter valid starting capital"
    }
  },
  es: {
    appTitle: "Trading Pro",
    nav: {
      dashboard: "Panel",
      newTrade: "Nueva Operación",
      history: "Historia",
      performance: "Rendimiento",
      emotions: "Emociones",
      compound: "Interés Compuesto",
      withdrawals: "Retiros"
    },
    dashboard: {
      title: "Panel de Control",
      capitalSetup: "Configuración de Capital",
      startCapital: "Capital Inicial (€)",
      saveCapital: "Guardar Capital Inicial",
      overview: "Resumen",
      currentCapital: "Capital Actual",
      trades: "Operaciones",
      winrate: "Tasa de Éxito",
      totalPL: "P/L Total",
      financialOverview: "Resumen Financiero",
      wins: "Ganancias",
      losses: "Pérdidas",
      withdrawals: "Retiros",
      cashflowSummary: "Resumen de Flujo de Caja",
      incomeVsExpenses: "Ingresos vs. Gastos",
      totalIncome: "Ingresos Totales",
      totalExpenses: "Gastos Totales",
      netResult: "Resultado Neto",
      equityCurve: "Curva de Capital",
      maxDrawdown: "Pérdida Máxima",
      profitFactor: "Factor de Beneficio"
    },
    trade: {
      title: "Nueva Operación",
      date: "Fecha",
      asset: "Activo",
      select: "-- seleccionar --",
      lotSize: "Tamaño de Lote",
      result: "Resultado",
      win: "Ganancia",
      loss: "Pérdida",
      breakeven: "Punto de Equilibrio",
      profitLoss: "Ganancia/Pérdida (€)",
      entryPrice: "Precio de Entrada",
      exitPrice: "Precio de Salida",
      strategy: "Estrategia",
      strategyPlaceholder: "ej. Seguimiento de Tendencia",
      emotion: "Emoción en la Operación",
      noEmotion: "-- sin emoción --",
      notes: "Notas",
      notesPlaceholder: "Tus pensamientos sobre la operación...",
      addTrade: "Agregar Operación",
      required: "* Campo obligatorio - todos los demás campos son opcionales"
    },
    history: {
      title: "Historial de Operaciones",
      date: "Fecha",
      asset: "Activo",
      lot: "Lote",
      result: "Resultado",
      emotion: "Emoción",
      actions: "Acciones",
      edit: "Editar",
      delete: "Eliminar",
      noTrades: "Aún no hay operaciones"
    },
    performance: {
      title: "Análisis de Rendimiento",
      metrics: "Métricas de Rendimiento",
      totalPL: "P/L Total",
      avgWin: "Ganancia Prom.",
      avgLoss: "Pérdida Prom.",
      winrate: "Tasa de Éxito",
      profitFactor: "Factor de Beneficio",
      trades: "Operaciones",
      bestTrade: "Mejor Operación",
      worstTrade: "Peor Operación",
      currentStreak: "Racha Actual",
      assetDistribution: "Distribución de Activos",
      assetPerformance: "Rendimiento por Activo (P/L)",
      monthlyPerformance: "Rendimiento Mensual",
      streaksTitle: "Rachas Ganadoras y Perdedoras",
      longestWinStreak: "Racha Ganadora Más Larga",
      longestLossStreak: "Racha Perdedora Más Larga",
      consecutiveWins: "victorias consecutivas",
      consecutiveLosses: "pérdidas consecutivas",
      currentlyIn: "Actualmente estás en una",
      winningStreak: "Racha Ganadora",
      losingStreak: "Racha Perdedora",
      noData: "Sin datos"
    },
    emotions: {
      title: "Seguimiento de Emociones",
      date: "Fecha",
      selectEmotion: "Seleccionar Emoción",
      confident: "Confiado",
      anxious: "Ansioso",
      excited: "Emocionado",
      frustrated: "Frustrado",
      calm: "Tranquilo",
      greedy: "Codicioso",
      intensity: "Intensidad (1-10)",
      notes: "Notas",
      notesPlaceholder: "¿Cómo te sientes hoy con el trading?",
      save: "Guardar Emoción",
      noEmotions: "Aún no hay emociones registradas",
      fromHistory: "Del Historial de Operaciones"
    },
    compound: {
      title: "Calculadora de Interés Compuesto",
      currentPerformance: "Tu Rendimiento Actual",
      currentCapital: "Capital Actual",
      avgMonthlyReturn: "Retorno Mensual Prom.",
      tradingSince: "Operando Desde",
      months: "Meses",
      calculate: "Calcular Interés Compuesto",
      startCapital: "Capital Inicial (€)",
      monthlyReturn: "Retorno Mensual (%)",
      timeframe: "Período (Meses)",
      monthlyWithdrawal: "Retiro Mensual (€)",
      optional: "Opcional - 0 para ningún retiro",
      yourCurrent: "Tu actual",
      calculateBtn: "Calcular",
      results: "Resultados del Cálculo",
      finalCapital: "Capital Final después de",
      totalGrowth: "Crecimiento Total",
      totalReturn: "Retorno Total",
      totalWithdrawn: "Total Retirado",
      capitalGrowth: "Crecimiento del Capital"
    },
    withdrawals: {
      title: "Retiros",
      newWithdrawal: "Nuevo Retiro",
      date: "Fecha",
      amount: "Monto (€)",
      notes: "Notas",
      notesPlaceholder: "Motivo del retiro...",
      add: "Agregar Retiro",
      total: "Retiros Totales",
      count: "Cantidad",
      noWithdrawals: "Sin retiros"
    },
    modals: {
      editTrade: "Editar Operación",
      deleteTrade: "¿Eliminar operación?",
      deleteEmotion: "¿Eliminar emoción?",
      deleteWithdrawal: "¿Eliminar retiro?",
      confirm: "Eliminar",
      cancel: "Cancelar",
      update: "Actualizar Operación"
    },
    messages: {
      capitalSaved: "¡Capital inicial guardado!",
      tradeAdded: "¡Operación agregada exitosamente!",
      tradeUpdated: "¡Operación actualizada!",
      tradeDeleted: "Operación eliminada",
      emotionSaved: "¡Emoción guardada!",
      emotionDeleted: "Emoción eliminada",
      withdrawalAdded: "¡Retiro agregado!",
      withdrawalDeleted: "Retiro eliminado",
      calculationSuccess: "¡Cálculo exitoso!",
      selectEmotion: "Por favor selecciona una emoción",
      fillAllFields: "Por favor completa todos los campos correctamente",
      validCapital: "Por favor ingresa un capital inicial válido"
    }
  }
};

let currentLang = localStorage.getItem('tradingJournalLang') || 'de';
let allData = [];
let charts = {};
let selectedEmotion = '';

// Language Management
function setLanguage(lang) {
  currentLang = lang;
  localStorage.setItem('tradingJournalLang', lang);
  document.getElementById('languageSelector').value = lang;
  document.getElementById('mobileLanguageSelector').value = lang;
  renderUI();
  updateAll();
}

function t(path) {
  const keys = path.split('.');
  let value = translations[currentLang];
  for (const key of keys) {
    value = value[key];
    if (value === undefined) return path;
  }
  return value;
}

// Mobile Menu
let mobileMenuBtn, sidebar, mobileOverlay;

function initMobileMenu() {
  mobileMenuBtn = document.getElementById('mobileMenuBtn');
  sidebar = document.getElementById('sidebar');
  mobileOverlay = document.getElementById('mobileOverlay');
  
  if (mobileMenuBtn) {
    mobileMenuBtn.addEventListener('click', () => {
      sidebar.classList.add('open');
      mobileOverlay.classList.add('show');
    });
  }
  
  if (mobileOverlay) {
    mobileOverlay.addEventListener('click', () => {
      sidebar.classList.remove('open');
      mobileOverlay.classList.remove('show');
    });
  }
}

// LocalStorage Functions
function saveToLocalStorage() {
  localStorage.setItem('tradingJournalData', JSON.stringify(allData));
}

function loadFromLocalStorage() {
  const stored = localStorage.getItem('tradingJournalData');
  if (stored) {
    allData = JSON.parse(stored);
  }
}

function generateId() {
  return Date.now().toString(36) + Math.random().toString(36).substr(2);
}

// Render Complete UI
function renderUI() {
  const lang = translations[currentLang];
  
  // Update titles
  document.getElementById('sidebarTitle').textContent = lang.appTitle;
  document.getElementById('mobileHeaderTitle').textContent = lang.appTitle;
  
  // Update navigation
  const navItems = document.querySelectorAll('.nav-item');
  navItems[0].innerHTML = `<span class="nav-icon">📊</span> <span class="nav-text">${lang.nav.dashboard}</span>`;
  navItems[1].innerHTML = `<span class="nav-icon">➕</span> <span class="nav-text">${lang.nav.newTrade}</span>`;
  navItems[2].innerHTML = `<span class="nav-icon">📜</span> <span class="nav-text">${lang.nav.history}</span>`;
  navItems[3].innerHTML = `<span class="nav-icon">📊</span> <span class="nav-text">${lang.nav.performance}</span>`;
  navItems[4].innerHTML = `<span class="nav-icon">🎭</span> <span class="nav-text">${lang.nav.emotions}</span>`;
  navItems[5].innerHTML = `<span class="nav-icon">🧮</span> <span class="nav-text">${lang.nav.compound}</span>`;
  navItems[6].innerHTML = `<span class="nav-icon">💸</span> <span class="nav-text">${lang.nav.withdrawals}</span>`;
  
  // Render main content sections
  renderDashboard();
  renderTradePage();
  renderHistoryPage();
  renderPerformancePage();
  renderEmotionsPage();
  renderCompoundPage();
  renderWithdrawalsPage();
  renderEditModal();
}

function renderDashboard() {
  const d = translations[currentLang].dashboard;
  const mainContent = document.getElementById('mainContent');
  
  const dashboardSection = document.createElement('section');
  dashboardSection.id = 'dashboard';
  dashboardSection.className = 'section active';
  dashboardSection.innerHTML = `
    <h2 style="margin-bottom:1.5rem">📊 ${d.title}</h2>
    <div class="grid grid-2">
      <div class="card">
        <div class="card-title">💰 ${d.capitalSetup}</div>
        <label for="startCapital">${d.startCapital}</label>
        <input type="number" id="startCapital" placeholder="10000" inputmode="decimal">
        <button class="btn btn-primary" id="saveCapital">${d.saveCapital}</button>
      </div>
      <div class="card">
        <div class="card-title">📌 ${d.overview}</div>
        <div class="stat-grid" style="grid-template-columns:repeat(2,1fr)">
          <div class="stat">
            <div class="stat-label">${d.currentCapital}</div>
            <div class="stat-value" id="currentCapital">0€</div>
          </div>
          <div class="stat">
            <div class="stat-label">${d.trades}</div>
            <div class="stat-value" id="totalTrades">0</div>
          </div>
          <div class="stat">
            <div class="stat-label">${d.winrate}</div>
            <div class="stat-value" id="winrate">0%</div>
          </div>
          <div class="stat">
            <div class="stat-label">${d.totalPL}</div>
            <div class="stat-value" id="totalPL">0€</div>
          </div>
        </div>
      </div>
    </div>
    <div class="card">
      <div class="card-title">💰 ${d.financialOverview}</div>
      <div class="stat-grid" style="grid-template-columns:repeat(3,1fr)">
        <div class="stat">
          <div class="stat-label">✅ ${d.wins}</div>
          <div class="stat-value profit" id="totalWins">0€</div>
          <div style="font-size:0.75rem;color:var(--muted);margin-top:0.5rem"><span id="winCount">0</span> ${d.trades}</div>
        </div>
        <div class="stat">
          <div class="stat-label">❌ ${d.losses}</div>
          <div class="stat-value loss" id="totalLosses">0€</div>
          <div style="font-size:0.75rem;color:var(--muted);margin-top:0.5rem"><span id="lossCount">0</span> ${d.trades}</div>
        </div>
        <div class="stat">
          <div class="stat-label">💸 ${d.withdrawals}</div>
          <div class="stat-value loss" id="totalWithdrawals">0€</div>
          <div style="font-size:0.75rem;color:var(--muted);margin-top:0.5rem"><span id="withdrawalCount">0</span> ${d.withdrawals}</div>
        </div>
      </div>
      
      <div style="margin-top:1.5rem;padding:1.25rem;background:rgba(59,130,246,0.05);border:1px solid var(--border);border-radius:0.75rem">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1rem;flex-wrap:wrap;gap:0.5rem">
          <div style="font-weight:600;font-size:1rem">💵 ${d.cashflowSummary}</div>
          <div style="font-size:0.875rem;color:var(--muted)">${d.incomeVsExpenses}</div>
        </div>
        <div class="stat-grid" style="grid-template-columns:repeat(2,1fr)">
          <div>
            <div style="font-size:0.875rem;color:var(--muted);margin-bottom:0.5rem">📥 ${d.totalIncome}</div>
            <div style="font-size:1.75rem;font-weight:700;color:var(--success)" id="totalIncome">0€</div>
          </div>
          <div>
            <div style="font-size:0.875rem;color:var(--muted);margin-bottom:0.5rem">📤 ${d.totalExpenses}</div>
            <div style="font-size:1.75rem;font-weight:700;color:var(--danger)" id="totalExpenses">0€</div>
          </div>
        </div>
        <div style="margin-top:1rem;padding-top:1rem;border-top:1px solid var(--border)">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <span style="font-size:0.875rem;color:var(--muted)">💎 ${d.netResult}</span>
            <span style="font-size:1.5rem;font-weight:700" id="netResult">0€</span>
          </div>
        </div>
      </div>
    </div>
    
    <div class="card">
      <div class="card-title">📈 ${d.equityCurve}</div>
      <div class="chart"><canvas id="equityChart"></canvas></div>
    </div>
    <div class="stat-grid">
      <div class="stat">
        <div class="stat-label">${d.maxDrawdown}</div>
        <div class="stat-value loss" id="maxDrawdown">0€</div>
      </div>
      <div class="stat">
        <div class="stat-label">${d.profitFactor}</div>
        <div class="stat-value" id="profitFactor">0.00</div>
      </div>
    </div>
  `;
  
  // Clear and append
  const existingDashboard = document.getElementById('dashboard');
  if (existingDashboard) existingDashboard.remove();
  mainContent.appendChild(dashboardSection);
  
  // Add event listener
  const saveCapitalBtn = document.getElementById('saveCapital');
  if (saveCapitalBtn) {
    saveCapitalBtn.addEventListener('click', function() {
      const value = parseFloat(document.getElementById('startCapital').value);
      
      if (isNaN(value) || value <= 0) {
        showToast(t('messages.validCapital'), 'error');
        return;
      }
      
      const existing = allData.find(d => d.type === 'capital');
      
      if (existing) {
        existing.start_capital = value;
      } else {
        allData.push({
          id: generateId(),
          type: 'capital',
          start_capital: value,
          date: new Date().toISOString()
        });
      }
      
      saveToLocalStorage();
      updateAll();
      showToast(t('messages.capitalSaved'), 'success');
    });
  }
}

function renderTradePage() {
  const tr = translations[currentLang].trade;
  const mainContent = document.getElementById('mainContent');
  
  const tradeSection = document.createElement('section');
  tradeSection.id = 'trade';
  tradeSection.className = 'section';
  tradeSection.innerHTML = `
    <h2 style="margin-bottom:1.5rem">➕ ${tr.title}</h2>
    <div class="card">
      <form id="tradeForm">
        <div class="form-grid">
          <div><label for="tradeDate">${tr.date} *</label><input type="date" id="tradeDate" required></div>
          <div><label for="tradeAsset">${tr.asset}</label><select id="tradeAsset"><option value="">${tr.select}</option><optgroup label="Major Pairs"><option>EUR/USD</option><option>GBP/USD</option><option>USD/JPY</option><option>USD/CHF</option><option>AUD/USD</option><option>USD/CAD</option><option>NZD/USD</option></optgroup><optgroup label="Minor Pairs"><option>EUR/GBP</option><option>EUR/AUD</option><option>EUR/CAD</option><option>EUR/JPY</option><option>GBP/JPY</option><option>GBP/AUD</option><option>AUD/JPY</option><option>NZD/JPY</option></optgroup><optgroup label="Exotic Pairs"><option>USD/TRY</option><option>USD/ZAR</option><option>USD/MXN</option><option>EUR/TRY</option></optgroup><optgroup label="Commodities"><option>XAU/USD (Gold)</option><option>XAG/USD (Silber)</option><option>WTI/USD (Öl)</option></optgroup><optgroup label="Crypto"><option>BTC/USD</option><option>ETH/USD</option><option>XRP/USD</option></optgroup><optgroup label="Indices"><option>US30</option><option>NAS100</option><option>SPX500</option><option>GER40</option><option>UK100</option></optgroup></select></div>
          <div><label for="tradeLot">${tr.lotSize}</label><input type="number" step="0.01" id="tradeLot" placeholder="0.01" inputmode="decimal"></div>
          <div><label for="tradeResult">${tr.result}</label><select id="tradeResult"><option value="">${tr.select}</option><option value="win">✅ ${tr.win}</option><option value="loss">❌ ${tr.loss}</option><option value="breakeven">➖ ${tr.breakeven}</option></select></div>
          <div><label for="tradePL">${tr.profitLoss}</label><input type="number" step="0.01" id="tradePL" placeholder="0.00" inputmode="decimal"></div>
          <div><label for="tradeEntry">${tr.entryPrice}</label><input type="number" step="0.00001" id="tradeEntry" placeholder="1.08500" inputmode="decimal"></div>
          <div><label for="tradeExit">${tr.exitPrice}</label><input type="number" step="0.00001" id="tradeExit" placeholder="1.08750" inputmode="decimal"></div>
          <div><label for="tradeStrategy">${tr.strategy}</label><input type="text" id="tradeStrategy" placeholder="${tr.strategyPlaceholder}"></div>
        </div>
        <p style="font-size:0.75rem;color:var(--muted);margin-top:0.5rem">${tr.required}</p>
        <label for="tradeEmotion">${tr.emotion}</label>
        <select id="tradeEmotion">
          <option value="">${tr.noEmotion}</option>
          <option value="confident">😎 ${translations[currentLang].emotions.confident}</option>
          <option value="anxious">😰 ${translations[currentLang].emotions.anxious}</option>
          <option value="excited">🤩 ${translations[currentLang].emotions.excited}</option>
          <option value="frustrated">😤 ${translations[currentLang].emotions.frustrated}</option>
          <option value="calm">😌 ${translations[currentLang].emotions.calm}</option>
          <option value="greedy">🤑 ${translations[currentLang].emotions.greedy}</option>
        </select>
        <label for="tradeNotes">${tr.notes}</label>
        <textarea id="tradeNotes" placeholder="${tr.notesPlaceholder}"></textarea>
        <button type="submit" class="btn btn-primary">${tr.addTrade}</button>
      </form>
    </div>
  `;
  
  const existingTrade = document.getElementById('trade');
  if (existingTrade) existingTrade.remove();
  mainContent.appendChild(tradeSection);
  
  // Add form handler
  const tradeForm = document.getElementById('tradeForm');
  if (tradeForm) {
    tradeForm.addEventListener('submit', function(e) {
      e.preventDefault();
      
      let profitLoss = parseFloat(document.getElementById('tradePL').value) || 0;
      const tradeResult = document.getElementById('tradeResult').value;
      
      if (tradeResult === 'loss' && profitLoss > 0) {
        profitLoss = -profitLoss;
      }
      
      allData.push({
        id: generateId(),
        type: 'trade',
        date: document.getElementById('tradeDate').value,
        asset: document.getElementById('tradeAsset').value,
        lot_size: parseFloat(document.getElementById('tradeLot').value) || 0,
        result: tradeResult,
        profit_loss: profitLoss,
        entry_price: parseFloat(document.getElementById('tradeEntry').value) || 0,
        exit_price: parseFloat(document.getElementById('tradeExit').value) || 0,
        strategy: document.getElementById('tradeStrategy').value || '',
        notes: document.getElementById('tradeNotes').value || '',
        emotion: document.getElementById('tradeEmotion').value || ''
      });
      
      saveToLocalStorage();
      updateAll();
      showToast(t('messages.tradeAdded'), 'success');
      this.reset();
      document.getElementById('tradeDate').value = new Date().toISOString().split('T')[0];
    });
  }
  
  // Set default date
  const tradeDateField = document.getElementById('tradeDate');
  if (tradeDateField) {
    tradeDateField.value = new Date().toISOString().split('T')[0];
  }
}

function renderHistoryPage() {
  const h = translations[currentLang].history;
  const mainContent = document.getElementById('mainContent');
  
  const historySection = document.createElement('section');
  historySection.id = 'history';
  historySection.className = 'section';
  historySection.innerHTML = `
    <h2 style="margin-bottom:1.5rem">📜 ${h.title}</h2>
    <div class="card">
      <div class="table-container">
        <div id="historyContent"></div>
      </div>
    </div>
  `;
  
  const existingHistory = document.getElementById('history');
  if (existingHistory) existingHistory.remove();
  mainContent.appendChild(historySection);
}

function renderPerformancePage() {
  const p = translations[currentLang].performance;
  const mainContent = document.getElementById('mainContent');
  
  const performanceSection = document.createElement('section');
  performanceSection.id = 'performance';
  performanceSection.className = 'section';
  performanceSection.innerHTML = `
    <h2 style="margin-bottom:1.5rem">📈 ${p.title}</h2>
    <div class="card">
      <div class="card-title">📊 ${p.metrics}</div>
      <div id="performanceStats"></div>
    </div>
    <div class="grid grid-2">
      <div class="card">
        <div class="card-title">🎯 ${p.assetDistribution}</div>
        <div class="chart-sm"><canvas id="assetChart"></canvas></div>
      </div>
      <div class="card">
        <div class="card-title">🏆 ${p.assetPerformance}</div>
        <div class="chart-sm"><canvas id="assetPerformanceChart"></canvas></div>
      </div>
    </div>
    <div class="card">
      <div class="card-title">📈 ${p.monthlyPerformance}</div>
      <div class="chart"><canvas id="monthlyChart"></canvas></div>
    </div>
  `;
  
  const existingPerformance = document.getElementById('performance');
  if (existingPerformance) existingPerformance.remove();
  mainContent.appendChild(performanceSection);
}

function renderEmotionsPage() {
  const e = translations[currentLang].emotions;
  const mainContent = document.getElementById('mainContent');
  
  const emotionsSection = document.createElement('section');
  emotionsSection.id = 'emotions';
  emotionsSection.className = 'section';
  emotionsSection.innerHTML = `
    <h2 style="margin-bottom:1.5rem">🎭 ${e.title}</h2>
    <div class="card">
      <form id="emotionForm">
        <label for="emotionDate">${e.date}</label>
        <input type="date" id="emotionDate" required>
        <label>${e.selectEmotion}</label>
        <div class="emotion-grid">
          <button type="button" class="emotion-btn" data-emotion="confident">
            <span class="emotion-icon">😎</span>${e.confident}
          </button>
          <button type="button" class="emotion-btn" data-emotion="anxious">
            <span class="emotion-icon">😰</span>${e.anxious}
          </button>
          <button type="button" class="emotion-btn" data-emotion="excited">
            <span class="emotion-icon">🤩</span>${e.excited}
          </button>
          <button type="button" class="emotion-btn" data-emotion="frustrated">
            <span class="emotion-icon">😤</span>${e.frustrated}
          </button>
          <button type="button" class="emotion-btn" data-emotion="calm">
            <span class="emotion-icon">😌</span>${e.calm}
          </button>
          <button type="button" class="emotion-btn" data-emotion="greedy">
            <span class="emotion-icon">🤑</span>${e.greedy}
          </button>
        </div>
        <label for="emotionIntensity">${e.intensity}</label>
        <input type="range" min="1" max="10" value="5" id="emotionIntensity">
        <div style="text-align:center;color:var(--muted);margin-top:0.5rem">
          <span id="intensityValue">5</span> / 10
        </div>
        <label for="emotionNotes">${e.notes}</label>
        <textarea id="emotionNotes" placeholder="${e.notesPlaceholder}"></textarea>
        <button type="submit" class="btn btn-primary">${e.save}</button>
      </form>
    </div>
    <div id="emotionHistory" style="margin-top:1.5rem"></div>
  `;
  
  const existingEmotions = document.getElementById('emotions');
  if (existingEmotions) existingEmotions.remove();
  mainContent.appendChild(emotionsSection);
  
  // Emotion buttons
  document.querySelectorAll('.emotion-btn').forEach(btn => {
    btn.addEventListener('click', function() {
      document.querySelectorAll('.emotion-btn').forEach(b => b.classList.remove('selected'));
      this.classList.add('selected');
      selectedEmotion = this.dataset.emotion;
    });
  });
  
  // Intensity slider
  const intensitySlider = document.getElementById('emotionIntensity');
  if (intensitySlider) {
    intensitySlider.addEventListener('input', function() {
      document.getElementById('intensityValue').textContent = this.value;
    });
  }
  
  // Form submission
  const emotionForm = document.getElementById('emotionForm');
  if (emotionForm) {
    emotionForm.addEventListener('submit', function(e) {
      e.preventDefault();
      
      if (!selectedEmotion) {
        showToast(t('messages.selectEmotion'), 'error');
        return;
      }
      
      allData.push({
        id: generateId(),
        type: 'emotion',
        date: document.getElementById('emotionDate').value,
        emotion: selectedEmotion,
        emotion_intensity: parseInt(document.getElementById('emotionIntensity').value),
        notes: document.getElementById('emotionNotes').value || ''
      });
      
      saveToLocalStorage();
      updateAll();
      showToast(t('messages.emotionSaved'), 'success');
      this.reset();
      document.querySelectorAll('.emotion-btn').forEach(b => b.classList.remove('selected'));
      selectedEmotion = '';
      document.getElementById('emotionIntensity').value = 5;
      document.getElementById('intensityValue').textContent = '5';
      document.getElementById('emotionDate').value = new Date().toISOString().split('T')[0];
    });
  }
  
  // Set default date
  const emotionDateField = document.getElementById('emotionDate');
  if (emotionDateField) {
    emotionDateField.value = new Date().toISOString().split('T')[0];
  }
}

function renderCompoundPage() {
  const c = translations[currentLang].compound;
  const mainContent = document.getElementById('mainContent');
  
  const compoundSection = document.createElement('section');
  compoundSection.id = 'goals';
  compoundSection.className = 'section';
  compoundSection.innerHTML = `
    <h2 style="margin-bottom:1.5rem">📊 ${c.title}</h2>
    
    <div class="card">
      <div class="card-title">📈 ${c.currentPerformance}</div>
      <div class="stat-grid" style="grid-template-columns:repeat(3,1fr)">
        <div class="stat">
          <div class="stat-label">${c.currentCapital}</div>
          <div class="stat-value profit" id="perfCurrentCapital">0€</div>
        </div>
        <div class="stat">
          <div class="stat-label">${c.avgMonthlyReturn}</div>
          <div class="stat-value" id="perfMonthlyReturn">0%</div>
        </div>
        <div class="stat">
          <div class="stat-label">${c.tradingSince}</div>
          <div class="stat-value" id="perfTradingSince">0 ${c.months}</div>
        </div>
      </div>
    </div>
    
    <div class="card">
      <div class="card-title">🧮 ${c.calculate}</div>
      <form id="compoundForm">
        <div class="form-grid">
          <div>
            <label for="compoundStartCapital">${c.startCapital}</label>
            <input type="number" step="0.01" id="compoundStartCapital" placeholder="10000" required inputmode="decimal">
          </div>
          <div>
            <label for="compoundMonthlyReturn">${c.monthlyReturn}</label>
            <input type="number" step="0.1" id="compoundMonthlyReturn" placeholder="5" required inputmode="decimal">
            <div style="font-size:0.75rem;color:var(--muted);margin-top:0.25rem">💡 ${c.yourCurrent}: <span id="hintMonthlyReturn">-</span></div>
          </div>
          <div>
            <label for="compoundMonths">${c.timeframe}</label>
            <input type="number" id="compoundMonths" placeholder="12" required inputmode="numeric">
          </div>
          <div>
            <label for="compoundWithdrawal">${c.monthlyWithdrawal}</label>
            <input type="number" step="0.01" id="compoundWithdrawal" placeholder="0" value="0" inputmode="decimal">
            <div style="font-size:0.75rem;color:var(--muted);margin-top:0.25rem">${c.optional}</div>
          </div>
        </div>
        <button type="submit" class="btn btn-primary">${c.calculateBtn}</button>
      </form>
    </div>
    
    <div id="compoundResults"></div>
  `;
  
  const existingCompound = document.getElementById('goals');
  if (existingCompound) existingCompound.remove();
  mainContent.appendChild(compoundSection);
  
  // Form submission
  const compoundForm = document.getElementById('compoundForm');
  if (compoundForm) {
    compoundForm.addEventListener('submit', handleCompoundCalculation);
  }
}

function handleCompoundCalculation(e) {
  e.preventDefault();
  const c = translations[currentLang].compound;
  
  const startCapital = parseFloat(document.getElementById('compoundStartCapital').value);
  const monthlyReturn = parseFloat(document.getElementById('compoundMonthlyReturn').value) / 100;
  const months = parseInt(document.getElementById('compoundMonths').value);
  const monthlyWithdrawal = parseFloat(document.getElementById('compoundWithdrawal').value) || 0;
  
  if (isNaN(startCapital) || isNaN(monthlyReturn) || isNaN(months) || startCapital <= 0 || months <= 0) {
    showToast(t('messages.fillAllFields'), 'error');
    return;
  }
  
  const labels = [];
  const capitalData = [];
  const withdrawalData = [];
  
  let currentCapital = startCapital;
  let totalWithdrawn = 0;
  
  labels.push('Start');
  capitalData.push(currentCapital);
  withdrawalData.push(0);
  
  for (let i = 1; i <= months; i++) {
    currentCapital = currentCapital * (1 + monthlyReturn);
    
    if (monthlyWithdrawal > 0) {
      currentCapital -= monthlyWithdrawal;
      totalWithdrawn += monthlyWithdrawal;
    }
    
    if (currentCapital < 0) currentCapital = 0;
    
    labels.push(`${currentLang === 'de' ? 'Monat' : currentLang === 'en' ? 'Month' : 'Mes'} ${i}`);
    capitalData.push(currentCapital);
    withdrawalData.push(totalWithdrawn);
  }
  
  const finalCapital = capitalData[capitalData.length - 1];
  const totalGrowth = finalCapital - startCapital + totalWithdrawn;
  const totalReturn = startCapital > 0 ? ((totalGrowth / startCapital) * 100) : 0;
  
  const resultsContainer = document.getElementById('compoundResults');
  
  resultsContainer.innerHTML = `
    <div class="card">
      <div class="card-title">📊 ${c.results}</div>
      <div class="stat-grid" style="grid-template-columns:repeat(2,1fr)">
        <div class="stat">
          <div class="stat-label">${c.finalCapital} ${months} ${c.months}</div>
          <div class="stat-value profit">${finalCapital.toFixed(2)}€</div>
        </div>
        <div class="stat">
          <div class="stat-label">${c.totalGrowth}</div>
          <div class="stat-value ${totalGrowth >= 0 ? 'profit' : 'loss'}">${totalGrowth >= 0 ? '+' : ''}${totalGrowth.toFixed(2)}€</div>
        </div>
        <div class="stat">
          <div class="stat-label">${c.totalReturn}</div>
          <div class="stat-value ${totalReturn >= 0 ? 'profit' : 'loss'}">${totalReturn >= 0 ? '+' : ''}${totalReturn.toFixed(1)}%</div>
        </div>
        ${monthlyWithdrawal > 0 ? `
        <div class="stat">
          <div class="stat-label">${c.totalWithdrawn}</div>
          <div class="stat-value loss">-${totalWithdrawn.toFixed(2)}€</div>
        </div>
        ` : '<div></div>'}
      </div>
      <div class="chart" style="margin-top:1.5rem">
        <canvas id="compoundChart"></canvas>
      </div>
    </div>
  `;
  
  const ctx = document.getElementById('compoundChart');
  if (charts.compound) charts.compound.destroy();
  
  const datasets = [{
    label: `💰 ${c.capitalGrowth}`,
    data: capitalData,
    borderColor: '#3b82f6',
    backgroundColor: 'rgba(59,130,246,0.1)',
    borderWidth: 3,
    pointRadius: 3,
    pointHoverRadius: 6,
    fill: true,
    tension: 0.3,
    yAxisID: 'y'
  }];
  
  if (monthlyWithdrawal > 0) {
    datasets.push({
      label: `💸 ${c.totalWithdrawn}`,
      data: withdrawalData,
      borderColor: '#ef4444',
      backgroundColor: 'rgba(239,68,68,0.05)',
      borderWidth: 2,
      borderDash: [5, 5],
      pointRadius: 2,
      pointHoverRadius: 5,
      fill: true,
      tension: 0.3,
      yAxisID: 'y'
    });
  }
  
  charts.compound = new Chart(ctx, {
    type: 'line',
    data: {
      labels: labels,
      datasets: datasets
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      interaction: { intersect: false, mode: 'index' },
      plugins: {
        legend: {
          labels: { color: '#e5e7eb', font: { size: 12 }, usePointStyle: true },
          position: 'top'
        },
        tooltip: {
          backgroundColor: 'rgba(21,27,46,0.95)',
          titleColor: '#e5e7eb',
          bodyColor: '#e5e7eb',
          borderColor: '#1f2937',
          borderWidth: 1,
          padding: 12,
          callbacks: {
            label: function(context) {
              return context.dataset.label + ': ' + context.parsed.y.toFixed(2) + '€';
            }
          }
        }
      },
      scales: {
        y: {
          type: 'linear',
          position: 'left',
          ticks: {
            color: '#6b7280',
            callback: function(value) {
              return value >= 1000 ? (value / 1000).toFixed(1) + 'k€' : value.toFixed(0) + '€';
            }
          },
          grid: { color: '#1f2937' }
        },
        x: {
          ticks: {
            color: '#6b7280',
            maxRotation: 45,
            minRotation: 0
          },
          grid: { display: false }
        }
      }
    }
  });
  
  showToast(t('messages.calculationSuccess'), 'success');
}

function renderWithdrawalsPage() {
  const w = translations[currentLang].withdrawals;
  const mainContent = document.getElementById('mainContent');
  
  const withdrawalsSection = document.createElement('section');
  withdrawalsSection.id = 'withdrawals';
  withdrawalsSection.className = 'section';
  withdrawalsSection.innerHTML = `
    <h2 style="margin-bottom:1.5rem">💸 ${w.title}</h2>
    <div class="card">
      <div class="card-title">${w.newWithdrawal}</div>
      <form id="withdrawalForm">
        <div class="form-grid">
          <div><label for="withdrawalDate">${w.date}</label><input type="date" id="withdrawalDate" required></div>
          <div><label for="withdrawalAmount">${w.amount}</label><input type="number" step="0.01" id="withdrawalAmount" placeholder="500" required inputmode="decimal"></div>
        </div>
        <label for="withdrawalNotes">${w.notes}</label>
        <textarea id="withdrawalNotes" placeholder="${w.notesPlaceholder}"></textarea>
        <button type="submit" class="btn btn-primary">${w.add}</button>
      </form>
    </div>
    <div id="withdrawalStats"></div>
    <div id="withdrawalHistory"></div>
  `;
  
  const existingWithdrawals = document.getElementById('withdrawals');
  if (existingWithdrawals) existingWithdrawals.remove();
  mainContent.appendChild(withdrawalsSection);
  
  // Form submission
  const withdrawalForm = document.getElementById('withdrawalForm');
  if (withdrawalForm) {
    withdrawalForm.addEventListener('submit', function(e) {
      e.preventDefault();
      
      allData.push({
        id: generateId(),
        type: 'withdrawal',
        date: document.getElementById('withdrawalDate').value,
        withdrawal_amount: parseFloat(document.getElementById('withdrawalAmount').value),
        notes: document.getElementById('withdrawalNotes').value || ''
      });
      
      saveToLocalStorage();
      updateAll();
      showToast(t('messages.withdrawalAdded'), 'success');
      this.reset();
      document.getElementById('withdrawalDate').value = new Date().toISOString().split('T')[0];
    });
  }
  
  // Set default date
  const withdrawalDateField = document.getElementById('withdrawalDate');
  if (withdrawalDateField) {
    withdrawalDateField.value = new Date().toISOString().split('T')[0];
  }
}

function renderEditModal() {
  const m = translations[currentLang].modals;
  const tr = translations[currentLang].trade;
  const e = translations[currentLang].emotions;
  
  const editModalContent = document.querySelector('#editModal .modal-content');
  if (editModalContent) {
    editModalContent.innerHTML = `
      <div class="modal-header">
        <h3 id="editModalTitle">${m.editTrade}</h3>
        <button class="modal-close" onclick="closeEditModal()">✕</button>
      </div>
      <form id="editTradeForm">
        <input type="hidden" id="editTradeId">
        <div class="form-grid">
          <div><label for="editTradeDate">${tr.date}</label><input type="date" id="editTradeDate" required></div>
          <div><label for="editTradeAsset">${tr.asset}</label><select id="editTradeAsset" required><option>EUR/USD</option><option>GBP/USD</option><option>USD/JPY</option><option>XAU/USD</option><option>BTC/USD</option></select></div>
          <div><label for="editTradeLot">${tr.lotSize}</label><input type="number" step="0.01" id="editTradeLot" required inputmode="decimal"></div>
          <div><label for="editTradeResult">${tr.result}</label><select id="editTradeResult" required><option value="win">${tr.win}</option><option value="loss">${tr.loss}</option><option value="breakeven">${tr.breakeven}</option></select></div>
          <div><label for="editTradePL">P/L (€)</label><input type="number" step="0.01" id="editTradePL" required inputmode="decimal"></div>
          <div><label for="editTradeEntry">Entry</label><input type="number" step="0.00001" id="editTradeEntry" required inputmode="decimal"></div>
          <div><label for="editTradeExit">Exit</label><input type="number" step="0.00001" id="editTradeExit" required inputmode="decimal"></div>
          <div><label for="editTradeStrategy">${tr.strategy}</label><input type="text" id="editTradeStrategy"></div>
        </div>
        <label for="editTradeEmotion">${tr.emotion}</label>
        <select id="editTradeEmotion">
          <option value="">${tr.noEmotion}</option>
          <option value="confident">😎 ${e.confident}</option>
          <option value="anxious">😰 ${e.anxious}</option>
          <option value="excited">🤩 ${e.excited}</option>
          <option value="frustrated">😤 ${e.frustrated}</option>
          <option value="calm">😌 ${e.calm}</option>
          <option value="greedy">🤑 ${e.greedy}</option>
        </select>
        <label for="editTradeNotes">${tr.notes}</label>
        <textarea id="editTradeNotes"></textarea>
        <button type="submit" class="btn btn-primary">${m.update}</button>
      </form>
    `;
  }
  
  // Form submission
  const editTradeForm = document.getElementById('editTradeForm');
  if (editTradeForm) {
    editTradeForm.addEventListener('submit', function(e) {
      e.preventDefault();
      
      const id = document.getElementById('editTradeId').value;
      const trade = allData.find(d => d.id === id);
      if (!trade) return;
      
      let profitLoss = parseFloat(document.getElementById('editTradePL').value);
      const tradeResult = document.getElementById('editTradeResult').value;
      
      if (tradeResult === 'loss' && profitLoss > 0) {
        profitLoss = -profitLoss;
      }
      
      trade.date = document.getElementById('editTradeDate').value;
      trade.asset = document.getElementById('editTradeAsset').value;
      trade.lot_size = parseFloat(document.getElementById('editTradeLot').value);
      trade.result = tradeResult;
      trade.profit_loss = profitLoss;
      trade.entry_price = parseFloat(document.getElementById('editTradeEntry').value);
      trade.exit_price = parseFloat(document.getElementById('editTradeExit').value);
      trade.strategy = document.getElementById('editTradeStrategy').value;
      trade.emotion = document.getElementById('editTradeEmotion').value;
      trade.notes = document.getElementById('editTradeNotes').value;
      
      saveToLocalStorage();
      updateAll();
      showToast(t('messages.tradeUpdated'), 'success');
      closeEditModal();
    });
  }
}

// Initialize
function initApp() {
  loadFromLocalStorage();
  renderUI();
  initMobileMenu();
  
  // Language selectors
  const langSelector = document.getElementById('languageSelector');
  const mobileLangSelector = document.getElementById('mobileLanguageSelector');
  
  if (langSelector) {
    langSelector.value = currentLang;
    langSelector.addEventListener('change', (e) => setLanguage(e.target.value));
  }
  
  if (mobileLangSelector) {
    mobileLangSelector.value = currentLang;
    mobileLangSelector.addEventListener('change', (e) => setLanguage(e.target.value));
  }
  
  // Navigation
  document.querySelectorAll('.nav-item').forEach(nav => {
    nav.addEventListener('click', () => {
      document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
      document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
      document.getElementById(nav.dataset.section).classList.add('active');
      nav.classList.add('active');
      
      // Close mobile menu
      if (sidebar) sidebar.classList.remove('open');
      if (mobileOverlay) mobileOverlay.classList.remove('show');
      
      updateAll();
    });
  });
  
  updateAll();
}

// Update All
function updateAll() {
  const cap = allData.find(d => d.type === 'capital');
  const startCapitalField = document.getElementById('startCapital');
  if (cap && startCapitalField) startCapitalField.value = cap.start_capital;
  updateDashboard();
  updateHistory();
  updatePerformance();
  updateEmotionHistory();
  updateCompoundCalculator();
  updateWithdrawals();
}

function updateDashboard() {
  const trades = allData.filter(d => d.type === 'trade');
  const withdrawals = allData.filter(d => d.type === 'withdrawal');
  const winTrades = trades.filter(t => (t.profit_loss || 0) > 0);
  const lossTrades = trades.filter(t => (t.profit_loss || 0) < 0);
  const winrate = trades.length > 0 ? ((winTrades.length / trades.length) * 100).toFixed(1) : 0;
  const totalPL = trades.reduce((sum, t) => sum + (t.profit_loss || 0), 0);
  const totalWithdrawals = withdrawals.reduce((sum, w) => sum + (w.withdrawal_amount || 0), 0);
  
  const capitalData = allData.find(d => d.type === 'capital');
  const startCapital = capitalData ? capitalData.start_capital : 0;
  const currentCapital = startCapital + totalPL - totalWithdrawals;
  
  let runningTotal = 0, maxDrawdown = 0, peak = 0;
  trades.forEach(t => {
    runningTotal += t.profit_loss || 0;
    if (runningTotal > peak) peak = runningTotal;
    const drawdown = peak - runningTotal;
    if (drawdown > maxDrawdown) maxDrawdown = drawdown;
  });
  
  const totalWins = winTrades.reduce((sum, t) => sum + (t.profit_loss || 0), 0);
  const totalLosses = Math.abs(lossTrades.reduce((sum, t) => sum + (t.profit_loss || 0), 0));
  const profitFactor = totalLosses > 0 ? (totalWins / totalLosses) : 0;
  
  const currentCapitalEl = document.getElementById('currentCapital');
  if (currentCapitalEl) {
    currentCapitalEl.textContent = currentCapital.toFixed(2) + '€';
    currentCapitalEl.className = 'stat-value ' + (currentCapital >= startCapital ? 'profit' : 'loss');
  }
  
  const totalTradesEl = document.getElementById('totalTrades');
  if (totalTradesEl) totalTradesEl.textContent = trades.length;
  
  const winrateEl = document.getElementById('winrate');
  if (winrateEl) winrateEl.textContent = winrate + '%';
  
  const totalPLEl = document.getElementById('totalPL');
  if (totalPLEl) {
    totalPLEl.textContent = totalPL.toFixed(2) + '€';
    totalPLEl.className = 'stat-value ' + (totalPL >= 0 ? 'profit' : 'loss');
  }
  
  const maxDrawdownEl = document.getElementById('maxDrawdown');
  if (maxDrawdownEl) maxDrawdownEl.textContent = '-' + maxDrawdown.toFixed(2) + '€';
  
  const profitFactorEl = document.getElementById('profitFactor');
  if (profitFactorEl) {
    profitFactorEl.textContent = profitFactor.toFixed(2);
    profitFactorEl.className = 'stat-value ' + (profitFactor >= 1 ? 'profit' : 'loss');
  }
  
  const totalWinsEl = document.getElementById('totalWins');
  if (totalWinsEl) totalWinsEl.textContent = '+' + totalWins.toFixed(2) + '€';
  
  const winCountEl = document.getElementById('winCount');
  if (winCountEl) winCountEl.textContent = winTrades.length;
  
  const totalLossesEl = document.getElementById('totalLosses');
  if (totalLossesEl) totalLossesEl.textContent = '-' + totalLosses.toFixed(2) + '€';
  
  const lossCountEl = document.getElementById('lossCount');
  if (lossCountEl) lossCountEl.textContent = lossTrades.length;
  
  const totalWithdrawalsEl = document.getElementById('totalWithdrawals');
  if (totalWithdrawalsEl) totalWithdrawalsEl.textContent = '-' + totalWithdrawals.toFixed(2) + '€';
  
  const withdrawalCountEl = document.getElementById('withdrawalCount');
  if (withdrawalCountEl) withdrawalCountEl.textContent = withdrawals.length;
  
  const totalIncomeEl = document.getElementById('totalIncome');
  if (totalIncomeEl) totalIncomeEl.textContent = '+' + totalWins.toFixed(2) + '€';
  
  const totalExpensesEl = document.getElementById('totalExpenses');
  if (totalExpensesEl) totalExpensesEl.textContent = '-' + (totalLosses + totalWithdrawals).toFixed(2) + '€';
  
  const netResult = totalWins - totalLosses - totalWithdrawals;
  const netResultEl = document.getElementById('netResult');
  if (netResultEl) {
    netResultEl.textContent = (netResult >= 0 ? '+' : '') + netResult.toFixed(2) + '€';
    netResultEl.className = netResult >= 0 ? 'profit' : 'loss';
  }
  
  updateEquityChart(trades);
}

function updateEquityChart(trades) {
  const ctx = document.getElementById('equityChart');
  if (!ctx) return;
  if (charts.equity) charts.equity.destroy();
  
  const capitalData = allData.find(d => d.type === 'capital');
  const startCapital = capitalData ? capitalData.start_capital : 0;
  
  if (trades.length === 0) {
    if (startCapital > 0) {
      charts.equity = new Chart(ctx, {
        type: 'line',
        data: {
          labels: ['Start'],
          datasets: [{
            label: currentLang === 'de' ? 'Kontostand' : currentLang === 'en' ? 'Account Balance' : 'Saldo de Cuenta',
            data: [startCapital],
            borderColor: '#3b82f6',
            backgroundColor: 'rgba(59,130,246,0.1)',
            fill: true,
            tension: 0.4,
            pointRadius: 6,
            pointHoverRadius: 8
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          plugins: {
            legend: { labels: { color: '#e5e7eb' } },
            tooltip: {
              callbacks: {
                label: function(context) {
                  const label = currentLang === 'de' ? 'Kontostand' : currentLang === 'en' ? 'Balance' : 'Saldo';
                  return label + ': ' + context.parsed.y.toFixed(2) + '€';
                }
              }
            }
          },
          scales: {
            y: {
              ticks: {
                color: '#6b7280',
                callback: function(value) {
                  return value.toFixed(0) + '€';
                }
              },
              grid: { color: '#1f2937' }
            },
            x: { ticks: { color: '#6b7280' }, grid: { color: '#1f2937' } }
          }
        }
      });
    } else {
      ctx.parentElement.innerHTML = `<div class="empty"><div class="empty-icon">📈</div><p>${currentLang === 'de' ? 'Bitte zuerst Startkapital eingeben' : currentLang === 'en' ? 'Please enter starting capital first' : 'Por favor ingresa el capital inicial primero'}</p></div>`;
    }
    return;
  }
  
  const sorted = [...trades].sort((a, b) => new Date(a.date) - new Date(b.date));
  const withdrawals = allData.filter(d => d.type === 'withdrawal').sort((a, b) => new Date(a.date) - new Date(b.date));
  
  const labels = ['Start'];
  const equityData = [startCapital];
  
  let currentEquity = startCapital;
  let tradeIndex = 0;
  let withdrawalIndex = 0;
  
  while (tradeIndex < sorted.length || withdrawalIndex < withdrawals.length) {
    const nextTrade = sorted[tradeIndex];
    const nextWithdrawal = withdrawals[withdrawalIndex];
    
    let useTradeNext = false;
    if (nextTrade && nextWithdrawal) {
      useTradeNext = new Date(nextTrade.date) <= new Date(nextWithdrawal.date);
    } else if (nextTrade) {
      useTradeNext = true;
    }
    
    if (useTradeNext) {
      currentEquity += nextTrade.profit_loss || 0;
      labels.push(new Date(nextTrade.date).toLocaleDateString(currentLang === 'de' ? 'de-DE' : currentLang === 'en' ? 'en-US' : 'es-ES'));
      equityData.push(currentEquity);
      tradeIndex++;
    } else if (nextWithdrawal) {
      currentEquity -= nextWithdrawal.withdrawal_amount || 0;
      labels.push(new Date(nextWithdrawal.date).toLocaleDateString(currentLang === 'de' ? 'de-DE' : currentLang === 'en' ? 'en-US' : 'es-ES') + ' 💸');
      equityData.push(currentEquity);
      withdrawalIndex++;
    }
  }
  
  charts.equity = new Chart(ctx, {
    type: 'line',
    data: {
      labels: labels,
      datasets: [{
        label: currentLang === 'de' ? 'Kontostand' : currentLang === 'en' ? 'Account Balance' : 'Saldo de Cuenta',
        data: equityData,
        borderColor: '#3b82f6',
        backgroundColor: 'rgba(59,130,246,0.1)',
        fill: true,
        tension: 0.4,
        pointRadius: 3,
        pointHoverRadius: 6
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: { labels: { color: '#e5e7eb' } },
        tooltip: {
          backgroundColor: 'rgba(21,27,46,0.95)',
          titleColor: '#e5e7eb',
          bodyColor: '#e5e7eb',
          borderColor: '#1f2937',
          borderWidth: 1,
          padding: 12,
          callbacks: {
            label: function(context) {
              const label = currentLang === 'de' ? 'Kontostand' : currentLang === 'en' ? 'Balance' : 'Saldo';
              return label + ': ' + context.parsed.y.toFixed(2) + '€';
            }
          }
        }
      },
      scales: {
        y: {
          ticks: {
            color: '#6b7280',
            callback: function(value) {
              return value.toFixed(0) + '€';
            }
          },
          grid: { color: '#1f2937' }
        },
        x: {
          ticks: {
            color: '#6b7280',
            maxRotation: 45,
            minRotation: 0
          },
          grid: { color: '#1f2937' }
        }
      }
    }
  });
}

function updateHistory() {
  const trades = allData.filter(d => d.type === 'trade').sort((a, b) => new Date(b.date) - new Date(a.date));
  const container = document.getElementById('historyContent');
  if (!container) return;
  
  const h = translations[currentLang].history;
  const tr = translations[currentLang].trade;
  const e = translations[currentLang].emotions;
  
  if (trades.length === 0) {
    container.innerHTML = `<div class="empty"><div class="empty-icon">📜</div><p>${h.noTrades}</p></div>`;
    return;
  }
  
  const emotionIcons = { confident: '😎', anxious: '😰', excited: '🤩', frustrated: '😤', calm: '😌', greedy: '🤑' };
  
  let html = `<table><thead><tr><th>${h.date}</th><th>${h.asset}</th><th>${h.lot}</th><th>${h.result}</th><th>${h.emotion}</th><th>P/L</th><th>${h.actions}</th></tr></thead><tbody>`;
  
  trades.forEach(trade => {
    const plValue = trade.profit_loss || 0;
    const isLoss = plValue < 0;
    const isWin = plValue > 0;
    const plClass = isLoss ? 'loss' : 'profit';
    const resultText = isLoss ? `❌ ${tr.loss}` : isWin ? `✅ ${tr.win}` : `➖ ${tr.breakeven}`;
    const emotionIcon = trade.emotion ? emotionIcons[trade.emotion] || '-' : '-';
    const displayValue = isLoss ? `${plValue.toFixed(2)}€` : isWin ? `+${plValue.toFixed(2)}€` : `${plValue.toFixed(2)}€`;
    html += `<tr>
      <td>${new Date(trade.date).toLocaleDateString(currentLang === 'de' ? 'de-DE' : currentLang === 'en' ? 'en-US' : 'es-ES')}</td>
      <td>${trade.asset || '-'}</td>
      <td>${trade.lot_size || '-'}</td>
      <td>${resultText}</td>
      <td style="font-size:1.5rem">${emotionIcon}</td>
      <td class="${plClass}">${displayValue}</td>
      <td>
        <button class="btn btn-sm btn-secondary" onclick="editTrade('${trade.id}')">${h.edit}</button>
        <button class="btn btn-sm btn-danger" onclick="deleteTrade('${trade.id}')">${h.delete}</button>
      </td>
    </tr>`;
  });
  
  html += '</tbody></table>';
  container.innerHTML = html;
}

function editTrade(id) {
  const trade = allData.find(d => d.id === id);
  if (!trade) return;
  
  document.getElementById('editTradeId').value = id;
  document.getElementById('editTradeDate').value = trade.date;
  document.getElementById('editTradeAsset').value = trade.asset;
  document.getElementById('editTradeLot').value = trade.lot_size;
  document.getElementById('editTradeResult').value = trade.result;
  document.getElementById('editTradePL').value = trade.profit_loss;
  document.getElementById('editTradeEntry').value = trade.entry_price;
  document.getElementById('editTradeExit').value = trade.exit_price;
  document.getElementById('editTradeStrategy').value = trade.strategy || '';
  document.getElementById('editTradeEmotion').value = trade.emotion || '';
  document.getElementById('editTradeNotes').value = trade.notes || '';
  
  document.getElementById('editModal').classList.add('show');
}

function closeEditModal() {
  document.getElementById('editModal').classList.remove('show');
}

function deleteTrade(id) {
  const m = translations[currentLang].modals;
  
  const deleteConfirm = document.createElement('div');
  deleteConfirm.style.cssText = 'position:fixed;top:50%;left:50%;transform:translate(-50%,-50%);background:var(--card);border:1px solid var(--border);border-radius:0.75rem;padding:1.5rem;z-index:10000;box-shadow:0 20px 50px rgba(0,0,0,0.7);max-width:90%;width:300px';
  deleteConfirm.innerHTML = `
    <div style="font-weight:600;margin-bottom:1rem;font-size:1.1rem">${m.deleteTrade}</div>
    <div style="display:flex;gap:0.75rem;margin-top:1rem">
      <button class="btn btn-danger" style="flex:1" id="confirmDeleteBtn">${m.confirm}</button>
      <button class="btn btn-secondary" style="flex:1" id="cancelDeleteBtn">${m.cancel}</button>
    </div>
  `;
  
  const overlay = document.createElement('div');
  overlay.style.cssText = 'position:fixed;inset:0;background:rgba(0,0,0,0.7);z-index:9999';
  
  document.body.appendChild(overlay);
  document.body.appendChild(deleteConfirm);
  
  document.getElementById('confirmDeleteBtn').onclick = () => {
    allData = allData.filter(d => d.id !== id);
    saveToLocalStorage();
    updateAll();
    showToast(t('messages.tradeDeleted'), 'success');
    overlay.remove();
    deleteConfirm.remove();
  };
  
  document.getElementById('cancelDeleteBtn').onclick = () => {
    overlay.remove();
    deleteConfirm.remove();
  };
  
  overlay.onclick = () => {
    overlay.remove();
    deleteConfirm.remove();
  };
}

function updatePerformance() {
  const trades = allData.filter(d => d.type === 'trade');
  const p = translations[currentLang].performance;
  const statsContainer = document.getElementById('performanceStats');
  
  if (!statsContainer) return;
  
  if (trades.length === 0) {
    statsContainer.innerHTML = `<div class="empty"><div class="empty-icon">📈</div><p>${p.noData}</p></div>`;
    return;
  }
  
  const winTrades = trades.filter(t => (t.profit_loss || 0) > 0);
  const lossTrades = trades.filter(t => (t.profit_loss || 0) < 0);
  const avgWin = winTrades.length > 0 ? winTrades.reduce((sum, t) => sum + (t.profit_loss || 0), 0) / winTrades.length : 0;
  const avgLoss = lossTrades.length > 0 ? lossTrades.reduce((sum, t) => sum + (t.profit_loss || 0), 0) / lossTrades.length : 0;
  const totalWins = winTrades.reduce((sum, t) => sum + (t.profit_loss || 0), 0);
  const totalLosses = Math.abs(lossTrades.reduce((sum, t) => sum + (t.profit_loss || 0), 0));
  const profitFactor = totalLosses !== 0 ? (totalWins / totalLosses) : 0;
  const bestTrade = winTrades.length > 0 ? Math.max(...winTrades.map(t => t.profit_loss || 0)) : 0;
  const worstTrade = lossTrades.length > 0 ? Math.min(...lossTrades.map(t => t.profit_loss || 0)) : 0;
  
  const totalPL = trades.reduce((sum, t) => sum + (t.profit_loss || 0), 0);
  const winrate = trades.length > 0 ? ((winTrades.length / trades.length) * 100) : 0;
  
  const sortedTrades = [...trades].sort((a, b) => new Date(a.date) - new Date(b.date));
  let currentStreak = 0;
  let streakType = null;
  let longestWinStreak = 0;
  let longestLossStreak = 0;
  let tempWinStreak = 0;
  let tempLossStreak = 0;
  
  sortedTrades.forEach(trade => {
    const isWin = (trade.profit_loss || 0) > 0;
    const isLoss = (trade.profit_loss || 0) < 0;
    
    if (isWin) {
      tempWinStreak++;
      tempLossStreak = 0;
      if (tempWinStreak > longestWinStreak) longestWinStreak = tempWinStreak;
    } else if (isLoss) {
      tempLossStreak++;
      tempWinStreak = 0;
      if (tempLossStreak > longestLossStreak) longestLossStreak = tempLossStreak;
    }
  });
  
  if (sortedTrades.length > 0) {
    const lastTrade = sortedTrades[sortedTrades.length - 1];
    const lastIsWin = (lastTrade.profit_loss || 0) > 0;
    const lastIsLoss = (lastTrade.profit_loss || 0) < 0;
    
    if (lastIsWin) {
      streakType = 'win';
      currentStreak = tempWinStreak;
    } else if (lastIsLoss) {
      streakType = 'loss';
      currentStreak = tempLossStreak;
    }
  }
  
  statsContainer.innerHTML = `
    <div class="stat-grid" style="grid-template-columns:repeat(3,1fr)">
      <div class="stat"><div class="stat-label">${p.totalPL}</div><div class="stat-value ${totalPL >= 0 ? 'profit' : 'loss'}">${totalPL >= 0 ? '+' : ''}${totalPL.toFixed(2)}€</div></div>
      <div class="stat"><div class="stat-label">${p.avgWin}</div><div class="stat-value profit">+${avgWin.toFixed(2)}€</div></div>
      <div class="stat"><div class="stat-label">${p.avgLoss}</div><div class="stat-value loss">${avgLoss.toFixed(2)}€</div></div>
      <div class="stat"><div class="stat-label">${p.winrate}</div><div class="stat-value ${winrate >= 50 ? 'profit' : ''}">${winrate.toFixed(1)}%</div></div>
      <div class="stat"><div class="stat-label">${p.profitFactor}</div><div class="stat-value">${profitFactor.toFixed(2)}</div></div>
      <div class="stat"><div class="stat-label">${p.trades}</div><div class="stat-value">${trades.length}</div></div>
      <div class="stat"><div class="stat-label">${p.bestTrade}</div><div class="stat-value profit">+${bestTrade.toFixed(2)}€</div></div>
      <div class="stat"><div class="stat-label">${p.worstTrade}</div><div class="stat-value loss">${worstTrade.toFixed(2)}€</div></div>
      <div class="stat"><div class="stat-label">${p.currentStreak}</div><div class="stat-value ${streakType === 'win' ? 'profit' : streakType === 'loss' ? 'loss' : ''}">${currentStreak > 0 ? (streakType === 'win' ? '✅ ' : '❌ ') + currentStreak : '-'}</div></div>
    </div>
    
    <div style="margin-top:1.5rem;padding:1.25rem;background:rgba(59,130,246,0.05);border:1px solid var(--border);border-radius:0.75rem">
      <div style="font-weight:600;font-size:1rem;margin-bottom:1rem">🔥 ${p.streaksTitle}</div>
      <div class="stat-grid" style="grid-template-columns:repeat(2,1fr)">
        <div style="padding:1rem;background:rgba(16,185,129,0.1);border:1px solid var(--success);border-radius:0.75rem">
          <div style="font-size:0.875rem;color:var(--muted);margin-bottom:0.5rem">✅ ${p.longestWinStreak}</div>
          <div style="font-size:2rem;font-weight:700;color:var(--success)">${longestWinStreak}</div>
          <div style="font-size:0.75rem;color:var(--muted);margin-top:0.25rem">${p.consecutiveWins}</div>
        </div>
        <div style="padding:1rem;background:rgba(239,68,68,0.1);border:1px solid var(--danger);border-radius:0.75rem">
          <div style="font-size:0.875rem;color:var(--muted);margin-bottom:0.5rem">❌ ${p.longestLossStreak}</div>
          <div style="font-size:2rem;font-weight:700;color:var(--danger)">${longestLossStreak}</div>
          <div style="font-size:0.75rem;color:var(--muted);margin-top:0.25rem">${p.consecutiveLosses}</div>
        </div>
      </div>
      ${currentStreak > 0 ? `
        <div style="margin-top:1rem;padding:1rem;background:rgba(59,130,246,0.05);border-radius:0.5rem;text-align:center">
          <div style="font-size:0.875rem;color:var(--muted)">${p.currentlyIn}</div>
          <div style="font-size:1.25rem;font-weight:700;margin-top:0.25rem;color:${streakType === 'win' ? 'var(--success)' : 'var(--danger)'}">
            ${streakType === 'win' ? '✅' : '❌'} ${currentStreak} ${streakType === 'win' ? p.winningStreak : p.losingStreak}
          </div>
        </div>
      ` : ''}
    </div>
  `;
  
  updateMonthlyChart(trades);
  updateAssetChart(trades);
  updateAssetPerformanceChart(trades);
}

function updateAssetPerformanceChart(trades) {
  const ctx = document.getElementById('assetPerformanceChart');
  if (!ctx) return;
  if (charts.assetPerformance) charts.assetPerformance.destroy();
  
  const p = translations[currentLang].performance;
  
  if (trades.length === 0) {
    ctx.parentElement.innerHTML = `<div class="empty"><div class="empty-icon">🏆</div><p>${p.noData}</p></div>`;
    return;
  }
  
  const assetPL = {};
  trades.forEach(t => {
    if (t.asset) {
      assetPL[t.asset] = (assetPL[t.asset] || 0) + (t.profit_loss || 0);
    }
  });
  
  const sortedAssets = Object.entries(assetPL).sort((a, b) => b[1] - a[1]);
  const labels = sortedAssets.map(a => a[0]);
  const data = sortedAssets.map(a => a[1]);
  
  charts.assetPerformance = new Chart(ctx, {
    type: 'bar',
    data: {
      labels: labels,
      datasets: [{
        label: currentLang === 'de' ? 'Gewinn/Verlust' : currentLang === 'en' ? 'Profit/Loss' : 'Ganancia/Pérdida',
        data: data,
        backgroundColor: data.map(v => v >= 0 ? '#10b981' : '#ef4444')
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      indexAxis: 'y',
      plugins: { legend: { display: false } },
      scales: {
        x: { ticks: { color: '#6b7280', callback: v => v.toFixed(0) + '€' }, grid: { color: '#1f2937' } },
        y: { ticks: { color: '#6b7280', font: { size: 10 } }, grid: { color: '#1f2937' } }
      }
    }
  });
}

function updateMonthlyChart(trades) {
  const ctx = document.getElementById('monthlyChart');
  if (!ctx) return;
  if (charts.monthly) charts.monthly.destroy();
  
  const monthlyData = {};
  trades.forEach(t => {
    const date = new Date(t.date);
    const key = `${date.getFullYear()}-${String(date.getMonth() + 1).padStart(2, '0')}`;
    const label = date.toLocaleDateString(currentLang === 'de' ? 'de-DE' : currentLang === 'en' ? 'en-US' : 'es-ES', { year: '2-digit', month: 'short' });
    if (!monthlyData[key]) {
      monthlyData[key] = { label: label, value: 0 };
    }
    monthlyData[key].value += (t.profit_loss || 0);
  });
  
  const sorted = Object.keys(monthlyData).sort();
  const labels = sorted.map(k => monthlyData[k].label);
  const data = sorted.map(k => monthlyData[k].value);
  
  charts.monthly = new Chart(ctx, {
    type: 'bar',
    data: {
      labels: labels,
      datasets: [{
        label: currentLang === 'de' ? 'Monatliche P/L' : currentLang === 'en' ? 'Monthly P/L' : 'P/L Mensual',
        data: data,
        backgroundColor: data.map(v => v >= 0 ? '#10b981' : '#ef4444'),
        borderRadius: 6,
        maxBarThickness: 60
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: {
          labels: { color: '#e5e7eb', font: { size: 12 } },
          display: true
        },
        tooltip: {
          backgroundColor: 'rgba(21,27,46,0.95)',
          titleColor: '#e5e7eb',
          bodyColor: '#e5e7eb',
          borderColor: '#1f2937',
          borderWidth: 1,
          padding: 12,
          displayColors: true,
          callbacks: {
            label: function(context) {
              const value = context.parsed.y;
              return `${value >= 0 ? '+' : ''}${value.toFixed(2)}€`;
            }
          }
        }
      },
      scales: {
        y: {
          ticks: {
            color: '#6b7280',
            font: { size: 11 },
            callback: function(value) {
              return value.toFixed(0) + '€';
            }
          },
          grid: { color: '#1f2937', lineWidth: 1 }
        },
        x: {
          ticks: {
            color: '#6b7280',
            font: { size: 11 },
            maxRotation: 45,
            minRotation: 0
          },
          grid: { display: false }
        }
      }
    }
  });
}

function updateAssetChart(trades) {
  const ctx = document.getElementById('assetChart');
  if (!ctx) return;
  if (charts.asset) charts.asset.destroy();
  
  const assetData = {};
  trades.forEach(t => {
    assetData[t.asset] = (assetData[t.asset] || 0) + 1;
  });
  
  charts.asset = new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: Object.keys(assetData),
      datasets: [{
        data: Object.values(assetData),
        backgroundColor: ['#3b82f6', '#10b981', '#f59e0b', '#ef4444', '#8b5cf6', '#ec4899', '#14b8a6']
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: { legend: { labels: { color: '#e5e7eb' }, position: 'bottom' } }
    }
  });
}

function updateEmotionHistory() {
  const emotions = allData.filter(d => d.type === 'emotion').sort((a, b) => new Date(b.date) - new Date(a.date));
  const trades = allData.filter(d => d.type === 'trade' && d.emotion).sort((a, b) => new Date(b.date) - new Date(a.date));
  const container = document.getElementById('emotionHistory');
  if (!container) return;
  
  const e = translations[currentLang].emotions;
  const allEmotionEntries = [...emotions, ...trades].sort((a, b) => new Date(b.date) - new Date(a.date));
  
  if (allEmotionEntries.length === 0) {
    container.innerHTML = `<div class="card"><div class="empty"><div class="empty-icon">🎭</div><p>${e.noEmotions}</p></div></div>`;
    return;
  }
  
  const emotionIcons = { confident: '😎', anxious: '😰', excited: '🤩', frustrated: '😤', calm: '😌', greedy: '🤑' };
  const emotionLabels = {
    confident: e.confident,
    anxious: e.anxious,
    excited: e.excited,
    frustrated: e.frustrated,
    calm: e.calm,
    greedy: e.greedy
  };
  
  let html = '';
  allEmotionEntries.forEach(entry => {
    const isTradeEmotion = entry.type === 'trade';
    const emotion = entry.emotion;
    const emotionIntensity = entry.emotion_intensity || 0;
    
    if (isTradeEmotion) {
      const plValue = entry.profit_loss || 0;
      const plClass = plValue >= 0 ? 'profit' : 'loss';
      const plDisplay = plValue >= 0 ? `+${plValue.toFixed(2)}€` : `${plValue.toFixed(2)}€`;
      
      html += `<div class="card">
        <div class="goal-header">
          <div style="display:flex;align-items:center;gap:0.75rem;flex:1">
            <span style="font-size:2rem">${emotionIcons[emotion]}</span>
            <div style="flex:1">
              <div style="font-weight:600">${emotionLabels[emotion]}</div>
              <div style="font-size:0.875rem;color:var(--muted)">${new Date(entry.date).toLocaleDateString(currentLang === 'de' ? 'de-DE' : currentLang === 'en' ? 'en-US' : 'es-ES')} • Trade: ${entry.asset || 'N/A'}</div>
            </div>
          </div>
          <div style="text-align:right">
            <div class="${plClass}" style="font-weight:700;font-size:1.1rem">${plDisplay}</div>
            <div style="font-size:0.75rem;color:var(--muted)">Lot: ${entry.lot_size || '-'}</div>
          </div>
        </div>
        ${entry.notes ? `<p style="margin-top:0.75rem;color:var(--muted);font-size:0.875rem;padding:0.75rem;background:rgba(59,130,246,0.05);border-radius:0.5rem">${entry.notes}</p>` : ''}
        <div style="margin-top:0.75rem;padding-top:0.75rem;border-top:1px solid var(--border);font-size:0.75rem;color:var(--muted)">📊 ${e.fromHistory}</div>
      </div>`;
    } else {
      const m = translations[currentLang].modals;
      html += `<div class="card">
        <div class="goal-header">
          <div style="display:flex;align-items:center;gap:0.75rem">
            <span style="font-size:2rem">${emotionIcons[emotion]}</span>
            <div>
              <div style="font-weight:600">${emotionLabels[emotion]}</div>
              <div style="font-size:0.875rem;color:var(--muted)">${new Date(entry.date).toLocaleDateString(currentLang === 'de' ? 'de-DE' : currentLang === 'en' ? 'en-US' : 'es-ES')}</div>
            </div>
          </div>
          <button class="btn btn-sm btn-danger" onclick="deleteEmotion('${entry.id}')">${translations[currentLang].history.delete}</button>
        </div>
        <div class="progress-bar">
          <div class="progress-fill" style="width:${emotionIntensity * 10}%"></div>
        </div>
        <div style="font-size:0.875rem;color:var(--muted)">${e.intensity.split(' ')[0]}: ${emotionIntensity}/10</div>
        ${entry.notes ? `<p style="margin-top:0.75rem;color:var(--muted);font-size:0.875rem">${entry.notes}</p>` : ''}
      </div>`;
    }
  });
  
  container.innerHTML = html;
}

function deleteEmotion(id) {
  const m = translations[currentLang].modals;
  
  const deleteConfirm = document.createElement('div');
  deleteConfirm.style.cssText = 'position:fixed;top:50%;left:50%;transform:translate(-50%,-50%);background:var(--card);border:1px solid var(--border);border-radius:0.75rem;padding:1.5rem;z-index:10000;box-shadow:0 20px 50px rgba(0,0,0,0.7);max-width:90%;width:300px';
  deleteConfirm.innerHTML = `
    <div style="font-weight:600;margin-bottom:1rem;font-size:1.1rem">${m.deleteEmotion}</div>
    <div style="display:flex;gap:0.75rem;margin-top:1rem">
      <button class="btn btn-danger" style="flex:1" id="confirmDeleteEmotionBtn">${m.confirm}</button>
      <button class="btn btn-secondary" style="flex:1" id="cancelDeleteEmotionBtn">${m.cancel}</button>
    </div>
  `;
  
  const overlay = document.createElement('div');
  overlay.style.cssText = 'position:fixed;inset:0;background:rgba(0,0,0,0.7);z-index:9999';
  
  document.body.appendChild(overlay);
  document.body.appendChild(deleteConfirm);
  
  document.getElementById('confirmDeleteEmotionBtn').onclick = () => {
    allData = allData.filter(d => d.id !== id);
    saveToLocalStorage();
    updateAll();
    showToast(t('messages.emotionDeleted'), 'success');
    overlay.remove();
    deleteConfirm.remove();
  };
  
  document.getElementById('cancelDeleteEmotionBtn').onclick = () => {
    overlay.remove();
    deleteConfirm.remove();
  };
  
  overlay.onclick = () => {
    overlay.remove();
    deleteConfirm.remove();
  };
}

function updateCompoundCalculator() {
  const trades = allData.filter(d => d.type === 'trade').sort((a, b) => new Date(a.date) - new Date(b.date));
  const withdrawals = allData.filter(d => d.type === 'withdrawal');
  const capitalData = allData.find(d => d.type === 'capital');
  const startCapital = capitalData ? capitalData.start_capital : 0;
  const totalPL = trades.reduce((sum, t) => sum + (t.profit_loss || 0), 0);
  const totalWithdrawals = withdrawals.reduce((sum, w) => sum + (w.withdrawal_amount || 0), 0);
  const currentCapital = startCapital + totalPL - totalWithdrawals;
  
  const perfCurrentCapitalEl = document.getElementById('perfCurrentCapital');
  if (perfCurrentCapitalEl) perfCurrentCapitalEl.textContent = currentCapital.toFixed(2) + '€';
  
  const c = translations[currentLang].compound;
  
  if (trades.length > 0 && startCapital > 0) {
    const firstTradeDate = new Date(trades[0].date);
    const today = new Date();
    const daysDiff = Math.max(1, Math.ceil((today - firstTradeDate) / (864e5)));
    const monthsElapsed = daysDiff / 30;
    
    const monthlyReturn = monthsElapsed > 0 ? (Math.pow(currentCapital / startCapital, 1 / monthsElapsed) - 1) * 100 : 0;
    
    const perfMonthlyReturnEl = document.getElementById('perfMonthlyReturn');
    if (perfMonthlyReturnEl) {
      perfMonthlyReturnEl.textContent = monthlyReturn.toFixed(2) + '%';
      perfMonthlyReturnEl.className = 'stat-value ' + (monthlyReturn >= 0 ? 'profit' : 'loss');
    }
    
    const perfTradingSinceEl = document.getElementById('perfTradingSince');
    if (perfTradingSinceEl) perfTradingSinceEl.textContent = Math.floor(monthsElapsed) + ' ' + c.months;
    
    const hintMonthlyReturnEl = document.getElementById('hintMonthlyReturn');
    if (hintMonthlyReturnEl) hintMonthlyReturnEl.textContent = monthlyReturn.toFixed(2) + '%';
    
    const compoundStartCapitalEl = document.getElementById('compoundStartCapital');
    if (compoundStartCapitalEl) compoundStartCapitalEl.value = currentCapital.toFixed(2);
    
    const compoundMonthlyReturnEl = document.getElementById('compoundMonthlyReturn');
    if (compoundMonthlyReturnEl) compoundMonthlyReturnEl.value = monthlyReturn.toFixed(2);
  } else {
    const perfMonthlyReturnEl = document.getElementById('perfMonthlyReturn');
    if (perfMonthlyReturnEl) perfMonthlyReturnEl.textContent = '0%';
    
    const perfTradingSinceEl = document.getElementById('perfTradingSince');
    if (perfTradingSinceEl) perfTradingSinceEl.textContent = '0 ' + c.months;
    
    const hintMonthlyReturnEl = document.getElementById('hintMonthlyReturn');
    if (hintMonthlyReturnEl) hintMonthlyReturnEl.textContent = '-';
    
    if (currentCapital > 0) {
      const compoundStartCapitalEl = document.getElementById('compoundStartCapital');
      if (compoundStartCapitalEl) compoundStartCapitalEl.value = currentCapital.toFixed(2);
    }
  }
}

function updateWithdrawals() {
  const withdrawals = allData.filter(d => d.type === 'withdrawal').sort((a, b) => new Date(b.date) - new Date(a.date));
  const totalWithdrawals = withdrawals.reduce((sum, w) => sum + (w.withdrawal_amount || 0), 0);
  
  const w = translations[currentLang].withdrawals;
  
  const withdrawalStatsEl = document.getElementById('withdrawalStats');
  if (withdrawalStatsEl) {
    withdrawalStatsEl.innerHTML = `
      <div class="card">
        <div class="stat-grid" style="grid-template-columns:repeat(2,1fr)">
          <div class="stat"><div class="stat-label">${w.total}</div><div class="stat-value loss">-${totalWithdrawals.toFixed(2)}€</div></div>
          <div class="stat"><div class="stat-label">${w.count}</div><div class="stat-value">${withdrawals.length}</div></div>
        </div>
      </div>
    `;
  }
  
  const container = document.getElementById('withdrawalHistory');
  if (!container) return;
  
  if (withdrawals.length === 0) {
    container.innerHTML = `<div class="card"><div class="empty"><div class="empty-icon">💸</div><p>${w.noWithdrawals}</p></div></div>`;
    return;
  }
  
  let html = `<div class="card"><div class="table-container"><table><thead><tr><th>${w.date}</th><th>${w.amount}</th><th>${w.notes}</th><th></th></tr></thead><tbody>`;
  
  withdrawals.forEach(withdrawal => {
    html += `<tr>
      <td>${new Date(withdrawal.date).toLocaleDateString(currentLang === 'de' ? 'de-DE' : currentLang === 'en' ? 'en-US' : 'es-ES')}</td>
      <td class="loss">-${withdrawal.withdrawal_amount.toFixed(2)}€</td>
      <td>${withdrawal.notes || '-'}</td>
      <td><button class="btn btn-sm btn-danger" onclick="deleteWithdrawal('${withdrawal.id}')">${translations[currentLang].history.delete}</button></td>
    </tr>`;
  });
  
  html += '</tbody></table></div></div>';
  container.innerHTML = html;
}

function deleteWithdrawal(id) {
  const m = translations[currentLang].modals;
  
  const deleteConfirm = document.createElement('div');
  deleteConfirm.style.cssText = 'position:fixed;top:50%;left:50%;transform:translate(-50%,-50%);background:var(--card);border:1px solid var(--border);border-radius:0.75rem;padding:1.5rem;z-index:10000;box-shadow:0 20px 50px rgba(0,0,0,0.7);max-width:90%;width:300px';
  deleteConfirm.innerHTML = `
    <div style="font-weight:600;margin-bottom:1rem;font-size:1.1rem">${m.deleteWithdrawal}</div>
    <div style="display:flex;gap:0.75rem;margin-top:1rem">
      <button class="btn btn-danger" style="flex:1" id="confirmDeleteWithdrawalBtn">${m.confirm}</button>
      <button class="btn btn-secondary" style="flex:1" id="cancelDeleteWithdrawalBtn">${m.cancel}</button>
    </div>
  `;
  
  const overlay = document.createElement('div');
  overlay.style.cssText = 'position:fixed;inset:0;background:rgba(0,0,0,0.7);z-index:9999';
  
  document.body.appendChild(overlay);
  document.body.appendChild(deleteConfirm);
  
  document.getElementById('confirmDeleteWithdrawalBtn').onclick = () => {
    allData = allData.filter(d => d.id !== id);
    saveToLocalStorage();
    updateAll();
    showToast(t('messages.withdrawalDeleted'), 'success');
    overlay.remove();
    deleteConfirm.remove();
  };
  
  document.getElementById('cancelDeleteWithdrawalBtn').onclick = () => {
    overlay.remove();
    deleteConfirm.remove();
  };
  
  overlay.onclick = () => {
    overlay.remove();
    deleteConfirm.remove();
  };
}

function showToast(message, type = 'success') {
  const toast = document.createElement('div');
  toast.className = `toast ${type}`;
  toast.textContent = message;
  document.body.appendChild(toast);
  setTimeout(() => {
    toast.style.animation = 'slideIn 0.3s reverse';
    setTimeout(() => toast.remove(), 300);
  }, 3000);
}

// Initialize app on load
document.addEventListener('DOMContentLoaded', initApp);

// Close modal on backdrop click
document.getElementById('editModal').addEventListener('click', function(e) {
  if (e.target === this) closeEditModal();
});
</script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9b6cec82d447e0d3',t:'MTc2NzIxNzEwNi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
