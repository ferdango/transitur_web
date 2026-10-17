# transitur.pe

Sitio público de Transitur Perú SAC en GitHub Pages (dominio `transitur.pe`, DNS en RCP).

| Ruta | Qué hace |
|---|---|
| `/` y `/login` | Redirigen al inicio de sesión del sistema interno (`transitur-sistema`, Cloudflare Workers) |
| `/reclamos` | Libro de Reclamaciones virtual (Ley N° 29571). Guarda en el proyecto Supabase de reclamaciones con la clave pública; solo puede insertar mediante la RPC `registrar_reclamacion` |
| cualquier otra | `404.html` con enlaces al sistema y al libro |

No publicar aquí documentos internos (reservas, calendarios, reportes): este repositorio es público y su historial también.
