{
  "version": "4.5-final",
  "scannedAt": "2026-03-24T00:13:49.208Z",
  "subject": "compass.html (inline JavaScript)",
  "note": "DST v4.5 applied to its own Compass diagnostic engine — the tool measures itself.",
  "theta": 0,
  "apparent": 100,
  "obsGap": 100,
  "obsGapSeverity": "critical",
  "regime": "Residual",
  "regimeDesc": "System in delayed failure. Refactor before adding anything.",
  "warning": {
    "icon": "🔴",
    "title": "CRITICAL: RESIDUAL REGIME — STRUCTURAL FAILURE EMBEDDED",
    "lines": [
      "κ is exhausted or near κ_max — masking is no longer effective",
      "Θ → 0: the system is in delayed failure mode",
      "New features will accelerate cascade, not delay it"
    ],
    "action": "STOP adding features. Initiate structural repair immediately. The next incident will not be gradual."
  },
  "dThetaDt": null,
  "direction": "unknown",
  "regimePred": null,
  "sigmaEff": 0,
  "sigmaHidden": 0,
  "kappaSat": 92,
  "riskScore": 100,
  "riskLevel": "CRITICAL",
  "kappaCount": 31,
  "sigmaCount": 0,
  "rhoCount": 21,
  "secCount": 1,
  "fileCount": 1,
  "linesScanned": 1172,
  "rewriteSignal": {
    "triggered": true,
    "criticalModules": [
      {
        "file": "compass.html",
        "score": 0,
        "findings": 32
      }
    ],
    "message": "Local modification is becoming infeasible. Structural replacement of these modules is the mathematically indicated intervention."
  },
  "actionSummary": {
    "fixTotal": 4,
    "mitigateTotal": 0,
    "acceptTotal": 0,
    "amplifyTotal": 0,
    "expiredKappaI": 0
  },
  "annualCost": 156115,
  "paybackMonths": 1.6,
  "fiveYearROI": 3658,
  "findings": [
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 509,
      "code": "if (!contradictions.length) { wrap.innerHTML = ''; return; }",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 510,
      "code": "wrap.innerHTML = `",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 575,
      "code": "document.getElementById('m-kappa').style.width  = kapScore + '%';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 576,
      "code": "document.getElementById('m-theta').style.width  = thetaScore + '%';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 577,
      "code": "document.getElementById('m-damage').style.width = dScore + '%';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 578,
      "code": "document.getElementById('m-rho').style.width    = rhoScore + '%';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 757,
      "code": "if (content) content.style.filter = 'none';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 758,
      "code": "if (content) content.style.color = 'rgba(245,240,232,0.85)';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 769,
      "code": "document.getElementById('premium-gate').style.display = 'none';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 795,
      "code": "document.getElementById('premium-content').style.display = 'block';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 803,
      "code": "if (err) { errBox.textContent = '⚠ ' + err; errBox.classList.add('show",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 833,
      "code": "statusEl.textContent = st.text;",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 834,
      "code": "statusEl.className = 'system-status-strip ' + st.cls;",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 835,
      "code": "statusEl.style.display = 'block';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 841,
      "code": "scoreEl.textContent=visualScore;",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 842,
      "code": "scoreEl.className=`score-number ${scoreColorClass(S.dstScore)}`;",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 844,
      "code": "fill.style.background=scoreBarColor(S.dstScore);",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 872,
      "code": "frLabel.innerHTML = `FINAL REGIME: <strong style=\"color:var(--gold)\">$",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 891,
      "code": "if (hslEl) { hslEl.textContent = hsl[S.regime.detected] || hsl.Elastic",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 893,
      "code": "if (hslWrap) hslWrap.style.display = 'block';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 945,
      "code": "document.getElementById('stage1-output').style.display='block';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 955,
      "code": "document.getElementById('ai-wrap').style.display = 'block';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 957,
      "code": "document.getElementById('ai-result').style.display = 'none';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 975,
      "code": "document.getElementById('ai-result').style.display = 'block';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "triple_normalizer",
      "severity": "medium",
      "line": 1101,
      "code": "const structLbl = (S.regime.structural||S.regime.user||S.regime.detect",
      "fix": "Normalize at the API/DB boundary once. Consumers receive a consistent shape.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "implicit_state",
      "severity": "high",
      "line": 1141,
      "code": "document.getElementById('stage2-output').style.display = 'block';",
      "fix": "Return new state instead of mutating. Make side effects explicit.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "sql_concat",
      "severity": "critical",
      "line": 290,
      "code": "body: `The system looks functional because ${kap} is compensating for ",
      "fix": "Use parameterized queries or an ORM. Never concatenate user input into SQL.",
      "category": "security",
      "kappaType": "security",
      "action": "REVIEW"
    },
    {
      "type": "large_file",
      "severity": "low",
      "line": 1,
      "code": "1172 lines",
      "fix": "Split by responsibility. A file should have one reason to change.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "god_function",
      "severity": "high",
      "line": 432,
      "code": "function buildAIPrompt(v,  regime,  conf, ...)",
      "fix": "Split by responsibility. Each function should have one reason to change.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "god_function",
      "severity": "high",
      "line": 739,
      "code": "function unlockPremiumV6()",
      "fix": "Split by responsibility. Each function should have one reason to change.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "god_function",
      "severity": "high",
      "line": 798,
      "code": "function runDiagnosis()",
      "fix": "Split by responsibility. Each function should have one reason to change.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    },
    {
      "type": "god_function",
      "severity": "high",
      "line": 1071,
      "code": "function runStage2()",
      "fix": "Split by responsibility. Each function should have one reason to change.",
      "category": "kappa",
      "kappaType": "accumulated",
      "action": "FIX"
    }
  ]
}
