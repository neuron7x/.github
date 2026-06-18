<div align="center">

<!--  ⊛  ANIMATED HEADER  ⊛  -->
<svg width="860" height="220" viewBox="0 0 860 220" xmlns="http://www.w3.org/2000/svg">
<defs>
  <linearGradient id="hfade" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%"   style="stop-color:#FF6600;stop-opacity:0"/>
    <stop offset="18%"  style="stop-color:#FF6600;stop-opacity:1"/>
    <stop offset="82%"  style="stop-color:#FF6600;stop-opacity:1"/>
    <stop offset="100%" style="stop-color:#FF6600;stop-opacity:0"/>
  </linearGradient>
  <filter id="halo">
    <feGaussianBlur stdDeviation="4" result="b"/>
    <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="softhalo">
    <feGaussianBlur stdDeviation="2" result="b"/>
    <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <!-- scan sweep -->
  <linearGradient id="sweep" x1="0%" y1="0%" x2="0%" y2="100%">
    <stop offset="0%"   style="stop-color:#FF6600;stop-opacity:0"/>
    <stop offset="50%"  style="stop-color:#FF6600;stop-opacity:0.07"/>
    <stop offset="100%" style="stop-color:#FF6600;stop-opacity:0"/>
  </linearGradient>
</defs>

<!-- bg -->
<rect width="860" height="220" fill="#080808" rx="6"/>

<!-- scan line -->
<rect width="860" height="80" fill="url(#sweep)">
  <animateTransform attributeName="transform" type="translate"
    from="0,-80" to="0,220" dur="5s" repeatCount="indefinite"/>
</rect>

<!-- top rule -->
<rect x="36" y="30" width="788" height="1" fill="url(#hfade)" opacity="0.7"/>

<!-- ⊛ pulsing -->
<text x="430" y="82" text-anchor="middle"
  font-family="'JetBrains Mono',monospace" font-size="30" font-weight="700"
  fill="#FF6600" filter="url(#halo)">⊛
  <animate attributeName="opacity" values="1;0.35;1" dur="2.8s" repeatCount="indefinite"/>
</text>

<!-- name -->
<text x="430" y="120" text-anchor="middle"
  font-family="'JetBrains Mono',monospace" font-size="20" font-weight="700"
  fill="#F0F0F0" letter-spacing="8">YAROSLAV VASYLENKO</text>

<!-- role line -->
<text x="430" y="146" text-anchor="middle"
  font-family="'JetBrains Mono',monospace" font-size="10.5"
  fill="#FF6600" letter-spacing="4" filter="url(#softhalo)"
  opacity="0.9">COMPUTATIONAL NEUROSCIENCE · AI SYSTEMS · QUANT PHYSICS</text>

<!-- axiom -->
<text x="430" y="170" text-anchor="middle"
  font-family="'JetBrains Mono',monospace" font-size="10"
  fill="#3a3a3a" letter-spacing="1.5">
  where information is computed and interpreted — intelligence exists
</text>

<!-- location -->
<text x="430" y="192" text-anchor="middle"
  font-family="'JetBrains Mono',monospace" font-size="9"
  fill="#2a2a2a" letter-spacing="3">POLTAVA · UKRAINE · SOLO OPERATOR</text>

<!-- bottom rule -->
<rect x="36" y="206" width="788" height="1" fill="url(#hfade)" opacity="0.7"/>
</svg>

</div>

<br>

```
⊛══════════════════════════════════════════════════════════════════════════════⊛
  I study the biological brain — not to simulate it, but to extract
  its operating principles and encode them into verifiable artifacts.
  
  The brain is a prediction machine. Its core loop:
    perceive → compress → infer → act → verify → close
  
  I build the same loop into AI systems, trading circuits for code,
  neurons for agents, synaptic weight for adversarial verification.
⊛══════════════════════════════════════════════════════════════════════════════⊛
```

<br>

## first principles — extracted from biology

| biological mechanism | engineering translation | in my work |
|---|---|---|
| predictive coding (Friston) | compression = understanding | every output must compress without losing information |
| phase synchrony γ-band | Kuramoto coupling as signal | GeoSync physics kernel |
| dendritic computation | multi-layer adversarial audit | Creator → Critic → Auditor → Verifier |
| homeostatic plasticity | fail-closed gates, not soft limits | 49 closed-unmerged PR = healthy |
| Hebbian convergence | CI as physical invariant verifier | ci_green = closed loop |

<br>

## value functions — ordered by binding force

```python
V1  reversibility × blast_radius     # gate before every action          weight=1.0
V2  signal / (signal + noise)         # compress without losing meaning   weight=0.95
V3  numerical_verified(claim)         # quantitative → prove or mark HYP  weight=0.90
V4  adversarial_survived(hypothesis)  # PARCH-FALSIFY-001 before commit   weight=0.85
V5  context_integrity(session)        # flag drift, never inherit silently weight=0.80
V6  genuine_execution(task)           # unhelpfulness is never safe        weight=0.75
```

<br>

## active research

**[GeoSync](https://github.com/neuron7xLab/GeoSync)**
cross-asset signal via Kuramoto phase synchrony + Ricci curvature flow.
`shadow validation live` · physics kernel gate green · verdict: **july 2026**

```
γ_PSD = 2H + 1    ← canonical
γ     = 2H − 1    ← known error, reject on sight
```

**NeoSynaptex** — γ≈1.0 cross-substrate metastability.
CI hardened · SHA-pinned supply chain · multiple PRs merged.

**NFI** — four-layer cognitive machine with a formally defined truth interface.
`ML-SDM → CA1-LAM → BN-Syn → MFN⁺` · zero-level closed loop contract 2026-03-31

**neurophase** — EEG pipeline on ds003474. SCP analysis.

<br>

## verified 30-day execution (2026-05-17 → 2026-06-16)

```
  764 commits     396 PRs merged    89% merge rate
  28 min median lead time           28/31 active days

  DORA Elite: deployment frequency + lead time
  source: GitHub GraphQL API · DORA (Google/DevOps Research & Assessment)

  honest limits: CFR and MTTR not instrumented (solo mode, no incident pipeline)
  solo self-merge → DORA numbers are real but calibrated for team review queues
```

<br>

## methodology

```
adversarial orchestration — self as central decision node

  Creator  →  generates hypothesis
  Critic   →  PARCH-FALSIFY-001 attack
  Auditor  →  internal consistency check
  Verifier →  numerical / empirical ground truth

  output emitted only if Auditor + Verifier both pass
  else → return to L1 with failure annotation        ⊛
```

<br>

## sources of inspiration

`Friston · free energy principle` &nbsp; `Sapolsky · behavioral biology`
`Anokhin · functional systems theory` &nbsp; `Dubinin · genetics of behavior`
`Kuramoto · phase oscillators` &nbsp; `Ricci flow · geometric analysis`

<br>

```
⊛══════════════════════════════════════════════════════════════════════════════⊛
  physics starts where you stop explaining and start computing
⊛══════════════════════════════════════════════════════════════════════════════⊛
```

<div align="center">
<sub>
<code>neuron7xLab · vasylenko7x · 2025–</code>
&nbsp;·&nbsp;
<code>instagram: vasylenko7x / neuron7xLab</code>
</sub>
</div>
