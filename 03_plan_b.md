# 💎 Plan B — Token Comunitario + DAO: Guía Paso a Paso

> **Plazo:** 10–16 semanas DESPUÉS del Plan A · **Meta:** 15–30 ETH · **Riesgo:** 🟡 Medio
> Ejecutar SOLO después de que Plan A logre ≥40% de sell-through.

---

## Por Qué el Plan B Viene Después

El Plan A es tu **prueba de concepto**. El Plan B es tu **motor de escala**.

Sin el Plan A primero:
- No tienes datos de ventas para demostrar
- No tienes comunidad de holders para votar en el DAO
- No tienes credibilidad para justificar un token

Con el Plan A exitoso:
- Tienes compradores reales = validación de mercado
- Tienes holders comprometidos = primeros stakers
- Tienes transparencia on-chain = confianza para nuevos inversores

---

## Fase 1: Diseño del Token *(Semanas 1–2)*

### ✅ Paso 1 — Tokenomics de $WOLI

**Suministro total:** `10,000,000 $WOLI`

**Tres funciones principales:**

| Función | Descripción |
|---------|-------------|
| 🗳️ **Gobernanza** | Apostar $WOLI para votar en decisiones del DAO |
| 💰 **Recompensas** | Ganar $WOLI de hitos de ventas proporcionalmente |
| 🏷️ **Descuentos** | Tener $WOLI = descuento escalonado en productos |

**Distribución del suministro:**

| Categoría | % | Tokens | Notas |
|-----------|---|--------|-------|
| 🌍 Venta Pública | 40% | 4,000,000 | Evento de generación de tokens |
| 🔒 Fondo de Recompensas | 30% | 3,000,000 | Bloqueado · distribuido en hitos |
| 👥 Equipo | 20% | 2,000,000 | Adquisición lineal 2 años · cliff 6 meses |
| 📣 Marketing/Socios | 10% | 1,000,000 | Influencers · asociaciones · listados |

---

### ✅ Paso 2 — Documento Público de Tokenomics

> ⚠️ **Obligatorio ANTES de desplegar cualquier contrato**

El documento debe incluir:
- [ ] Suministro total y distribución
- [ ] Calendario de adquisición del equipo
- [ ] Mecanismos de activación de recompensas
- [ ] Cómo funciona el DAO
- [ ] Qué NO garantiza el token

**Publicar en:** Sitio web · Discord (fijado) · Twitter/X

> 💡 La opacidad en tokenomics es lo que mata proyectos. Sé vergonzosamente transparente.

---

## Fase 2: Configuración del DAO *(Semanas 3–5)*

### ✅ Paso 3 — Desplegar Contrato ERC-20

**Herramienta:** [OpenZeppelin Contracts Wizard](https://wizard.openzeppelin.com)

Configuración:
```
Tipo:          ERC-20 con ERC20Votes (compatible con Snapshot)
Cadena:        Base
Propietario:   Safe multisig (mismo del Plan A)
Costo:         ~0.02 ETH
```

**Extensiones a incluir:**
- ✅ `ERC20Votes` — votación compatible con Snapshot
- ✅ `Ownable` — control de acuñación
- ✅ Minteo con límite de tiempo (calendario de adquisición)

---

### ✅ Paso 4 — Configurar Snapshot.org

1. Ir a [snapshot.org](https://snapshot.org)
2. Crear espacio `wolicbd.eth`
3. Configurar: `100 $WOLI = 1 voto`
4. Vincular al contrato ERC-20 desplegado

**Primera votación (estratégica — debe ser fácil y emocionante):**

> 🗳️ *"¿Cuál sabor de tintura fabricamos primero — cítrico o menta?"*

Esto demuestra que el DAO funciona y crea compromiso emocional inmediato.

---

### ✅ Paso 5 — Pool de Liquidez Inicial

1. Tomar 20% del ETH del Plan A (fondo de recompensas) + recaudación del token
2. Crear pool `$WOLI/ETH` en [Uniswap v3](https://app.uniswap.org) en Base
3. Comunicar claramente: *"Liquidez inicial es baja. Esto es una construcción a largo plazo."*

> ⚠️ Gestión de expectativas aquí previene pánico y resentimiento de la comunidad

---

## Fase 3: Venta del Token *(Semanas 6–10)*

### ✅ Paso 6 — Evento de Generación de Tokens

**Herramienta:** [Juicebox.money](https://juicebox.money) o página de claim en Manifold

**Precio inicial:** `$0.01 USD por $WOLI`

**Potencial de recaudación:**
```
4,000,000 tokens × $0.01 = $40,000 USD (venta completa)
Objetivo mínimo viable: 50% → $20,000 USD
```

---

## Fase 4: Activación B2B *(Mes 4+)*

### ✅ Paso 7 — White-Label via DAO

El DAO vota sobre qué marcas acercarse para manufactura white-label.

**Proceso:**
1. El equipo propone 3 candidatos de marcas
2. La comunidad vota (Snapshot)
3. La marca ganadora recibe propuesta formal de Woli
4. Holders tienen incentivo financiero para traer clientes = tu equipo de ventas

**Servicios white-label disponibles:**
- Manufactura de productos bajo marca del cliente
- Exportación/importación en región latinoamericana
- Webinars educativos con médicos (español/inglés)
- Desarrollo web (frontend, diseño)

---

## Hitos de Ventas y Recompensas

| Hito | Ventas | Acción |
|------|--------|--------|
| 🥉 Hito 1 | 150 unidades | Distribuir 10% del fondo de recompensas a stakers de $WOLI |
| 🥈 Hito 2 | 300 unidades | Distribuir 15% adicional + desbloquear preventa de tinturas |
| 🥇 Hito 3 | 1,000 unidades | Distribuir 20% adicional + DAO vota hoja de ruta de cultivo |

> 📢 **Publicar CADA recibo y hito públicamente. La evidencia on-chain ES tu marketing.**

---

## 📈 Métricas de Éxito Plan B

| Métrica | Meta |
|---------|------|
| Sell-through del token (primera semana) | ≥ 25% |
| Participación en primera votación DAO | ≥ 50 voters |
| Liquidez pool $WOLI/ETH | ≥ $5,000 USD |
| Deals white-label activados por comunidad | ≥ 1 en primeros 3 meses |

---

## 🛠️ Stack Adicional para Plan B

```
Token ERC-20:   OpenZeppelin Wizard
Gobernanza:     Snapshot.org
Liquidez:       Uniswap v3 (Base)
Venta token:    Juicebox.money
Analytics:      Dune Analytics (dashboard público)
```
