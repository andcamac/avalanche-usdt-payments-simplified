# App de Pagos Simplificada: USDT en Avalanche

Una aplicación de pagos ultra-simple que permite enviar USDT en Avalanche usando una billetera existente (MetaMask). Transacciones sub-segundo, bajas comisiones. Integración directa con ethers.js para USDT (ERC-20).

## Funcionalidades
- Conectar MetaMask (wallet existente, sin generar nueva).
- Verificar balance de USDT.
- Enviar pagos de USDT.

## Advertencias
- Usa MetaMask con Avalanche configurado (Mainnet: Chain ID 43114).
- Prueba en testnet primero: Cambia RPC a `https://api.avax-test.network/ext/bc/C/rpc` y Chain ID a 43113.
- USDT en Avalanche: 6 decimales. Asegúrate de tener AVAX para gas (~0.01 AVAX por txn).
- Demo educativa: No para producción sin auditoría.

## Setup
1. Clona: `git clone https://github.com/tu-usuario/avalanche-usdt-simple-payments.git`
2. Abre `index.html` en browser con MetaMask instalado.
3. O sirve local: `npx http-server . -p 8080` y abre http://localhost:8080.

## Uso
1. Haz clic en "Conectar MetaMask".
2. Aprueba la conexión y switch a Avalanche.
3. Verifica balance y envía USDT.
4. Ver txns en [Snowtrace](https://snowtrace.io/).

## Dependencias
- Solo ethers.js via CDN (no npm needed).

## Licencia
MIT.