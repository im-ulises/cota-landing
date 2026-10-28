# BarreraMX · Barreras antiinundación modulares

Catálogo comercial estático para presentar los modelos 50X y 100X y preparar solicitudes de cotización desde Ciudad Juárez, Chihuahua.

## Publicación en Cloudflare Pages

- **Proveedor:** GitHub
- **Repositorio:** im-ulises/cota-landing
- **Rama de producción:** main
- **Framework preset:** None
- **Build command:** dejar vacío
- **Build output directory:** raíz del repositorio
- **Project name:** cota-landing (se conserva para mantener la URL existente)

Cloudflare Pages genera despliegues automáticos al actualizar main si la integración con GitHub está conectada.

## Nomenclatura comercial

Los productos se presentan al público como BarreraMX 50X y BarreraMX 100X. La trazabilidad con códigos internos del fabricante se maneja fuera de este repositorio público.

## Tecnología y límites

HTML, CSS y JavaScript sin backend ni proceso de pagos. El formulario abre la aplicación de correo del visitante (mailto); no almacena automáticamente registros en un CRM.

La calculadora divide el ancho del acceso entre 0.65 m (50X) o 0.96 m (100X) y redondea hacia arriba. Esta es una **estimación geométrica** y no una especificación de instalación.

Los seis archivos WebP que se muestran en la página son **renders ilustrativos** creados con referencias de geometría de los modelos. No son fotografías de instalaciones reales, pruebas hidráulicas ni material oficial del fabricante. La fotografía original de inundación se conserva en el repositorio, pero ya no se utiliza en la página.

Precios de venta, disponibilidad, terminales, anclajes, sellos y prestaciones deben confirmarse con el fabricante antes de hacer promesas comerciales. El nombre BarreraMX debe verificarse antes del registro y uso de marca.

## Desarrollo local

Ejecutar desde la raíz del repositorio:

    python3 -m http.server 8080

Abrir http://localhost:8080.
