# Introducción a GitHub: Publica tu Primer Proyecto Académico

**Autor:** Alberto Permuy Leal — Director Técnico, //Codery_  
**Organización:** ECOBAS — Economics and Business Administration for Society  
**Evento:** Workshop · 25 Marzo 2026  
**Contacto:** apermuy@codery.es · www.codery.es

---

## Descripción

Este repositorio contiene los materiales del workshop *"Introducción a GitHub: Publica tu Primer Proyecto Académico"*, organizado por ECOBAS para Personal Docente e Investigador (PDI) de UDC, UVigo y USC.

El taller introduce el uso de git y GitHub como herramientas de gestión de versiones y publicación de proyectos académicos, con especial atención a la reproducibilidad de la investigación en economía y administración de empresas.

---

## Contenidos del taller

- Qué es un sistema de control de versiones y por qué es importante
- Diferencia entre git y GitHub
- Fundamentos de git: repositorios, ramas, estados y commits
- Introducción a GitHub.com y GitHub Desktop
- Consejos para la publicación de proyectos académicos
- Aspectos legales: licencias, propiedad intelectual y RGPD
- Buenas prácticas con datos: documentación y reproducibilidad
- Seguridad: qué no debe subirse a un repositorio

---

## Toolkit utilizado

| Herramienta | Función | Enlace |
|-------------|---------|--------|
| GitHub | Plataforma de alojamiento de repositorios | https://github.com |
| GitHub Desktop | Cliente visual para gestionar repositorios | https://desktop.github.com |
| Visual Studio Code | Editor de código y ficheros Markdown | https://code.visualstudio.com |

---

## Flujo de trabajo básico

```
Editas archivo  →  git add (staged)  →  git commit  →  git push
   (modified)                           (local)        (remoto)
                                          ← git pull ←
```

---

## Cómo empezar con tu primer repositorio

1. Crear cuenta en GitHub.com
2. Instalar GitHub Desktop
3. Identificar los ficheros y documentos de tu proyecto
4. Crear un repositorio nuevo desde GitHub Desktop
5. Añadir los ficheros al repositorio
6. Hacer el primer commit con un mensaje descriptivo
7. Publicar el repositorio con Push

---

## Consejos para proyectos académicos

### Legales
- Identifica claramente la autoría del proyecto
- Elige una licencia adecuada:
  - Código: MIT, GPL, Apache
  - Datos y documentos: CC-BY, CC-SA
- Cumple el RGPD: anonimiza los datos y justifica su uso

### Datos
- Documenta el dataset: descripción, fuente, fecha y metodología
- Incluye los pasos necesarios para regenerar los datos o el análisis
- Versiona los datasets y declara las dependencias de software

### Seguridad
- Nunca incluyas en el repositorio: emails, API keys, contraseñas ni datos personales
- Utiliza un sistema de configuración externo para las credenciales

---

## Recursos adicionales (Bonus)

| Recurso | Descripción |
|---------|-------------|
| [Markdown para GitHub](https://docs.github.com/es/get-started/writing-on-github) | Guía oficial de formato Markdown en GitHub |
| [GitHub Pages](https://pages.github.com) | Publica tu repositorio como sitio web gratuito |
| [Zenodo + GitHub](https://zenodo.org) | Asigna un DOI citable a tu repositorio |
| [GitHub Classroom](https://classroom.github.com) | Gestiona entregas de estudiantes como repositorios |

---

## Licencia

El contenido de este repositorio se publica bajo licencia [Creative Commons CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).  
Puedes reutilizar y adaptar los materiales citando la fuente.

---

*README generado como ejemplo para el workshop. Basado en los contenidos de la presentación ECOBAS Git · Marzo 2026.*