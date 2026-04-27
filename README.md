# ATLAS — Sistema de Diagnóstico de Estrategia

ATLAS es un sistema interactivo de diagnóstico estratégico diseñado para identificar el cuello de botella principal de un negocio antes de ejecutar marketing.

No es un formulario.  
Es un árbol de decisión con lógica de bloqueo, basado en evidencia.

---

## 🎯 Propósito

Detectar si el problema es:

- Pre-estratégico (fundación) → producto, mercado, posicionamiento  
- Estratégico (marketing) → captación, conversión, retención, monetización  

Regla central:

> La estrategia correcta es la que resuelve el cuello de botella principal.

---

## 🧠 Lógica del sistema

ATLAS opera en 3 capas:

### 1. Fundación (bloqueante)
Evalúa si el negocio es viable antes de aplicar marketing.

Si falla aquí:
- Se detiene el flujo
- Se muestra un bloqueador estratégico
- Se recomienda resolver antes de continuar

### 2. Marketing
Identifica el punto exacto donde se rompe el funnel:

- Alcance (no te encuentran)
- Conversión (no compran)
- Retención (no regresan)
- Monetización (ticket bajo)

### 3. Output
Genera automáticamente:

- Score de fundación
- Diagnóstico estructurado
- Problema dominante
- Hipótesis de trabajo
- Acción concreta
- Playbook recomendado
- Routing a sistema externo (Funnel Atlas)

---

## ⚙️ Sistema de scoring

El score mide la viabilidad estructural del negocio.

| Tipo de variable | Peso |
|------------------|------|
| Problema validado / producto / modelo | Crítico (−30) |
| ICP / posicionamiento | Alto (−15) |
| Datos de funnel | Medio (−10) |

### Interpretación

- 80–100 → fundación sólida (puedes ejecutar marketing)
- 50–79 → riesgo medio (requiere ajustes)
- <50 → error estructural (detener marketing)

---

## 📊 Evidencia (clave del sistema)

ATLAS no funciona con opinión.

Cada respuesta crítica requiere evidencia:

Ejemplos válidos:
- 5+ entrevistas reales con ICP
- Datos de funnel (mínimo 4 semanas)
- Win/Loss analysis
- Feedback directo de clientes

Sin evidencia:
> el output es una hipótesis, no un diagnóstico.

---

## 🧩 Arquitectura

Archivo principal:

- atlas_v2.html 

Incluye:

- UI completa (HTML + CSS)
- Lógica de navegación (JS inline)
- Sistema de scoring
- Generador de output dinámico
- Modo oscuro / claro
- Manual integrado (modal)

---

## 🔁 Flujo de uso

text Fundación → validación estructural     ↓ Marketing → identificación de cuello de botella     ↓ Output → hipótesis + acción + playbook     ↓ Funnel Atlas → ejecución táctica 

---

## 🧪 Casos de uso

- Diagnóstico rápido de clientes
- Auditorías de marketing
- Toma de decisiones bajo incertidumbre
- Base para workshops o consultoría
- Generación de briefs estratégicos

---

## 🔗 Relación con otros sistemas

ATLAS forma parte de:

AMPLIFY (sistema completo)

- A → Analyze (ATLAS vive aquí)
- M → Map
- P → Position
- L → Leverage
- I → Implement
- F → Feedback
- Y → Yield

Y conecta con:

- Funnel Atlas (ejecución táctica)

---

## ⚠️ Limitaciones

- No reemplaza criterio estratégico
- Depende de la calidad de la evidencia
- No mide performance real, solo estructura
- El score es orientativo, no absoluto

---

## 🚀 Setup

No requiere instalación.

Solo abre el archivo:

bash atlas_v2.html 

Opcional:
- Deploy en GitHub Pages
- Integración en Notion (embed)
- Uso como herramienta interna

---

## 📌 Filosofía

ATLAS no intenta decirte qué hacer primero.

Te dice:

> qué NO deberías estar haciendo todavía.

---

## 📄 Licencia

Uso libre para fines educativos o internos.  
Para uso comercial o adaptación, se recomienda extender con contexto propio.

---

## ✍️ Autor

Sistema diseñado como herramienta de diagnóstico estratégico basada en:

- Lean Startup (Eric Ries)
- Continuous Discovery (Teresa Torres)
- Positioning (April Dunford)
- Value Proposition Design (Osterwalder)

---

## 🧭 Siguiente paso

Usa el output para activar ejecución en:

→ Funnel Atlas  
→ Playbooks específicos por estrategia  
→ Sistemas de contenido o adquisición  

-
