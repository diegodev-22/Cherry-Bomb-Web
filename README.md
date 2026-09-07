# 🍒 Cherry Bomb Web

![Cherry Bomb Logo](/public/Logo_CHERRY_BOMB.png)

> La plataforma de e-commerce enfocada en moda, diseñada para cerrar ventas directamente por WhatsApp.

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-16.0-black?style=flat&logo=next.js)
![React](https://img.shields.io/badge/React-19.0-blue?style=flat&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?style=flat&logo=tailwind-css)
![Status](https://img.shields.io/badge/Estado-Activo-green)

</div>

---

## Sobre el Proyecto

¡Hola! Este es **Cherry Bomb**, una aplicación web de ventas.

Se diseño un catálogo fluido donde los usuarios pueden armar su pedido y enviarlo listo por WhatsApp. De esta forma, no solo se elimino la fricción de los procesos de registro tradicionales, sino que también se logro una solución **gratuita**, sin comisiones por ventas ni costos de mantenimiento.

Recientemente se refactorizo todo el código para aprovechar la potencia de **Next.js 16** y el nuevo **Tailwind CSS 4**, logrando que la navegación sea instantánea y se sienta muy moderna en móviles.

## Lo que se ha implementado

### Experiencia de Compra
La app se enfoca mucho en los detalles que mejoran la usabilidad:
- **Carrito Inteligente:** Se implemento persistencia con `LocalStorage`, así que si recargas la página, tus productos siguen ahí.
- **Control Total:** Se puso selectores intuitivos para sumar o restar cantidades sin complicaciones.
- **Pedido a WhatsApp:** Se automatizo la creación del mensaje de pedido. Al finalizar, la app genera un texto detallado y profesional listo para enviar al vendedor.
- **Feedback Visual:** Se agrego notificaciones (Toasts) para que sepas exactamente cuándo agregaste algo al carrito.

### Diseño y UX
- **Mobile First:** Se diseño pensando primero en el celular. Agregué pistas visuales para el scroll horizontal en las categorías para que sea más fácil navegar.
- **Badge Flotante:** Siempre se mantiene visible cuántos items llevas seleccionados.
- **Accesibilidad:** Se mejoro la navegación por teclado y las etiquetas para que la web sea más inclusiva.

## El Stack Tecnológico

Para este proyecto se eligio las herramientas más actuales para asegurar rendimiento y escalabilidad:

- **Framework:** [Next.js 16.0.10](https://nextjs.org/) (Usando App Router para mejor estructura).
- **Librería:** [React 19.2.1](https://react.dev/) (Aprovechando los últimos Hooks).
- **Estilos:** [Tailwind CSS 4](https://tailwindcss.com/) (Para mantener el CSS limpio y mantenible).
- **Calidad de Código:** ESLint v9.

## ¿Qué vas a encontrar en el catálogo?

Se organizo los productos en secciones claras para facilitar la búsqueda:
- **Chicas:** Desde Jeans y Faldas hasta Casacas.
- **Niñas:** Poleras y Conjuntos completos.
- **Deportiva:** Ropa cómoda para entrenar.
- **Novedades y Moda:** Accesorios, peluches, maquillaje y perfumes.

## Cómo correr el proyecto en tu local

Si quieres probar el código en tu máquina o colaborar, sigue estos pasos sencillos:

1. **Clona el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/cherry-bomb.git](https://github.com/tu-usuario/cherry-bomb.git)
   cd cherry-bomb
2. **Instala las dependencias:**
   ```bash
   npm install
3. **Levanta el servidor de desarrollo:**
   ```bash
   npm run dev
5. ¡Listo! Abre tu navegador y entra a http://localhost:3000 para verlo en acción.

#### **Nota:** Recuerda cambiar donde dice `tu-usuario` y `TU_USUARIO_GITHUB` por tu nombre de usuario real de GitHub para que los comandos de clonar y las estadísticas funcionen de verdad.
---
Hecho con mucho código y café ☕ por Diego Avalos. 
