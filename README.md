<!-- HERO BANNER CUSTOMIZADO (SVG Puro) -->
<div align="center">
  <svg width="850" height="250" viewBox="0 0 850 250" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Gradiente do Fundo (Preto e Vermelho Escuro) -->
      <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#090607" />
        <stop offset="100%" stop-color="#4A060B" />
      </linearGradient>
      
      <!-- Gradiente da Borda (Vermelho Vibrante) -->
      <linearGradient id="borderGradient" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#D91E2E" />
        <stop offset="100%" stop-color="#B81422" />
      </linearGradient>

      <!-- Máscara para a foto circular -->
      <clipPath id="avatar-clip">
        <circle cx="120" cy="125" r="65" />
      </clipPath>
    </defs>

    <!-- Fundo do Card -->
    <rect width="840" height="240" x="5" y="5" rx="15" fill="url(#bgGradient)" stroke="url(#borderGradient)" stroke-width="2" />
    
    <!-- Linha Decorativa Superior -->
    <path d="M 220 50 Q 400 10 600 70" fill="none" stroke="#7D0D17" stroke-width="1.5" opacity="0.6"/>

    <!-- Avatar (Substitua a URL pela sua imagem real caso não carregue) -->
    <!-- Borda do Avatar -->
    <circle cx="120" cy="125" r="70" fill="none" stroke="#D91E2E" stroke-width="3" />
    <!-- Imagem -->
    <image href="https://avatars.githubusercontent.com/u/262653814?v=4" x="55" y="60" width="130" height="130" clip-path="url(#avatar-clip)" />

    <!-- Textos -->
    <text x="220" y="70" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="16" fill="#F6F2EB" font-weight="500" opacity="0.8">
      @dlaube-zs
    </text>
    
    <text x="220" y="130" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="52" fill="#D91E2E" font-weight="800" letter-spacing="-1">
      Daniel Laube
    </text>
    
    <text x="220" y="165" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="16" fill="#F6F2EB" font-weight="400" opacity="0.9">
      Estudante de Sistemas de Informação | Software Developer ( JavaScript | Python | SQL )
    </text>

    <!-- "Botões" Decorativos (Estilo Tags) -->
    <g transform="translate(220, 190)">
      <rect width="110" height="30" rx="15" fill="#090607" stroke="#D91E2E" stroke-width="1.5"/>
      <text x="55" y="20" font-family="sans-serif" font-size="13" fill="#F6F2EB" font-weight="600" text-anchor="middle">Open Source</text>
    </g>
    <g transform="translate(345, 190)">
      <rect width="90" height="30" rx="15" fill="#090607" stroke="#B81422" stroke-width="1.5"/>
      <text x="45" y="20" font-family="sans-serif" font-size="13" fill="#F6F2EB" font-weight="600" text-anchor="middle">Projects</text>
    </g>
    <g transform="translate(450, 190)">
      <rect width="90" height="30" rx="15" fill="#090607" stroke="#7D0D17" stroke-width="1.5"/>
      <text x="45" y="20" font-family="sans-serif" font-size="13" fill="#F6F2EB" font-weight="600" text-anchor="middle">Systems</text>
    </g>
  </svg>
</div>
