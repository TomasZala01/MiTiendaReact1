# Mi Tienda React 🛍️

Proyecto final de React desarrollado con **Vite** y desplegado en **GitHub Pages** por Tomas Zalazar.
La aplicación simula una tienda online con autenticación, carrito de compras y panel de administración de productos.

---

## 🚀 Tecnologías utilizadas
- [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- [React Router DOM](https://reactrouter.com/) para la navegación
- [React Toastify](https://fkhadra.github.io/react-toastify/) para notificaciones
- [Bootstrap](https://getbootstrap.com/) y estilos propios
- Context API para manejo de **auth**, **productos** y **carrito**

---

📖 Funcionalidades principales
Registro e inicio de sesión de usuarios

Carrito de compras con persistencia

Panel de administración para crear/editar productos

Rutas protegidas con ProtectedRoute

Manejo de estados globales con Context API

Notificaciones de acciones con Toastify

Se utiliza HashRouter para evitar errores 404 en GitHub Pages.

El archivo 404.html está configurado para redirigir a index.html en caso de rutas inválidas.

El archivo .env no debe subirse al repositorio (configurado en .gitignore).

Al refrescar la página, las rutas funcionan correctamente gracias al uso de HashRouter.

