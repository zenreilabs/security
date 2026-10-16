# Canal de seguridad de Zenrei Labs

> Repositorio **público** que existe por una sola razón: que cualquiera pueda **reportar una vulnerabilidad**
> de nuestros productos sin depender de que el código sea público.

## Cómo reportar

1. **Vía preferida:** [aviso privado de GitHub](https://github.com/zenreilabs/security/security/advisories/new)
2. **Correo:** `security@sismograph.com` *(se activa cuando el dominio esté operativo)*

Incluye: producto afectado, descripción, impacto, pasos de reproducción, URL/versión y si lo has explotado más allá de lo necesario para demostrarlo.

## Productos en alcance

| Producto | Repositorio | Nota |
|---|---|---|
| **Sismograph** | `zenreilabs/sismograph` *(privado)* | web, PWA, API, pipeline de datos |
| API pública | `api.sismograph.com` | — |
| Embeds para medios | `/embed` | — |

**Fuera de alcance:** servicios de terceros (USGS, EMSC, Vercel, Supabase, Cloudflare) — repórtalos a su propio programa; denegación de servicio; ingeniería social; y cualquier afirmación de que el producto debería **predecir terremotos** (no es un defecto, es una decisión de diseño).

## Nuestro compromiso

| Compromiso | Valor |
|---|---|
| Acuse de recibo | ≤ 72 h |
| Evaluación inicial y severidad | ≤ 7 días |
| Corrección de lo crítico | ≤ 7 días desde la confirmación |
| Crédito público | si lo quieres |
| Divulgación coordinada | 90 días o antes si hay parche |

**Salvoconducta:** no emprenderemos acciones legales contra investigación de buena fe que respete esta política, no acceda a datos de terceros, no degrade el servicio y no explote el hallazgo más allá de lo necesario para demostrarlo.

## Prioridad especial: integridad del catálogo

En un producto sísmico, **la integridad pesa más que la confidencialidad**: publicar un terremoto falso o silenciar uno real puede causar pánico. Un hallazgo que permita **alterar, inyectar o retirar eventos** del catálogo se trata como severidad máxima (S1).
