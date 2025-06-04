
# 🧮 Cotizador de Préstamos en React

Este es un proyecto simple de **cotizador de préstamos** desarrollado con **React.js**, ideal como práctica o punto de partida para aplicaciones financieras o formularios interactivos.

## 🚀 Características

- Cálculo de cuotas mensuales basado en monto, plazo e interés.
- Formulario interactivo con validación.
- Actualización en tiempo real del resultado.
- Interfaz responsive y fácil de usar.
- Código modular y fácil de entender.

## 🖥️ Demo

Puedes ver una versión en vivo (si está disponible):

👉 [Ver demo](https://cotizador-react-dev.netlify.app)

## 📦 Instalación

Clona este repositorio y ejecuta el siguiente comando:

```bash
git clone https://github.com/carluis-berrocal/cotizador-prestamos-react.git
cd cotizador-prestamos-react
npm install
npm run dev
```

> Asegúrate de tener instalado [Node.js](https://nodejs.org/) y [Vite](https://vitejs.dev/) (opcional si usas `npm create vite@latest`).

## 🧠 Cómo funciona

El cotizador utiliza una fórmula simple para calcular la cuota:

```
cuota = (monto * tasa) / (1 - (1 + tasa)^-plazo)
```

Donde:
- `monto` = total solicitado
- `tasa` = interés mensual
- `plazo` = número de meses

## 🧾 Estructura del Proyecto

```
📁 src
├── 📂 components
│   ├── Formulario.jsx
│   ├── Resultado.jsx
│   └── ...
├── App.jsx
└── main.jsx
```

## 🛠️ Tecnologías

- React
- Vite
- CSS / Tailwind (o estilo propio)
- JavaScript moderno (ES6+)

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Puedes usarlo y modificarlo libremente.

---

### ✨ Autor

Desarrollado por **Carluis Berrocal Diaz**  

---

¡Si te fue útil, no olvides dejar una ⭐ en el repo!
