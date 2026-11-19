<svg xmlns="http://www.w3.org/2000/svg" width="900" height="270" viewBox="0 0 900 270">
  <style>
    .mono { font-family: 'JetBrains Mono', 'Fira Code', Consolas, 'Courier New', monospace; font-size: 17px; }
    .prompt { fill: #3fb950; font-weight: 700; }
    .cmd { fill: #e6edf3; }
    .name { fill: #ffffff; font-weight: 700; font-size: 22px; }
    .dim { fill: #8b949e; }
    .err { fill: #ff7b72; }
    .wip { fill: #d29922; font-weight: 700; }
    .line { animation: show .35s ease-out both; }
    .l1 { animation-delay: .2s } .l2 { animation-delay: .8s } .l3 { animation-delay: 1.6s }
    .l4 { animation-delay: 2.3s } .l5 { animation-delay: 3.0s } .l6 { animation-delay: 3.5s }
    .cursor { animation: blink 1s steps(1) infinite; }
    @keyframes show { from { opacity: 0; transform: translateX(-6px); } to { opacity: 1; transform: none; } }
    @keyframes blink { 50% { opacity: 0; } }
  </style>
  <rect x="1" y="1" width="898" height="268" rx="12" fill="#0d1117" stroke="#30363d" stroke-width="2"/>
  <rect x="1" y="1" width="898" height="38" rx="12" fill="#161b22"/>
  <rect x="1" y="26" width="898" height="13" fill="#161b22"/>
  <circle cx="26" cy="20" r="7" fill="#ff5f56"/><circle cx="48" cy="20" r="7" fill="#ffbd2e"/><circle cx="70" cy="20" r="7" fill="#27c93f"/>
  <text x="450" y="25" text-anchor="middle" class="mono dim" style="font-size:14px">nullmalloc@42nice: ~</text>

  <text x="30" y="80" class="mono line l1"><tspan class="prompt">$</tspan><tspan class="cmd"> whoami</tspan></text>
  <text x="30" y="114" class="mono line l2"><tspan class="name">Sami</tspan><tspan class="dim"> // 42 Nice student, aspiring pentester</tspan></text>
  <text x="30" y="160" class="mono line l3"><tspan class="prompt">$</tspan><tspan class="cmd"> cat flag.txt</tspan></text>
  <text x="30" y="190" class="mono line l4"><tspan class="err">cat: flag.txt: Permission denied</tspan></text>
  <text x="30" y="220" class="mono line l5"><tspan class="wip">[*]</tspan><tspan class="dim"> 2 flags hidden on this page. Go find them.</tspan></text>
  <g class="line l6"><text x="30" y="252" class="mono"><tspan class="prompt">$</tspan></text><rect x="50" y="236" width="10" height="20" fill="#e6edf3" class="cursor"/></g>
</svg>
