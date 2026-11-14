<svg width="700" height="80" viewBox="0 0 700 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="burgundy-glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3.5" result="blur" />
      <feFlood flood-color="#A82046" flood-opacity="0.75" result="glowColor" />
      <feComposite in="glowColor" in2="blur" operator="in" result="softGlow" />
      <feMerge>
        <feMergeNode in="softGlow" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>

  </defs>
  <style>
    .typing-text {
      font-family: 'Fira Code', 'JetBrains Mono', 'Courier New', monospace;
      font-size: 24px;
      font-weight: 400; 
      fill: #800020; 
      letter-spacing: 0.5px;
    }
  </style>

  <g clip-path="url(#typing-clip)">
    <text x="180" y="48" class="typing-text" filter="url(#burgundy-glow)">
      welcome to my dashboard
    </text>
  </g>
</svg>
