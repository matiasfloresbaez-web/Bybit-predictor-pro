# Bybit Predictor Pro — PWA

App de análisis técnico en tiempo real para Bybit con Stop Loss y Take Profit automáticos.

## Archivos incluidos
```
bybit-predictor-pwa/
├── index.html        ← App completa
├── manifest.json     ← Configuración PWA
├── sw.js             ← Service Worker (funciona sin internet para la UI)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## Cómo subir a GitHub Pages (gratis)

1. Ve a https://github.com y crea una cuenta si no tienes
2. Clic en **New repository**
3. Nombre: `bybit-predictor` (o el que quieras)
4. Marca **Public** → clic en **Create repository**
5. Sube todos los archivos de esta carpeta arrastrándolos al repositorio
6. Ve a **Settings → Pages**
7. En *Source* selecciona **Deploy from a branch**
8. Elige la rama `main` y carpeta `/ (root)` → clic en **Save**
9. Espera 1-2 minutos → tu app estará en:
   `https://TU-USUARIO.github.io/bybit-predictor/`

## Instalar en el celular (Android)
1. Abre la URL en Chrome
2. Aparece banner "Agregar a pantalla de inicio" → acepta
3. O toca los tres puntos → "Instalar app"

## Instalar en iPhone (iOS)
1. Abre la URL en Safari
2. Toca el ícono de compartir (cuadrado con flecha)
3. Selecciona "Agregar a pantalla de inicio"
4. Confirma → aparece el ícono en tu pantalla

## Instalar en PC (Chrome/Edge)
1. Abre la URL en Chrome o Edge
2. Aparece ícono de instalar en la barra de dirección (esquina derecha)
3. Clic → "Instalar"

## Indicadores incluidos
- RSI (14)
- MACD (12,26,9)
- Bollinger Bands (20,2)
- EMA 20 / EMA 50 / SMA 200
- Estocástico (14,3)
- ATR (volatilidad)
- Volumen relativo

## Stop Loss & Take Profit
- Calculados con ATR × multiplicador ajustado por confianza
- Combinado con soportes/resistencias reales
- 3 niveles de TP: conservador (1:1), moderado (1:2), agresivo (1:3)
