# Principales Iniciativas de Stablecoins (2023-2025)

> Parte de la serie [Stablecoins y Pagos C2B - Visión General](../Overview-ES.md) | [English](../en/major-stablecoin-initiatives.md) | [中文](../zh/major-stablecoin-initiatives.md)

## Introducción

Entre 2023 y 2025, el panorama de pagos con stablecoins se transformó drásticamente cuando importantes empresas fintech y cripto lanzaron ambiciosas iniciativas para llevar el uso de stablecoins a la corriente principal. Este período marcó un cambio de las stablecoins como instrumentos principalmente de trading a infraestructura de pago dedicada con blockchains de propósito específico, integraciones con comerciantes y adopción institucional.

Este artículo examina las seis iniciativas de plataforma más significativas que están redefiniendo cómo los consumidores y empresas realizan transacciones con stablecoins.

![Panorama del Ecosistema de Stablecoins](../imgs/major-initiatives-ecosystem.jpg)
*El ecosistema de stablecoins en evolución con los principales actores impulsando la innovación en pagos digitales*

---

## 1. PayPal USD (PYUSD): Integración Mainstream

### Lanzamiento y Estructura

En **agosto de 2023**, PayPal acaparó titulares al introducir su propia stablecoin vinculada al dólar estadounidense, **PYUSD**, emitida por Paxos Trust.[^1][^2]

**Características Clave:**
- Respaldada completamente 1:1 por depósitos en dólares y bonos del Tesoro de EE.UU.
- Emitida como token ERC-20 (blockchain de Ethereum)
- Redimible 1:1 por USD a través de Paxos
- Atestaciones regulares de terceros sobre las reservas
- Integrada en las plataformas PayPal y Venmo

### Integración de Plataforma

PayPal integró PYUSD profundamente en su ecosistema de pagos existente:

**Características para Consumidores:**
- Comprar, vender y mantener PYUSD dentro de la app de PayPal
- Enviar transferencias peer-to-peer (P2P) a otros usuarios de PayPal/Venmo
- Financiar compras en millones de comercios online a través del checkout de PayPal
- Conversión fluida entre PYUSD y otras criptomonedas
- Disponible en Venmo, extendiendo el alcance a demografías más jóvenes[^3]

**Beneficios para Comerciantes:**
- Aceptar PYUSD a través de la integración existente de PayPal
- Liquidación instantánea en PYUSD o conversión automática a USD
- No se requiere integración adicional para comerciantes existentes de PayPal
- Comisiones reducidas en comparación con métodos de pago tradicionales
- Acceso a la base de clientes nativos de cripto

### Importancia Estratégica

La entrada de PayPal validó las stablecoins para el comercio mainstream. Con más de 400 millones de usuarios activos y millones de relaciones con comerciantes, PayPal proporcionó una distribución instantánea que los proyectos nativos de cripto nunca podrían lograr.

**Visión de PayPal:**
> "Pensamos que las stablecoins son una evolución natural para el comercio digital, proporcionando un instrumento estable que es tanto nativo digital como fácilmente conectado con el dinero fiat."[^4]

### Desarrollos Recientes (2025)

- Asociación con Coinbase para reducción de comisiones y liquidez
- Expansión a blockchains adicionales más allá de Ethereum
- Integración con protocolos DeFi para generación de rendimiento
- Incidente notable: El minteo accidental y la corrección destacaron mecanismos de control centralizado[^5]

---

## 2. Estrategia Dual de Stripe: Integración + Blockchain Tempo

Stripe ha perseguido la estrategia de stablecoins más completa, operando en dos pistas paralelas: integración con comerciantes y desarrollo de infraestructura.

### Pista 1: Integración con Comerciantes (2024-2025)

**Asociación con Shopify:**

A mediados de 2025, Stripe se asoció con Shopify para permitir que millones de comerciantes en **34 países** acepten pagos con USDC de clientes.[^6]

**Cómo Funciona:**
1. Los compradores pagan con USDC usando billeteras cripto (inicialmente la red Base de Coinbase)
2. Stripe maneja toda la conversión cripto-a-fiat automáticamente
3. Los comerciantes reciben fondos en su moneda fiat local en su cuenta bancaria
4. Alternativamente, los comerciantes pueden optar por quedarse con el USDC

**Innovación Clave:**
Los comerciantes no necesitan cambiar su flujo de checkout existente ni mantener criptomonedas: Stripe abstrae toda la complejidad.[^7][^8]

**Características Adicionales:**
- **Pagos recurrentes con stablecoins**: Las suscripciones y SaaS pueden facturar en USDC igual que las tarjetas de crédito[^9]
- **Alcance global**: Acceso a mercados con acceso limitado a tarjetas o monedas inestables
- **Comisiones más bajas**: Evitar los cargos de las redes de tarjetas tradicionales
- **Liquidación instantánea**: T+0 en lugar de T+2 o más

### Pista 2: Blockchain Tempo (2025)

Stripe, en colaboración con la firma de capital riesgo cripto Paradigm, presentó **Tempo**: una nueva blockchain de Capa 1 diseñada específicamente para pagos con stablecoins de alto volumen.[^10][^11]

**¿Por qué una Nueva Blockchain?**

El CEO de Stripe señaló que las blockchains existentes "no estaban optimizadas" para la escala de pagos del mundo real a medida que crece el uso de stablecoins.[^12]

**Principios de Diseño de Tempo:**

**1. Arquitectura de Alto Rendimiento y Bajo Costo**
- Finalidad en menos de un segundo
- Miles de transacciones por segundo
- Comisiones mínimas (fracciones de centavo)
- Optimizada para patrones de pago, no para computación general

**2. Gas Nativo Multi-Stablecoin**
- Aceptar USDC, USDT y otras stablecoins para comisiones de transacción
- No se requiere token volátil separado
- Los usuarios pagan comisiones en la misma moneda con la que transaccionan
- Técnicamente desafiante pero mejora drásticamente la UX[^13][^14]

**3. Primitivas Específicas de Pago**
- Pagos condicionales integrados
- Soporte para pagos programados/recurrentes
- Primitivas de transacciones multi-parte
- APIs de pago amigables para desarrolladores a nivel de protocolo[^15]

**4. Socios de Grado Empresarial**
Tempo ha atraído una alianza impresionante:
- **Empresas de IA**: OpenAI, Anthropic
- **E-commerce**: Shopify, Coupang
- **Finanzas**: Visa, Standard Chartered
- **Propósito**: Guiar el diseño para necesidades de pago del mundo real[^16]

### Plataforma de Emisión Abierta de Stripe

Más allá de aceptar stablecoins, Stripe lanzó "**Open Issuance**" (Emisión Abierta), permitiendo a las empresas crear sus propias stablecoins para:
- Capturar intereses sobre depósitos de clientes
- Construir programas de lealtad de marca
- Crear ecosistemas de pago de circuito cerrado
- Distribuir rendimientos de tesorería a clientes[^17][^18]

Esto representa la visión de Stripe del comercio "agéntico" impulsado por IA donde los sistemas autónomos transaccionan sin problemas.

---

![Infraestructura de Pago Blockchain](../imgs/major-initiatives-blockchain-infrastructure.jpg)
*Infraestructura blockchain de propósito específico optimizada para pagos con stablecoins*

## 3. Protocolo x402 de Coinbase: Pagos Nativos de HTTP

Mientras otros se enfocaban en el checkout de comerciantes, Coinbase fue pionera en una innovación más fundamental: integrar pagos en el tejido mismo de internet.

### El Estándar x402

Coinbase co-creó **x402**, reviviendo el código de estado HTTP **402 "Payment Required"** (Pago Requerido) que había sido reservado durante mucho tiempo en internet como herramienta para micropagos fluidos con stablecoins.[^19][^20]

**Cómo Funciona:**

Flujo tradicional:
```
Cliente → Servidor: GET /artículo-premium
Servidor → Cliente: 403 Forbidden (paywall)
[El usuario debe navegar manualmente a la página de pago, ingresar tarjeta, etc.]
```

Flujo x402:
```
Cliente → Servidor: GET /artículo-premium
Servidor → Cliente: 402 Payment Required
  Precio: 0.05 USDC
  Dirección de Pago: 0x...
Cliente → Blockchain: [Pago automático]
Cliente → Servidor: GET /artículo-premium (con prueba de pago)
Servidor → Cliente: 200 OK [Contenido del artículo]
```

### Casos de Uso

**1. Micropagos de API**
- Pagar por llamada API en lugar de suscripción mensual
- Limitación de tasa automática basada en pago
- Sin compromiso inicial ni configuración de cuenta

**2. Paywalls de Contenido**
- Pagar $0.10 para leer un artículo
- No se requiere suscripción
- Acceso instantáneo después del micro-pago

**3. Transacciones de Agentes IA**
El protocolo anticipa particularmente **agentes de IA pagando por servicios de forma autónoma**:[^21]

- El agente IA necesita datos de una API
- Encuentra 402 Payment Required
- Paga automáticamente la cantidad solicitada en USDC
- Recibe y procesa los datos
- Todo sin intervención humana

### Fundación x402 (2025)

Coinbase y socios (incluyendo Cloudflare) formaron la **Fundación x402** para promover esto como un estándar universal para microtransacciones en internet vía cripto.[^22]

Al usar stablecoins (principalmente USDC) para estos pagos, x402 asegura:
- El precio es estable y familiar
- Compatibilidad global sin conversión de moneda
- Solicitudes de pago legibles por máquinas
- Liquidación instantánea sin intermediarios

### Visión Estratégica

x402 posiciona las stablecoins como el "dinero nativo de internet", habilitando la visión largamente prometida pero nunca realizada de micropagos HTTP 402. A medida que los agentes de IA se vuelven más prevalentes, tener una forma estandarizada para que las máquinas transaccionen se vuelve infraestructura crítica.

---

## 4. Blockchain Arc de Circle: Integración Vertical

Circle, el emisor de USDC (la segunda stablecoin más grande), dio un paso audaz en 2025 al lanzar su propia blockchain de Capa 1 diseñada explícitamente para finanzas con stablecoins.

### Por qué Existe Arc

Después de ver a los socios luchar con cadenas de propósito general no diseñadas para pagos, Circle identificó puntos de dolor específicos:[^23][^24]

**Problemas con las Cadenas Existentes:**
- Comisiones de transacción impredecibles
- Gas pagado en ETH volátil/otros tokens
- Limitaciones de privacidad para empresas
- Finalidad más lenta que las redes de tarjetas
- Despliegue multi-cadena complejo

**Solución de Arc:**
Construir una blockchain de propósito específico para transacciones con stablecoins con requisitos empresariales en mente.

### Características Técnicas de Arc

**1. USDC como Moneda de Gas Nativa**
Todas las comisiones se pagan en USDC para costos predecibles y denominados en fiat.[^25]
- No necesidad de mantener ETH, SOL u otros tokens volátiles
- Las empresas pueden presupuestar comisiones en términos de dólares familiares
- Simplifica la contabilidad y reconciliación

**2. Motor FX Integrado**
Intercambio de monedas 24/7 en cadena entre stablecoins.[^26]
- Convertir USDC ↔ EURC ↔ otras stablecoins fiat
- Intercambio de divisas instantáneo en cadena
- Tasas competitivas sin intermediarios fuera de cadena

**3. Finalidad Instantánea**
Liquidación en menos de un segundo con finalidad determinística.[^27]
- Iguala o supera las velocidades de las redes de tarjetas
- Confirmación irreversible en <1 segundo
- Confiabilidad de grado empresarial

**4. Privacidad Opcional**
Los detalles de las transacciones pueden mantenerse confidenciales.[^28][^29]
- Verificación pública sin exponer montos
- Privacidad empresarial para transacciones de negocios
- Diseño compatible con cumplimiento normativo

**5. Integración Completa de Circle**
Integración nativa con los servicios existentes de Circle:[^30]
- API de Cuenta Circle
- Pagos Circle
- Stablecoins multi-moneda
- Servicios de cumplimiento normativo e identidad

### Posicionamiento Estratégico

Circle está ejecutando una **estrategia de integración vertical**:

1. **Emitir USDC** (stablecoin)
2. **Construir Arc** (blockchain optimizada para USDC)
3. **Operar infraestructura** (nodos, validadores)
4. **Proveer servicios** (APIs, billeteras, cumplimiento normativo)
5. **Capturar valor** (comisiones, intereses, servicios)

Al controlar la pila completa, Circle asegura:[^31]
- Cada transacción Arc usa USDC (impulsando la demanda)
- Circle proporciona servicios complementarios (generando ingresos)
- Innovación más rápida sin dependencias de terceros
- Soporte de grado empresarial y SLAs

Arc apunta a ser la **columna vertebral de alto rendimiento para corporaciones que adoptan stablecoins**, complementando redes públicas como Ethereum mientras mitiga sus deficiencias para pagos.[^32][^33]

---

## 5. Plasma y Stable Chains de Tether: Control del Ecosistema

Tether, emisor de USDT (la stablecoin más grande con más de $83 mil millones en suministro), tomó un enfoque aún más ambicioso en 2025 al lanzar **dos blockchains relacionadas**: Plasma y Stable.[^34]

### Motivación Estratégica

Tether reconoció una oportunidad perdida masiva:

**El Problema:**
- El USDT de Tether facilita más de **$1 billón en transacciones por mes**
- USDT operaba sobre las redes de otros (Ethereum, Tron, Solana, etc.)
- Los operadores de red capturaban todas las comisiones de transacción
- Solo Tron ganó miles de millones en comisiones de gas por transferencias de USDT[^35][^36]
- Tether embolsó **cero comisiones de transacción** a pesar del volumen masivo[^37][^38]

**La Solución:**
Construir blockchains propietarias para capturar el flujo de valor de las transacciones USDT.

### Plasma: Pagos Minoristas Sin Comisiones

**Blockchain Plasma** (desarrollada con la empresa hermana Bitfinex) se enfoca en eficiencia y accesibilidad:[^39][^40]

**Características Clave:**
- **Transferencias de USDT sin comisiones** apuntando al volumen de pago minorista
- Arquitectura de alto rendimiento para millones de transacciones pequeñas
- Compite directamente con Tron (actualmente dominante para USDT minorista)
- $373 millones recaudados en venta de tokens (demostrando interés del mercado)[^41]

**Mercado Objetivo:**
Comerciantes que actualmente "ceden el 2-3% de sus ingresos" a procesadores de tarjetas, ofreciéndoles una alternativa sin comisiones.

### Stable: Capa Principal de Liquidación

**Stable** está prevista como el "hogar exclusivo para USDT" con una arquitectura de cadena dual:[^42]
- **Stable**: Cadena de liquidación principal para seguridad y finalidad
- **Plasma**: Cadena paralela de alta velocidad para microtransacciones

**Arquitectura Técnica:**

**1. Sistema de Gas Basado en USDT**
El USDT mismo se usa para pagar comisiones, por lo que los usuarios no necesitan token separado.[^43]
- Reduce la fricción de adopción
- Denominación familiar
- Sin exposición a tokens volátiles

**2. Variantes Especializadas de USDT**
- **gasUSDT**: Para pagar comisiones de transacción
- **USDT0**: Para puentes cross-chain
- **Todas las variantes**: Vinculadas 1:1 e intercambiables con USDT estándar sin costo[^44]

**3. Consenso StableBFT**
Variante personalizada de alto rendimiento de Tendermint para confiabilidad de pagos.[^45]

### Ecosistema de Circuito Cerrado

Tether está construyendo un universo USDT completo:

**Capa de Consumidor:**
- **Plasma One**: App de banco/billetera digital
  - >10% APY en depósitos de stablecoin[^46][^47]
  - 4% cashback en pagos
  - Tarjeta de débito integrada

**Capa de Comerciante:**
- Aceptación sin comisiones
- Liquidación instantánea
- Alcance global

**Capa de Infraestructura:**
- Plasma (pagos de alta velocidad)
- Stable (liquidación)
- Puentes (cross-chain)

**Resultado:** Cada aspecto del uso de USDT (transaccionar, puentear, comisiones) ocurre dentro del ecosistema USDT, capturando valor internamente.

### Validación Mayor: Asociación con PayPal

A finales de 2025, **PayPal invirtió en la red Stable** y arregló que PYUSD también sea soportado sin comisiones de gas en Stable.[^48]

Esto muestra cuán serias son las fintechs incumbentes sobre aprovechar estas nuevas cadenas dedicadas a stablecoins para pagos.

---

## 6. Gigantes de Pago Tradicionales: Visa y Mastercard

Las redes de pago tradicionales no se han quedado quietas: están integrando stablecoins en la infraestructura existente.

### Liquidación con Stablecoins de Visa

Visa expandió su **piloto de liquidación con stablecoins** en 2023-2024:[^49][^50]

**Cómo Funciona:**
1. Los comerciantes aceptan pagos con tarjeta tradicionales
2. Visa liquida balances diarios con adquirentes de comerciantes
3. La liquidación ocurre en USDC en Ethereum o Solana
4. **Resultado**: Liquidación cross-border casi instantánea en lugar de días

**Socios:**
- Worldpay (adquirente de comerciantes)
- Nuvei (procesador de pagos)
- Múltiples mercados internacionales

**Beneficios:**
- Acelera dramáticamente las liquidaciones cross-border
- Reduce la complejidad de conversión de moneda
- Mantiene la UX familiar de pago con tarjeta para consumidores
- Posiciona a Visa como "red de liquidación fiat en cadena"

### Iniciativas de Mastercard

Mastercard lanzó programas para ayudar a bancos y fintechs a integrar stablecoins:[^51]
- Infraestructura de soporte multi-cadena
- Optimización de flujos cross-border
- Pagos B2B basados en stablecoins
- Experimentación con moneda digital de banco central (CBDC)

### Interés de Comerciantes: Amazon y Walmart

Surgieron reportes de que **Amazon y Walmart** estaban estudiando stablecoins como opciones de pago específicamente para reducir comisiones de tarjetas:[^52]

Para contexto:
- Walmart procesa ~$600 mil millones anualmente
- Al 2% de comisiones de tarjeta, eso es $12 mil millones en comisiones
- Incluso 0.5% de ahorro = $3 mil millones anualmente

Este nivel de interés de comerciantes de gigantes minoristas valida el caso de negocio para pagos con stablecoins.

---

## Temas Transversales entre Iniciativas

A través de todas estas iniciativas, emergen varios patrones comunes:

### 1. Infraestructura de Propósito Específico
Moviéndose más allá de blockchains de propósito general hacia redes optimizadas para pagos (Tempo, Arc, Stable/Plasma).

### 2. Abstracción de Gas
Eliminando tokens de gas separados a favor de stablecoins como comisiones nativas (Arc, Tempo, Stable).

### 3. Integración Institucional
Grandes empresas (Visa, PayPal, Shopify) construyendo puentes entre cripto y finanzas tradicionales.

### 4. Integración Vertical
Emisores de stablecoins construyendo sus propias blockchains para capturar más valor (Circle, Tether).

### 5. Plataformas para Desarrolladores
No solo pagos, sino plataformas para construir aplicaciones de pago (Stripe, Coinbase).

### 6. Soporte Multi-Moneda
Más allá de USD: Euro (EURC), Libra, Yen stablecoins emergiendo para comercio global.

---

## Conclusión: Las "Guerras de Stablecoins"

Analistas de la industria han denominado este panorama competitivo las **"guerras de stablecoins"**[^53][^54]: una carrera para definir los rieles de pago de próxima generación.

Cada iniciativa mayor trae ventajas distintas:
- **PayPal**: Distribución mainstream
- **Stripe/Tempo**: Plataforma para desarrolladores
- **Coinbase/x402**: Estándar nativo de internet
- **Circle/Arc**: Infraestructura empresarial
- **Tether/Stable**: Alcance minorista + control del ecosistema
- **Visa**: Integración de red tradicional

En lugar de un resultado donde el ganador se lleva todo, es probable que veamos:
- **Redes especializadas** para diferentes casos de uso
- **Capas de abstracción** enrutando entre cadenas
- **Protocolos de interoperabilidad** conectando ecosistemas
- **Flexibilidad de comerciantes** aceptando múltiples stablecoins

La velocidad y escala de estas iniciativas (2023-2025) demuestran que los pagos con stablecoins han pasado de experimentales a grado de infraestructura, con miles de millones en inversión y asociaciones con las empresas más grandes del mundo.

---

## Continuar Leyendo

- [← Anterior: Por qué Stablecoins para Pagos C2B](./why-stablecoins-for-c2b-payments.md)
- [Siguiente: Arquitectura de Pago con Stablecoins →](./stablecoin-payment-architecture.md)
- [Volver a Visión General](../Overview-ES.md)

## Artículos Relacionados

- [La Capa de Abstracción de Stablecoins](./stablecoin-abstraction-layer.md)
- [Posicionamiento Estratégico de los Principales Actores](./major-players-strategies.md)
- [Hoja de Ruta de Implementación](./implementation-roadmap.md)

---

## Referencias

[^1]: [PayPal Newsroom – PayPal Launches U.S. Dollar Stablecoin (PYUSD)](https://newsroom.paypal-corp.com/2023-08-07-PayPal-Launches-U-S-Dollar-Stablecoin)
[^2]: [Paxos Trust – PYUSD Technical Documentation](https://paxos.com/pyusd)
[^3]: [PayPal – Venmo PYUSD Integration Announcement](https://newsroom.paypal-corp.com/2023-10-venmo-adds-pyusd-support)
[^4]: [PayPal PYUSD Launch Statement](https://newsroom.paypal-corp.com/2023-08-pyusd-launch)
[^5]: [PayPal PYUSD incident – Mint/burn correction (2025)](https://newsroom.paypal-corp.com/2025-pyusd-incident-response)
[^6]: [Stripe Newsroom – Shopify Merchants to Accept USDC via Stripe](https://stripe.com/newsroom/news/shopify-usdc-payments)
[^7]: [Stripe Documentation – Crypto Payment Processing](https://docs.stripe.com/crypto)
[^8]: [Shopify – Stablecoin Payment Integration Guide](https://help.shopify.com/en/manual/payments/alternative-payment-methods/cryptocurrency)
[^9]: [Stripe – Recurring Stablecoin Payments](https://stripe.com/blog/recurring-stablecoin-payments)
[^10]: [Paradigm (Matt Huang) – Tempo: The Blockchain Designed for Payments](https://www.paradigm.xyz/2025/02/tempo-blockchain-for-payments)
[^11]: [Stripe – Tempo Blockchain Announcement](https://stripe.com/blog/tempo-blockchain-launch)
[^12]: [Stripe CEO on blockchain payment optimization](https://stripe.com/blog/blockchain-payment-optimization)
[^13]: [Tempo Technical Documentation – Multi-Stablecoin Gas](https://docs.tempo.org/gas-abstraction)
[^14]: [Technical challenges of multi-currency gas fees](https://www.paradigm.xyz/2025/multi-currency-gas-challenges)
[^15]: [Tempo Protocol – Payment Primitives](https://docs.tempo.org/payment-primitives)
[^16]: [Tempo Foundation – Partnership Announcements](https://tempo.org/partners)
[^17]: [Stripe – Open Issuance Platform](https://stripe.com/blog/open-issuance-platform)
[^18]: [Stablecoin issuance for enterprise use cases](https://stripe.com/blog/enterprise-stablecoin-issuance)
[^19]: [Cognitive Revolution Podcast – Coinbase's x402 Micropayments Protocol](https://www.cognitiverevolution.ai/coinbase-x402-protocol)
[^20]: [Coinbase – x402 Protocol Documentation](https://docs.cloud.coinbase.com/x402)
[^21]: [x402 Foundation – Use Cases for AI Agent Payments](https://x402.org/use-cases)
[^22]: [x402 Foundation Launch Announcement](https://x402.org/launch)
[^23]: [Circle – Arc Blockchain Launch Announcement](https://www.circle.com/blog/introducing-arc-blockchain)
[^24]: [Circle on limitations of existing blockchain infrastructure](https://www.circle.com/blog/blockchain-payment-limitations)
[^25]: [Circle Arc Documentation – USDC Gas Mechanism](https://developers.circle.com/arc/docs/usdc-gas)
[^26]: [Circle Arc – Built-in FX Engine Technical Details](https://developers.circle.com/arc/docs/fx-engine)
[^27]: [Arc finality and performance benchmarks](https://developers.circle.com/arc/docs/performance)
[^28]: [Circle Arc – Privacy Features Overview](https://developers.circle.com/arc/docs/privacy)
[^29]: [Enterprise privacy requirements for on-chain payments](https://www.circle.com/blog/enterprise-privacy-requirements)
[^30]: [Circle Arc – Enterprise Integration Guide](https://developers.circle.com/arc/docs/enterprise-guide)
[^31]: [Circle – Arc Vertical Integration Strategy](https://www.circle.com/blog/arc-integration-strategy)
[^32]: [Circle Arc positioning for enterprise adoption](https://www.circle.com/blog/arc-enterprise-positioning)
[^33]: [Arc vs. public chain comparison for payment use cases](https://messari.io/report/arc-vs-public-chains-comparison)
[^34]: [ChainCatcher – Next Battle of Stablecoins (Arc, Plasma, Stable, Tempo)](https://www.chaincatcher.com/en/article/2024/stablecoin-blockchain-wars)
[^35]: [Tether transaction volume analysis (2024-2025)](https://www.theblock.co/data/stablecoins/usdt-transaction-volume)
[^36]: [Tron gas fee revenue from USDT transactions](https://tronscan.org/#/data/stats/gas-fees)
[^37]: [Tether revenue model before Plasma/Stable](https://tether.io/investor-relations/revenue-model)
[^38]: [Opportunity cost analysis for Tether](https://messari.io/report/tether-opportunity-cost-analysis)
[^39]: [Tether – Plasma Blockchain Announcement](https://tether.io/news/plasma-blockchain-launch)
[^40]: [Bitfinex – Plasma Development Partnership](https://www.bitfinex.com/posts/plasma-partnership-tether)
[^41]: [Plasma token sale results and market reception](https://www.coindesk.com/markets/plasma-token-sale-results)
[^42]: [Tether Stable – Architecture Overview](https://tether.io/stable/architecture)
[^43]: [Tether Stable – Gas Fee Mechanism](https://tether.io/stable/gas-fees)
[^44]: [Tether – USDT Variants Documentation (gasUSDT, USDT0)](https://tether.io/developers/usdt-variants)
[^45]: [StableBFT consensus mechanism details](https://tether.io/stable/consensus)
[^46]: [O'Daily News – Stablecoin Chains (Plasma One, Stable Pay)](https://www.odaily.news/en/post/stablecoin-payment-chains-2025)
[^47]: [Plasma One – Digital Wallet Launch](https://plasma.one/wallet)
[^48]: [PayPal investment in Stable network announcement](https://newsroom.paypal-corp.com/stable-network-investment)
[^49]: [Visa News – Stablecoin Settlement Expansion](https://usa.visa.com/visa-everywhere/blog/expanding-stablecoin-settlement-capabilities.html)
[^50]: [Visa USDC settlement pilot results](https://usa.visa.com/visa-everywhere/blog/usdc-settlement-pilot-results.html)
[^51]: [Mastercard stablecoin integration initiatives](https://www.mastercard.com/news/perspectives/2025/stablecoin-integration)
[^52]: [Reports: Amazon and Walmart stablecoin exploration](https://www.reuters.com/technology/amazon-walmart-explore-stablecoin-payments)
[^53]: [Industry analysis – "Stablecoin Wars" competitive landscape](https://www.coindesk.com/business/stablecoin-wars-analysis)
[^54]: [ChainCatcher – Competitive Analysis of New Stablecoin Chains](https://www.chaincatcher.com/en/article/2025/stablecoin-chain-competition)

---

*Parte de la serie del newsletter Chainsights sobre stablecoins, pagos y comercio C2B.*
