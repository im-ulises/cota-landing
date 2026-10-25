# COTA · Protección preventiva contra inundaciones

Sitio estático de captación de solicitudes de evaluación en Ciudad Juárez, Chihuahua.

## Publicación en Cloudflare Pages

- **Proveedor**: GitHub
- **Repositorio**: `im-ulises/cota-landing`
- **Rama de producción**: `main`
- **Framework preset**: `None`
- **Build command**: dejar vacío (sin compilación)
- **Build output directory**: `/` (raíz del repositorio)
- **Project name**: `cota-landing` (si está disponible)

Cloudflare Pages generará despliegues automáticos al actualizar `main` una vez conectada la integración con GitHub.

## Tecnología y límites actuales

HTML / CSS / JavaScript, sin backend. El formulario abre la aplicación de correo del visitante (`mailto:`); no almacena automáticamente los registros en un CRM ni cobra pedidos. No se anuncian garantías técnicas, fechas de entrega ni inventarios confirmados.

Contenido gráfico: fotografía proporcionada por el propietario del sitio, recortada y optimizada; no contiene identificadores visibles de viviendas/vehículos.

## Desarrollo local

```bash
python3 -m http.server 8080
```

Abrir `http://localhost:8080`.
