# Francisco Paredes

Ingeniero de Sistemas en Mérida, Venezuela. Fundador de [VenusTech](https://venustechfp.com) y socio de CoreBiz.

Desarrollo páginas web y sistemas a medida, y los pongo en marcha en servidores que yo mismo administro. Tengo más de 5 años de experiencia en soporte técnico, servidores Linux y redes, así que me encargo de todo el camino: desde la base de datos hasta el despliegue en producción. Trabajo también en remoto.

## Tecnologías

- **Desarrollo:** TypeScript, JavaScript, React, PHP 8, Astro, Tailwind CSS, Bootstrap 5, Chart.js
- **Bases de datos:** MySQL, PostgreSQL, SQLite
- **Infraestructura:** Linux (Ubuntu, Debian), Docker, Nginx, Proxmox, Cloudflare, Windows Server
- **Redes y monitoreo:** UISP / airFiber, Grafana, Uptime Kuma

## Proyectos

### [VenusTech, sitio web y panel de control](https://github.com/fjavierpared/VenusTech)

Mi web de negocio, en producción en [venustechfp.com](https://venustechfp.com). Páginas estáticas rápidas y con buen SEO, más un panel propio con analítica sin cookies, mensajes de contacto, blog con imágenes y video, y publicación automática en Instagram. Desplegada con Docker y Nginx en un VPS.

Astro, Tailwind CSS, SQLite, Docker, Nginx.

### Servidor propio en producción

Administro mi propio VPS con Ubuntu Server, donde alojo mis proyectos con dominio propio ([venustechfp.com](https://venustechfp.com)). Lo monté para tener varios proyectos en el mismo servidor, cada uno aislado en sus contenedores:

- Nginx como proxy inverso, con certificados SSL de Let's Encrypt que se renuevan solos.
- Contenedores con PHP-FPM 8.5, MySQL 8.4, PostgreSQL 18 y Node.js, todos en una red interna de Docker. Las bases de datos no quedan expuestas a internet.
- Dominio gestionado en Cloudflare, con proxy y SSL en modo Full (Strict).
- Seguridad: firewall UFW, Fail2ban para SSH y Nginx, acceso SSH con llave Ed25519 y rotación de logs.
- Monitoreo con Uptime Kuma y administración con Portainer.
- Reglas fijas para cada proyecto nuevo: su propio subdominio, contenedor, puerto interno y configuración de Nginx.

Ubuntu Server, Docker, Nginx, Let's Encrypt, Cloudflare, MySQL, PostgreSQL.

### CoreBiz, ERP para pymes (código privado)

Sistema de gestión empresarial pensado para Venezuela, que desarrollo en sociedad dentro de la organización CoreBizSystem: facturación, inventario, caja multimoneda en USD y Bs, cuentas por cobrar y por pagar, comandas y reportes en tiempo real. Es multiempresa y multisucursal, e incluye un asistente con inteligencia artificial. La primera versión era PHP y MySQL; la migramos a React, TypeScript y PostgreSQL. [Ver el caso](https://venustechfp.com/proyectos/corebiz-erp).

React, TypeScript, PostgreSQL.

### Sistema de operaciones para un centro de emergencias (código privado)

Aplicación web que reemplazó el control en papel de la asistencia del personal, los visitantes y las operaciones de emergencia, desde la llamada hasta el cierre de cada caso. Tiene permisos por módulo y por acción, auditoría de cada cambio y reportes oficiales en PDF y Excel. Son 58 tablas, 27 módulos y 29 endpoints de API. [Ver el caso](https://venustechfp.com/proyectos/sistema-operaciones-emergencias).

PHP 8, MySQL, JavaScript, Bootstrap 5, Chart.js, FPDF.

### [Infraestructura UISP para una red airFiber](https://github.com/fjavierpared/airfiber-uisp-infrastructure)

Migración de la consola UISP de una red inalámbrica a un servidor dedicado con Ubuntu Server y Docker: backup y restauración sin pérdida de datos, reconexión automática de todas las antenas y monitoreo con Grafana y Uptime Kuma.

Ubuntu Server, Docker, UISP, Grafana, Uptime Kuma.

### [PlantillaCRUD](https://github.com/fjavierpared/PlantillaCRUD)

Plantilla de panel administrativo en JavaScript puro, sin compilar: login, menú con buscador, tema claro y oscuro, identidad configurable desde el panel, tablas, gráficas y reportes imprimibles. La uso como base para arrancar sistemas nuevos.

JavaScript, HTML, CSS, Chart.js.

CoreBiz y el sistema del centro de emergencias son privados porque uno es un producto comercial de la sociedad y el otro es de un cliente. Puedo mostrarlos en una entrevista.

## Contacto

- Web: [venustechfp.com](https://venustechfp.com)
- Correo: [venustech47@gmail.com](mailto:venustech47@gmail.com)
- Instagram: [@venustech47](https://www.instagram.com/venustech47)
- WhatsApp: [+58 424 712 6299](https://wa.me/584247126299)
