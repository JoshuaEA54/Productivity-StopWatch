# ⏱️ Productivity StopWatch

Aplicación web desarrollada con **Next.js** y **TypeScript** que permite crear y administrar múltiples cronómetros de productividad personalizados. Cada temporizador tiene nombre, color, y funciones para iniciar, pausar, reiniciar y eliminar. Toda la información se guarda localmente con `localStorage`, permitiendo conservar el progreso entre recargas.

## 🚀 Funcionalidades

- Crear cronómetros personalizados con nombre y color aleatorio.
- Iniciar, pausar, reiniciar y eliminar cada cronómetro.
- Visualización del tiempo en formato legible (horas, minutos, segundos).
- Guardado automático en el `localStorage`.
- Gráficos visuales (circular y lineal) para mostrar distribución del tiempo.
- Actualización en tiempo real con un solo `setInterval` global (uso de `useRef`).
- Optimización con `useMemo` para cálculos pesados.

## 🛠️ Tecnologías y herramientas utilizadas

- **Next.js** con App Router
- **TypeScript**
- **React Hooks**: `useRef`, `useMemo`, `useEffect`, `useState`
- **Custom Hook**: `useLocalStorage`
- **Patrones de diseño**:
  - `Container-Presenter`
  - `Singleton` (para el intervalo global)

## 🔗 Enlaces importantes

- 🧠 Proyecto original en vivo: [Ver en Vercel](https://productivity-stopwatch-nextjs.vercel.app/)
- 🧑‍💻 Repositorio original: [GitHub](https://github.com/KendallSN/Productivity-Stopwatch-Nextjs)

## 👨‍🏫 Créditos

Basado en la guía desarrollada en el curso **Programación IV - UNA**, por los estudiantes:
- Angelo Marín Granados
- Joselyn Morales Román
- Kendall Salazar Navarro

Desarrollado y adaptado por Joshua Elizondo Abarca.
