# RouteMetrics

Aplicativo PWA para metrificação de tempo de trajeto com rastreamento GPS.

## Funcionalidades

- **Cronômetro com GPS** — rastreamento contínuo de coordenadas durante o trajeto
- **Distância real** — cálculo via Haversine ponto a ponto
- **Velocidade média** — calculada automaticamente (km/h)
- **Mini-mapa SVG** — traçado visual do percurso por viagem
- **Comparativo semanal** — Semana 1 vs 2 vs 3 com gráficos
- **Exportação** — CSV e Excel (.xlsx) com dados completos
- **Offline** — funciona sem internet após primeiro acesso (Service Worker)
- **Dados persistentes** — armazenamento via localStorage

## Como usar

1. Acesse: `https://cjinfoaulas-psy.github.io/route-metrics/`
2. No Chrome, toque em **"Adicionar à tela inicial"**
3. Crie rotas e meça seus trajetos

## Stack

- React 18 (CDN)
- Recharts (gráficos)
- SheetJS (exportação Excel)
- Geolocation API (GPS)
- PWA (manifest + Service Worker)

## Licença

Projeto pessoal de Caio Henrique Vieira Lima.
