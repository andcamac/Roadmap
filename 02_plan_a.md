# 🚀 Plan A — Drop NFT Phygital: Guía Paso a Paso

> **Plazo:** 8–10 semanas · **Meta:** 4–5 ETH · **Riesgo:** 🟢 Bajo
> Ejecutar PRIMERO. Este es tu punto de partida y prueba de concepto.

---

## Fase 1: Fundación Legal y Estructural *(Semanas 1–2)*

### ✅ Paso 1 — Descargo de Responsabilidad Legal

**Acción:** Contratar abogado costarricense (~$200 USD) para redactar descargo de una página.

El descargo debe indicar claramente:

- [ ] Los NFTs son **tokens de utilidad**, no valores de inversión
- [ ] Representan acceso de preventa a bienes físicos fabricados en Costa Rica
- [ ] Los holders no pueden importar donde esté prohibido por ley
- [ ] Las recompensas están condicionadas al logro de **hitos de ventas**
- [ ] Woli CBD S.A. no es responsable por importación o envío internacional

> ⚠️ **Publicar en:** Página de acuñación · Discord · Twitter fijado · Sitio web

---

### ✅ Paso 2 — Documentos de Respaldo (subir a IPFS)

- [ ] Certificado de registro corporativo de Woli CBD S.A. (renovar ahora)
- [ ] Registro de Fucannamed CR
- [ ] Certificados de lote / pruebas de laboratorio del ungüento
- [ ] Fotografía profesional del producto (al menos 10 fotos de calidad)
- [ ] Video corto del proceso de manufactura (60 segundos mínimo)

**Herramienta:** [Pinata.cloud](https://pinata.cloud) — plan gratuito es suficiente

> 💡 Estos documentos son tu **prueba de trabajo**. Todo inversor serio los buscará.

---

## Fase 2: Configuración Técnica *(Semanas 2–4)*

### ✅ Paso 3 — Billetera Multi-Firma (Gnosis Safe)

1. Ir a [safe.global](https://safe.global)
2. Crear billetera **2-de-3** (los 3 fundadores como firmantes)
3. **Publicar esta dirección públicamente ANTES de abrir la acuñación**
4. Ningún fundador puede mover fondos solo — esta es tu capa de confianza

```
Configuración recomendada:
Firmante 1: Fundador A
Firmante 2: Fundador B  
Firmante 3: Fundador C
Threshold: 2 de 3
```

---

### ✅ Paso 4 — Desplegar Contrato en Manifold

| Parámetro | Valor |
|-----------|-------|
| **Cadena** | Base (recomendada) o Abstract |
| **Estándar** | ERC-1155 (soporta los 3 niveles en 1 contrato) |
| **Royalties** | 5% (ganancias en mercado secundario) |
| **Nombre del contrato** | `WOLI-GENESIS-001` |
| **Costo de despliegue** | ~0.05 ETH |

**Pasos:**
1. Ir a [manifold.xyz](https://manifold.xyz)
2. Conectar la billetera Safe multisig
3. Crear nuevo contrato ERC-1155
4. Configurar los 3 tiers como tokens separados dentro del mismo contrato
5. Configurar la página de acuñación con fotos, video y links de documentos

---

### ✅ Paso 5 — Arte y Metadatos NFT

**Herramienta:** Canva Pro ($13/mes) es suficiente

| Nivel | Tratamiento Visual |
|-------|-------------------|
| 🌱 Cultivador | Foto del producto · marco verde · número de lata visible |
| 🌿 Cultivador Pro | Doble lata · marco azul · badge "Pro" |
| 🏅 Fundador | Marco dorado · tratamiento premium · badge "Genesis Founder" |

**Flujo de subida:**
```
Crear imagen → Subir a Pinata (IPFS) → Copiar hash → Crear JSON metadata → Subir JSON a Pinata
```

---

## Fase 3: Construcción de Comunidad *(Semanas 3–5)*

> 🎯 **Meta: 200 billeteras calientes ANTES de abrir la acuñación pública**
> Esta es la fase más crítica. La mayoría de los drops fallidos fallan aquí.

### ✅ Paso 6 — Estrategia Twitter/X

- [ ] Publicar hilo "construyendo en público" sobre el viaje de 4 años de Woli
- [ ] Etiquetar: `#cannabis #RWA #phygital #DeSci #web3 #NFT #CostaRica`
- [ ] Publicar fotos del producto con caption: *"200 latas vendidas. Cero publicidad. Ahora vamos on-chain."*
- [ ] Mensajes personales a las **20 principales cuentas** de cannabis-cripto (no plantillas, mensajes reales)
- [ ] Interactuar con posts de otros proyectos phygital/RWA con comentarios genuinos

**Frecuencia mínima:** 1 post diario durante las semanas 3–5

---

### ✅ Paso 7 — Estrategia Discord

**Servidores a unirse:**
1. Una comunidad de cannabis
2. Un servidor enfocado en RWA
3. Un servidor Web3 latinoamericano
4. Un servidor DeSci
5. Una comunidad general de NFTs

> ⏳ **Ser genuinamente útil durante 2 semanas ANTES de mencionar Woli**

**Canales para el Discord de Woli:**
- `#anuncios`
- `#info-productos`
- `#faq-canje`
- `#preview-dao`
- `#lista-blanca`

---

### ✅ Paso 8 — Activar Fucannamed CR

- [ ] Publicar en todos los canales de Fucannamed CR sobre el drop
- [ ] Crear post educativo: transparencia del cannabis → trazabilidad blockchain
- [ ] Invitar seguidores existentes a unirse al Discord de Woli

---

## Fase 4: Ejecución de la Acuñación *(Semanas 6–8)*

### ✅ Paso 9 — Ventana de Lista Blanca (72 horas)

**Formulario de lista blanca:** Google Form simple con campos:
- Dirección de billetera ETH
- Twitter/X (opcional)
- ¿Cómo encontraste Woli?

**Precios lista blanca (10% de descuento):**

| Nivel | Precio Público | Precio Lista Blanca |
|-------|---------------|---------------------|
| Cultivador | 0.01 ETH | 0.009 ETH |
| Cultivador Pro | 0.025 ETH | 0.0225 ETH |
| Fundador | 0.06 ETH | 0.054 ETH |

---

### ✅ Paso 10 — Acuñación Pública (7 días)

**Durante la ventana de acuñación:**
- [ ] Publicar actualización diaria del % de venta en X
- [ ] Responder CADA pregunta en Discord dentro de 2 horas
- [ ] Si 50% se vende en 48h → publicar hilo festivo de FOMO
- [ ] **NO extender más allá de 7 días** — la escasez es real

---

## Fase 5: Distribución de Fondos *(Semanas 8–10)*

### ✅ Paso 11 — Asignación de Fondos

Basado en una recaudación de **4.5 ETH**:

| Categoría | % | ETH | Uso |
|-----------|---|-----|-----|
| 🔒 Fondo de Recompensas | 30% | ~1.35 ETH | BLOQUEADO hasta hitos de ventas |
| 🏭 Manufactura | 42% | ~1.89 ETH | Convertir a USD via Binance · 2 tinturas |
| 📣 Marketing | 14% | ~0.63 ETH | Redes sociales · influencers · PR |
| 👥 Gastos del Equipo | 7% | ~0.315 ETH | Costos operativos |
| 💻 Tecnología | 7% | ~0.315 ETH | Manifold · IPFS · sitio web |

> ⚠️ El fondo de recompensas NO se toca hasta alcanzar el hito del 50% de ventas físicas

---

### ✅ Paso 12 — Entrega y Recompensas

1. **Entrega física:** Holders envían datos via Google Form → Woli envía producto → Publicar foto de paquetes (dirección borrosa)
2. **Activación de recompensas:** Al vender el 50% del inventario → distribuir proportional a holders via Safe batch transfer o Merkle drop
3. **Publicar todo:** Cada recibo de venta, cada envío, cada hito — on-chain y en redes

> 💡 Esta transparencia radical es el marketing más poderoso para el siguiente drop

---

## 📈 Métricas de Éxito

| Métrica | Meta |
|---------|------|
| Billeteras calientes antes del mint | ≥ 200 |
| Sell-through lista blanca (72h) | ≥ 30% |
| Sell-through total (7 días) | ≥ 50% |
| Tasa de conversión comunidad → mint | ≥ 15% |
| Tiempo de respuesta en Discord | ≤ 2 horas |

---

## 🛠️ Stack Tecnológico

```
Billetera:     Safe (safe.global) — multisig 2 de 3
Contrato:      Manifold.xyz — ERC-1155
Cadena:        Base o Abstract
Arte/diseño:   Canva Pro
IPFS:          Pinata.cloud
Marketplace:   Magic Eden / OpenSea
Gobernanza:    Snapshot.org (Plan B)
Conversión:    Binance (ETH → USD)
```
