<svg xmlns="http://www.w3.org/2000/svg" width="900" height="330" viewBox="0 0 900 330">
  <style>
    .mono { font-family: 'JetBrains Mono', 'Fira Code', Consolas, 'Courier New', monospace; font-size: 17px; }
    .prompt { fill: #3fb950; font-weight: 700; }
    .cmd { fill: #e6edf3; }
    .name { fill: #ffffff; font-weight: 700; font-size: 22px; }
    .dim { fill: #8b949e; }
    .ok { fill: #3fb950; font-weight: 700; }
    .wip { fill: #d29922; font-weight: 700; }
    .todo { fill: #6e7681; font-weight: 700; }
    .red { fill: #ff5f56; }
    .line { animation: show .35s ease-out both; }
    .l1 { animation-delay: .2s } .l2 { animation-delay: .7s } .l3 { animation-delay: 1.3s }
    .l4 { animation-delay: 1.7s } .l5 { animation-delay: 2.0s } .l6 { animation-delay: 2.3s }
    .l7 { animation-delay: 2.6s } .l8 { animation-delay: 3.1s }
    .cursor { animation: blink 1s steps(1) infinite; }
    @keyframes show { from { opacity: 0; transform: translateX(-6px); } to { opacity: 1; transform: none; } }
    @keyframes blink { 50% { opacity: 0; } }
  </style>
  <rect x="1" y="1" width="898" height="328" rx="12" fill="#0d1117" stroke="#30363d" stroke-width="2"/>
  <rect x="1" y="1" width="898" height="38" rx="12" fill="#161b22"/>
  <rect x="1" y="26" width="898" height="13" fill="#161b22"/>
  <circle cx="26" cy="20" r="7" fill="#ff5f56"/><circle cx="48" cy="20" r="7" fill="#ffbd2e"/><circle cx="70" cy="20" r="7" fill="#27c93f"/>
  <text x="450" y="25" text-anchor="middle" class="mono dim" style="font-size:14px">nullmalloc@42nice: ~</text>

  <text x="30" y="78" class="mono line l1"><tspan class="prompt">$</tspan><tspan class="cmd"> whoami</tspan></text>
  <text x="30" y="112" class="mono line l2"><tspan class="name">Sami</tspan><tspan class="dim"> // 42 Nice student, aspiring pentester</tspan></text>

  <text x="30" y="156" class="mono line l3"><tspan class="prompt">$</tspan><tspan class="cmd"> ./status --short</tspan></text>
  <text x="30" y="188" class="mono line l4"><tspan class="ok">[+]</tspan><tspan class="cmd"> CompTIA Security+</tspan><tspan class="dim">  certified</tspan></text>
  <text x="30" y="216" class="mono line l5"><tspan class="ok">[+]</tspan><tspan class="cmd"> libft</tspan><tspan class="dim">  100/100, 43 C functions, zero leaks</tspan></text>
  <text x="30" y="244" class="mono line l6"><tspan class="wip">[*]</tspan><tspan class="cmd"> ft_printf</tspan><tspan class="dim">  +  TryHackMe Jr Penetration Tester</tspan></text>
  <text x="30" y="272" class="mono line l7"><tspan class="todo">[&gt;]</tspan><tspan class="cmd"> PJPT</tspan><tspan class="dim"> -&gt; </tspan><tspan class="cmd">CPTS</tspan><tspan class="dim"> -&gt; </tspan><tspan class="red">OSCP</tspan></text>

  <g class="line l8"><text x="30" y="308" class="mono"><tspan class="prompt">$</tspan></text><rect x="50" y="292" width="10" height="20" fill="#e6edf3" class="cursor"/></g>
</svg>
