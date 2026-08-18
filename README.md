<p align="center">
  <svg width="100%" viewBox="0 0 1280 320" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#08111F"/>
        <stop offset="100%" stop-color="#142744"/>
      </linearGradient>

      <linearGradient id="wave" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#22D3EE"/>
        <stop offset="50%" stop-color="#67E8F9"/>
        <stop offset="100%" stop-color="#C4F5FF"/>
      </linearGradient>

      <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="6" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <rect width="1280" height="320" rx="18" fill="url(#bg)"/>

    <circle cx="1100" cy="70" r="90" fill="#38BDF8" opacity="0.05"/>

    <g fill="none" stroke-linecap="round">
      <path d="M-20 240 C140 160,260 290,420 210 S760 90,930 180 S1160 260,1300 140"
            stroke="#56D7EE" stroke-opacity="0.18" stroke-width="2"/>

      <path d="M-20 248 C140 168,260 298,420 218 S760 98,930 188 S1160 268,1300 148"
            stroke="#56D7EE" stroke-opacity="0.30" stroke-width="2"/>

      <path d="M-20 256 C140 176,260 306,420 226 S760 106,930 196 S1160 276,1300 156"
            stroke="url(#wave)" stroke-width="4" filter="url(#glow)"/>

      <path d="M-20 264 C140 184,260 314,420 234 S760 114,930 204 S1160 284,1300 164"
            stroke="#C4F5FF" stroke-opacity="0.45" stroke-width="2"/>
    </g>

    <text x="80" y="120"
          font-family="Arial, Helvetica, sans-serif"
          font-size="64"
          font-weight="700"
          fill="#F8FAFC">
      Sandhya
    </text>

    <text x="84" y="155"
          font-family="Arial, Helvetica, sans-serif"
          font-size="20"
          letter-spacing="5"
          fill="#B6C8DA">
      COMPUTATIONAL BIOLOGY
    </text>
  </svg>
</p>
