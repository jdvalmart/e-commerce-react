# 🛒 React E-Commerce Store

Este es un proyecto de aprendizaje de una tienda virtual, desarrollado con **React** y **Vite**. El objetivo principal fue practicar la arquitectura de componentes y la gestión de estado global.

## 🔗 Demo en Vivo
🚀 **[e-commerce](https://eccommercevalmart.netlify.app/)**

---

## 📂 Estructura del Proyecto

Basado en la organización actual del repositorio:

* **`Pages/`**: Contiene las vistas principales (Home, Checkout, Detalles).
* **`components/`**: Piezas de UI reutilizables como la Navbar y las Cards de productos.
* **`context/`**: Manejo de estado global con **Context API** (carrito, filtros y búsqueda).
* **`main.jsx`**: Punto de entrada de la aplicación.
* **`index.css`**: Estilos globales.

## ✨ Características
* **Filtrado por categorías**: Organización dinámica de productos.
* **Carrito de Compras**: Gestión de productos mediante estado global.
* **Responsive Design**: Interfaz adaptada a dispositivos móviles.
* **Vite Speed**: Configurado con Vite para un desarrollo y build ultra rápidos.

## 🛠️ Tecnologías Utilizadas
* **React.js**
* **Vite**
* **Tailwind CSS / CSS Modules** (según lo que estés usando)
* **React Context API**

## 🚀 Instalación y Uso Local

1.  **Clona este repositorio:**
    ```bash
    git clone [https://github.com/jdvalmart/e-commerce-react.git](git@github.com:jdvalmart/e-commerce-react.git)
    ```
2.  **Instala las dependencias:**
    ```bash
    npm install
    ```
3.  **Inicia el servidor de desarrollo:**
    ```bash
    npm run dev
    ```

---

## 🧠 Aprendizajes Clave
Durante el desarrollo de este proyecto, profundicé en:
1.  El uso de **Context API** para evitar el *prop drilling* en el carrito de compras.
2.  La creación de rutas dinámicas y lógica de filtrado.
3.  Despliegue continuo (CI/CD) utilizando **Netlify**.

---
Hecho por [Juan David Valencia]