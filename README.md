<div align="center">

# Talento sin Fronteras

### Guía de empleo, documentación y derechos laborales para extranjeros en España

[![Ver demo](https://img.shields.io/badge/Ver_demo-D4AF37?style=for-the-badge&logo=googlechrome&logoColor=black)](https://proyectotalentosinfronteras.github.io/talento_sin_fronteras/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)

</div>

<br>

## El problema

Llegar a España sin saber los pasos para tramitar la documentación, lo que implica navegar trámites dispersos entre distintas webs oficiales (NIE, TIE, Seguridad Social, homologación de títulos), sin una guía clara de qué hacer primero, cuáles son tus derechos laborales, o qué empresas realmente contratan talento internacional sin sesgos.

Talento sin Fronteras centraliza esa información en una única plataforma interactiva, con un itinerario lógico paso a paso y herramientas de IA para aplicar lo aprendido directamente al CV y a la búsqueda de empleo.

<br>

## Stack técnico

| Capa | Tecnología | Por qué |
|---|---|---|
| Estructura | HTML5 semántico | accesibilidad y SEO desde la base |
| Estilos | CSS3 (secciones a medida) | control total del diseño sin dependencias |
| Interactividad | JavaScript vanilla | navegación por pestañas, acordeones, módulos de IA |
| IA | Módulos conversacionales integrados | consultor de visados, generador de CV, simulador de entrevistas |
| Despliegue | GitHub Pages | hosting gratuito, sin backend necesario |

<br>

## Estructura del proyecto

```
talento_sin_fronteras/
├── index.html
├── css/
│   └── styles.css
├── js/
│   ├── navegacion.js
│   ├── consultor-ia.js       # chat del consultor de extranjería
│   ├── generador-cv.js       # formulario + preview del CV ATS
│   └── simulador-entrevistas.js
├── img/
└── docs/
    └── screenshots/
```

<br>

## Módulos principales

- **Guía paso a paso** — itinerario en 3 fases: regularización base (NIE, empadronamiento, Seguridad Social) → adaptación de CV a formato ATS → canales de búsqueda de empleo.
- **Documentación y regularización** — explicación interactiva (tabs/acordeón) de NIE/TIE, Seguridad Social y homologación de títulos, diferenciando profesiones reguladas y no reguladas.
- **Derechos laborales** — marco legal (Art. 14 CE, Estatuto de los Trabajadores, SMI) con enlaces directos a canales oficiales de denuncia (CEDRE, ITSS).
- **Directorio de empresas inclusivas** — más de 30 empresas en España filtrables por sector, con su certificación o política de diversidad concreta.
- **Herramientas con IA:**
  - *Consultor de extranjería* — resuelve dudas sobre arraigo, renovación de NIE/TIE y regularización.
  - *Generador de CV ATS* — toma los datos del usuario y devuelve una versión optimizada para sistemas de selección automatizados.
  - *Simulador de entrevistas* — practica preguntas por perfil profesional (Analista de Datos, Desarrollador Web, Administración) con evaluación de la respuesta.

<br>

## Cómo correrlo localmente

```bash
git clone https://github.com/proyectotalentosinfronteras/talento_sin_fronteras.git
cd talento_sin_fronteras
# al ser HTML/CSS/JS estático, basta con abrir index.html
# o servirlo con un servidor local, por ejemplo:
npx serve .
```

<br>

## Despliegue

El sitio se sirve directamente desde la rama principal vía GitHub Pages (Settings → Pages → rama `main` / carpeta raíz).

<br>

## Demo en vivo

🔗 [proyectotalentosinfronteras.github.io/talento_sin_fronteras](https://proyectotalentosinfronteras.github.io/talento_sin_fronteras/)

<br>

---

<div align="center">

Proyecto desarrollado y mantenido por **Camila Rabelo de Amorim** · [LinkedIn](https://linkedin.com/in/camilarabeloamorim)

*Información orientativa de libre acceso. No sustituye asesoría legal profesional.*

</div>
