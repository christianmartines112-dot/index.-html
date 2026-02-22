cellnet-security/
├── 📁 .github/
│   └── 📁 workflows/
│       └── deploy.yml              # CI/CD opcional con GitHub Actions
│
├── 📁 src/
│   ├── 📁 css/
│   │   ├── main.css               # Estilos principales
│   │   ├── security-dashboard.css # Estilos del panel de seguridad
│   │   ├── wifi-scanner.css       # Estilos del escáner WiFi
│   │   └── animations.css         # Animaciones y efectos visuales
│   │
│   ├── 📁 js/
│   │   ├── app.js                 # Punto de entrada principal
│   │   ├── 📁 modules/
│   │   │   ├── networkScanner.js  # Escáner de redes WiFi
│   │   │   ├── intrusionDetection.js # Sistema IDS
│   │   │   ├── deviceMonitor.js   # Monitoreo de dispositivos
│   │   │   ├── vulnerabilityScanner.js # Análisis de vulnerabilidades
│   │   │   ├── securityScore.js   # Cálculo de puntuación de seguridad
│   │   │   ├── packetAnalyzer.js  # Analizador de paquetes
│   │   │   └── threatIntelligence.js # Inteligencia de amenazas
│   │   ├── 📁 utils/
│   │   │   ├── helpers.js         # Funciones auxiliares
│   │   │   ├── constants.js       # Constantes y configuración
│   │   │   └── mockData.js        # Datos simulados para demo
│   │   └── 📁 services/
│   │       └── awsIntegration.js  # Integración con AWS (opcional futuro)
│   │
│   └── 📁 assets/
│       ├── 📁 images/
│       │   ├── logo.svg
│       │   ├── icons/
│       │   └── screenshots/
│       └── 📁 fonts/
│           └── custom-font.woff2
│
├── 📁 public/                     # Archivos estáticos que no necesitan procesamiento
│   ├── favicon.ico
│   ├── manifest.json              # PWA manifest
│   ├── robots.txt
│   └── sitemap.xml
│
├── 📁 docs/                       # Documentación
│   ├── README.md                  # Documentación principal del proyecto
│   ├── ARCHITECTURE.md            # Arquitectura de la aplicación
│   ├── SECURITY.md                # Políticas de seguridad
│   ├── DEPLOYMENT.md              # Guía de despliegue detallada
│   └── API.md                     # Documentación de API (futuro)
│
├── 📁 tests/                      # Tests (futuro implementación)
│   ├── unit/
│   ├── integration/
│   └── e2e/
│
├── 📁 config/                     # Configuraciones
│   ├── amplify.yml                # Configuración AWS Amplify
│   └── jest.config.js            # Configuración de testing
│
├── index.html                     # Punto de entrada HTML
├── package.json                   # Dependencias y scripts (futuro)
├── .gitignore                     # Archivos ignorados por Git
├── LICENSE                        # Licencia MIT
└── CHANGELOG.md                   # Historial de cambios


