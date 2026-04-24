<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="1200" height="320" role="img" aria-label="Nassim Baheddi Full Stack Web Developer">
  <defs>
    <radialGradient id="spot" cx="22%" cy="40%" r="55%">
      <stop offset="0%" stop-color="#f5f5f0" stop-opacity="0.10"/>
      <stop offset="55%" stop-color="#f5f5f0" stop-opacity="0.02"/>
      <stop offset="100%" stop-color="#f5f5f0" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="spot2" cx="85%" cy="75%" r="40%">
      <stop offset="0%" stop-color="#c9c4b8" stop-opacity="0.06"/>
      <stop offset="100%" stop-color="#c9c4b8" stop-opacity="0"/>
    </radialGradient>
    <pattern id="grid" width="32" height="32" patternUnits="userSpaceOnUse">
      <path d="M 32 0 L 0 0 0 32" fill="none" stroke="#ffffff" stroke-opacity="0.035" stroke-width="0.5"/>
    </pattern>
    <filter id="noise">
      <feTurbulence type="fractalNoise" baseFrequency="0.9" numOctaves="2" stitchTiles="stitch"/>
      <feColorMatrix values="0 0 0 0 1  0 0 0 0 1  0 0 0 0 1  0 0 0 0.08 0"/>
    </filter>
  </defs>

  <!-- base -->
  <rect width="1200" height="320" fill="#0a0a0a"/>
  <rect width="1200" height="320" fill="url(#grid)"/>
  <rect width="1200" height="320" fill="url(#spot)"/>
  <rect width="1200" height="320" fill="url(#spot2)"/>
  <rect width="1200" height="320" filter="url(#noise)" opacity="0.55"/>

  <!-- hairline frame -->
  <rect x="0.5" y="0.5" width="1199" height="319" fill="none" stroke="#ffffff" stroke-opacity="0.08"/>

  <!-- small-caps mono label -->
  <g font-family="ui-monospace, 'SF Mono', Menlo, Consolas, monospace" fill="#a8a39a">
    <text x="80" y="110" font-size="11" letter-spacing="4" opacity="0.75">— PORTFOLIO / 2026</text>
    <line x1="80" y1="124" x2="150" y2="124" stroke="#a8a39a" stroke-opacity="0.4" stroke-width="0.5"/>
  </g>

  <!-- display headline -->
  <text x="78" y="200" font-family="Georgia, 'Times New Roman', serif" font-size="82" font-style="italic" font-weight="400" fill="#efece5" letter-spacing="-1">
    Nassim Baheddi<tspan fill="#8a8478" font-style="normal">.</tspan>
  </text>

  <!-- subline mono -->
  <text x="80" y="240" font-family="ui-monospace, 'SF Mono', Menlo, Consolas, monospace" font-size="13" fill="#8a8478" letter-spacing="1">
    full-stack engineer &#8212; building quiet, scalable interfaces on the web.
  </text>

  <!-- corner mono meta -->
  <g font-family="ui-monospace, 'SF Mono', Menlo, Consolas, monospace" font-size="10" fill="#6e685d" letter-spacing="2">
    <text x="80" y="56" opacity="0.8">N / 01</text>
    <text x="1120" y="56" text-anchor="end" opacity="0.8">DZ · 36.7°N</text>
    <text x="80" y="290" opacity="0.8">INDEX —</text>
    <text x="1120" y="290" text-anchor="end" opacity="0.8">README.MD</text>
  </g>
</svg>
