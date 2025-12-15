#  Tiendas 3E simulación 

---

## Página web y sistema de organización


---

1️⃣ README.md

# Sistema Web de Inventario y Control de Caducidades

![Logo del Proyecto](ruta/a/tu/logo-readme.png)

## Descripción
Este proyecto consiste en un sistema de inventario web con control de caducidades, desarrollado con HTML, CSS y JavaScript puro. Permite visualizar productos, controlar fechas de caducidad y simular roles (Administrador, Auditor, Cajero) sin necesidad de backend.

## Tecnologías
- HTML
- CSS
- JavaScript
- JSON (como base de datos local)
- LocalStorage (persistencia de datos)
- Vercel (despliegue online)

## Funcionalidades
- Mostrar inventario completo en tabla dinámica
- Tabla de caducidades con alertas visuales
- Simulación de roles y permisos
- Persistencia de cambios en LocalStorage
- Preparado para migración futura a SQL/Supabase y autenticación

## Instalación / Uso
1. Clonar o descargar el repositorio
2. Abrir `index.html` en cualquier navegador moderno
3. Todas las funciones se ejecutan localmente (no requiere backend)
4. Para desplegar, se puede usar Vercel u otro hosting estático

## Capturas de pantalla
![Inventario](ruta/a/tu/captura-inventario.png)
![Caducidades](ruta/a/tu/captura-caducidades.png)

## Logos
![Logo 1](ruta/a/tu/logo1.png)
![Logo 2](ruta/a/tu/logo2.png)
![Logo 3](ruta/a/tu/logo3.png)

## Créditos
Proyecto realizado por [Tu Nombre], como práctica educativa y demostración funcional.

> Solo reemplaza ruta/a/tu/... con tus archivos reales.




---

2️⃣ CSS para logos en HTML (ajustado y responsive)

/* logos.css */
.logo {
  max-width: 150px;  /* limita tamaño */
  max-height: 50px;
  width: auto;
  height: auto;
  margin: 10px;
  display: inline-block;
}

/* contenedor flexible para varios logos */
.logos-container {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  justify-content: center;
  align-items: center;
}

Ejemplo de uso en HTML:

<div class="logos-container">
  <img src="logo1.png" class="logo" alt="Logo 1">
  <img src="logo2.png" class="logo" alt="Logo 2">
  <img src="logo3.png" class="logo" alt="Logo 3">
</div>

Con esto tus logos siempre se ven bien, ajustados y centrados.


---

3️⃣ Imagen para README (placeholder)

Puedes usar un screenshot de tu tabla de inventario o logo principal.

Ejemplo de placeholder:


ruta/a/tu/logo-readme.png

> Solo reemplázalo por tu captura final de inventario, caducidades o logotipo oficial.




---

