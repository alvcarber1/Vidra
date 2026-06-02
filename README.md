# Vidra

Consultoría especializada en Inteligencia Artificial diseñada para transformar información de negocio en sistemas operativos y resultados medibles.

## 🚀 Estructura del Proyecto

Este repositorio contiene tanto la plataforma web como las herramientas de soporte:

- **/web**: Aplicación frontend construida con [Astro](https://astro.build/) y TypeScript.
- **/.venv**: Entorno virtual de Python para procesos de análisis y ciencia de datos.

## 🛠️ Desarrollo del Frontend

Toda la lógica de la web se encuentra en la carpeta `web`. Para comenzar:

```sh
cd web
npm install
npm run dev
```

### Comandos principales (dentro de /web)

| Comando | Acción |
| :--- | :--- |
| `npm run dev` | Inicia el servidor local en `localhost:4321`. |
| `npm run build` | Genera el sitio estático optimizado en `./dist/`. |
| `npm run preview` | Previsualiza la versión de producción localmente. |
| `npm run astro check` | Ejecuta diagnósticos de TypeScript y Astro. |

## 🧠 Áreas de Especialización

La web refleja nuestros tres pilares de servicio:
1. **Análisis:** Auditoría y organización de datos con IA.
2. **Machine Learning:** Modelos predictivos para decisiones operativas.
3. **Deep Learning:** IA avanzada para datos complejos (NLP, imágenes).

## 🌍 Multi-idioma

El contenido es dinámico y soporta **Español (ES)** e **Inglés (EN)**. Todas las traducciones y textos se gestionan centralizadamente en:
`web/src/lib/siteContent.ts`
