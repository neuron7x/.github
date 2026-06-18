<div align="center">

<svg width="860" height="180" viewBox="0 0 860 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&amp;display=swap');
      .mono { font-family: 'JetBrains Mono', 'Courier New', monospace; }
    </style>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <linearGradient id="fadeH" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#FF6600;stop-opacity:0"/>
      <stop offset="20%" style="stop-color:#FF6600;stop-opacity:1"/>
      <stop offset="80%" style="stop-color:#FF6600;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#FF6600;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="scan" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#FF6600;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#FF6600;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#FF6600;stop-opacity:0"/>
    </linearGradient>
  </defs>

  <!-- background -->
  <rect width="860" height="180" fill="#0a0a0a" rx="4"/>

  <!-- scan line animation -->
  <rect width="860" height="60" fill="url(#scan)" rx="0">
    <animateTransform attributeName="transform" type="translate" from="0,-60" to="0,180"
      dur="4s" repeatCount="indefinite"/>
  </rect>

  <!-- top rule -->
  <rect x="40" y="28" width="780" height="1" fill="url(#fadeH)" opacity="0.6"/>

  <!-- ⊛ symbol -->
  <text x="430" y="72" text-anchor="middle" class="mono"
    font-size="28" font-weight="700" fill="#FF6600" filter="url(#glow)"
    letter-spacing="2">
    ⊛
    <animate attributeName="opacity" values="1;0.4;1" dur="3s" repeatCount="indefinite"/>
  </text>

  <!-- name -->
  <text x="430" y="110" text-anchor="middle" class="mono"
    font-size="22" font-weight="700" fill="#FAFAFA" letter-spacing="6">
    YAROSLAV VASYLENKO
  </text>

  <!-- tagline -->
  <text x="430" y="136" text-anchor="middle" class="mono"
    font-size="11" fill="#666666" letter-spacing="4">
    NEURON7XLAB · POLTAVA · UKRAINE
  </text>

  <!-- axiom -->
  <text x="430" y="158" text-anchor="middle" class="mono"
    font-size="10" fill="#444444" letter-spacing="1">
    where information is computed and interpreted — intelligence exists
  </text>

  <!-- bottom rule -->
  <rect x="40" y="168" width="780" height="1" fill="url(#fadeH)" opacity="0.6"/>
</svg>

</div>

<br>

```
⊛════════════════════════════════════════════════════════════════════════⊛
  computational neuroscience  ·  AI systems architecture  ·  quant finance
  adversarial orchestration   ·  solo operator             ·  fail-closed
⊛════════════════════════════════════════════════════════════════════════⊛
```

<br>

## what i build

**[GeoSync](https://github.com/neuron7xLab/GeoSync)** — cross-asset signal via Kuramoto phase synchrony + Ricci curvature.
physics kernel: shadow validation live. verdict: july 2026.

**[NeoSynaptex](https://github.com/neuron7xLab/NeoSynaptex)** — γ≈1.0 cross-substrate metastability framework.
CI hardened · SHA-pinned supply chain · multiple PRs merged.

**[neurophase](https://github.com/neuron7xLab/neurophase)** — EEG pipeline on ds003474. SCP analysis.
canonical formula: `γ_PSD = 2H + 1`

**NFI** — four-layer cognitive machine: `ML-SDM → CA1-LAM → BN-Syn → MFN⁺`
formally defined truth interface. zero-level closed loop contract 2026-03-31.

<br>

## verified 30-day output (2026-05-17 → 2026-06-16)

| metric | value | classification |
|--------|-------|----------------|
| commits | **764** | — |
| PRs merged | **396** | — |
| merge rate | **89%** | — |
| lead time (median) | **28 min** | DORA Elite |
| deployment frequency | **12.8 / day** | DORA Elite |
| active days | **28 / 31** | — |

> source: GitHub GraphQL API (`contributionsCollection`) + PR search · DORA framework (Google/DevOps Research)
> self-merge solo mode · collaboration axis not measured · N/A = honestly not instrumented

<br>

## methodology

```
Creator → Critic → Auditor → Verifier
```

adversarial orchestration. self as central decision node.
every output passes PARCH-FALSIFY-001 before commit.
instrument kills its own hypothesis. 49 closed-unmerged PR = healthy fail-closed.

<br>

## canon

```python
γ_PSD = 2*H + 1          # canonical. always.
γ     = 2*H - 1          # known error. reject on sight.

axiom = "physics starts where you stop explaining and start computing"
```

<br>

## stack

`Python` `GitHub Actions` `Claude Code` `FastMCP` `n8n`
`Kuramoto` `Ricci flow` `EEG / MNE` `SQLite` `systemd`

local hardware · Ubuntu lowlatency · forest, Poltava region

<br>

```
⊛════════════════════════════════════════════════════════════════════════⊛
```

<div align="center">
<sub><code>neuron7xLab · vasylenko7x · 2025–</code></sub>
</div>
