# 💧 Piscinas de Liquidez y Rango Concentrado en Uniswap v3

> **Material de Cátedra e Investigación Técnica de Microestructura DeFi**  
> **Semillero de Investigación en Blockchain — Universidad de Antioquia (UdeA)**  
> **Laboratorio Financiero UdeA** (Bloque 19, Aula 206)  
> **Facultad de Ingeniería & Facultad de Ciencias Económicas**  
> Cátedra Conducida por: **La Alquimia**

---

## 📌 Descripción General

Este repositorio contiene la presentación interactiva y el análisis cuantitativo sobre **Piscinas de Liquidez (Liquidity Pools)**, **Mecanismos de Formación de Precios en AMM vs. Economía Clásica**, **Tokenización de Empresas en Base (L2)** y **Liquidez Concentrada en Uniswap v3**.

Diseñado para proyección académica en el **Laboratorio Financiero UdeA**, el material sintetiza en 10 diapositivas de alta fidelidad los principios de microestructura financiera descentralizada y capital efficiency.

---

## 📂 Contenido del Repositorio

| Archivo | Formato | Descripción |
| :--- | :--- | :--- |
| [`presentacion_liquidity_pools.html`](./presentacion_liquidity_pools.html) | HTML5 / CSS3 / Vanilla JS | **Presentación Magistral Interactiva (10 Diapositivas):** Motor de proyección completo con glassmorphism institucional UdeA, fórmulas KaTeX, atajos de teclado, modal de navegación y simulador en tiempo real. |
| [`index.html`](./index.html) | HTML5 | Acceso directo para despliegue automático en GitHub Pages o servidores estáticos. |
| [`assets/`](./assets/) | Media / Vectores | Logotipos oficiales de la Universidad de Antioquia y recursos gráficos. |

---

## 📑 Temario de las 10 Diapositivas

1. **Portada Institucional UdeA:** Semillero de Blockchain & Finanzas Cuantitativas (Bloque 19-206).
2. **"Ya creamos el ERC-20... ¿Qué es una Piscina?":** De la asignación contable estática en wallet a la contraparte algorítmica perpetua (Peer-to-Contract - P2C).
3. **¿Qué es el Precio? Economía Clásica vs. Ratio AMM:** Curvas de Marshall y Hayek vs. el ratio determinista de reservas ($P = y/x$). Ceguera del contrato y necesidad del arbitraje.
4. **Caso Provocador: Tokenizar Empresa de $2M con Pool de $10 en Base:** El espejismo del Fully Diluted Valuation (FDV) frente a la realidad de la Profundidad de Mercado (*Market Depth*). Por qué vender 25 tokens drena la pool y desploma el precio un -91.8%.
5. **Creación de la Pool en Uniswap v3 (Solidity en Base):** `INonfungiblePositionManager`, orden léxico (`token0 < token1`), Fee Tiers y formato de precio de punto fijo Q64.96 ($\sqrt{P}_{X96}$).
6. **La Revolución del Rango: De v2 a Liquidez Concentrada:** Rango infinito $(0, \infty)$ vs. reservas virtuales acotadas $[p_a, p_b]$.
7. **Maximización de Liquidez por Rangos Estrechos:** Multiplicador de eficiencia $\chi = \frac{1}{1 - \sqrt{p_a/p_b}}$. Cómo simular $10,000 USD de profundidad con $10 USD a $\pm 0.1\%$ y los riesgos de Impermanent Loss concentrado.
8. **Órdenes de Rango (Range Orders) y Mapas de Liquidez:** Órdenes límite sintéticas en 1 tick, la trampa de la reversibilidad y análisis de muros Bid-Side (USDC) vs. Ask-Side (CORP).
9. **Simulador Interactivo de Microestructura:** Herramienta interactiva con controles deslizantes para simular reservas, eficiencia de rango, órdenes de venta y detección de colapso de liquidez.
10. **Síntesis Magistral y Cierre ("¡Muchas Gracias!"):** Los 4 axiomas definitivos de las piscinas de liquidez y agradecimiento institucional al Semillero La Alquimia y a la comunidad universitaria.

---

## 🖥️ Cómo Visualizar las Diapositivas

El archivo es **100% autocontenido** (no requiere dependencias externas ni compiladores). Puedes abrirlo directamente:

```bash
open presentacion_liquidity_pools.html
# o
open index.html
```

### Atajos de Teclado durante la Proyección:
- **`→` / `Espacio` / `PageDown`**: Avanzar diapositiva.
- **`←` / `PageUp`**: Retroceder diapositiva.
- **`O`**: Abrir / cerrar el índice de cuadrícula para saltar a cualquier tema.
- **`F`**: Activar / desactivar pantalla completa.
- **`Home` / `End`**: Ir a la primera o última diapositiva.

---

**Universidad de Antioquia · Semillero de Blockchain La Alquimia**  
*Medellín, Colombia*
