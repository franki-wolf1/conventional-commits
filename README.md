# 📄 Convención de Commits

Esta guía sigue el estándar de *Conventional Commits*, una convención ampliamente adoptada para estructurar y estandarizar los mensajes de commits en proyectos. Facilita la organización del historial de commits, el seguimiento de cambios y la generación de versiones.

---

## 📑 Estructura del Commit

Cada mensaje de commit debe seguir la estructura:


### Ejemplo General:


---

## 📋 Tipos de Commits

A continuación se presentan los tipos principales de commits, su uso y ejemplos de cada uno.

### 1. `feat` - Nueva Funcionalidad

Este tipo se usa cuando introduces una nueva característica o funcionalidad en el proyecto.

**Ejemplos:**
- `feat(user): add user profile section`
- `feat(auth): implement login and logout functionality`
- `feat(dashboard): add real-time data visualization`

### 2. `fix` - Corrección de Errores

Se usa cuando solucionas un bug o error en el código.

**Ejemplos:**
- `fix(api): correct response status code for error handling`
- `fix(route): resolve issue with incorrect route parameters`
- `fix(nav): correct broken link in header navigation`

### 3. `chore` - Mantenimiento General

Este tipo es para cambios menores de mantenimiento, que no afectan el código o la funcionalidad.

**Ejemplos:**
- `chore(deps): update dependencies to latest versions`
- `chore(lint): fix linting errors in code`
- `chore(env): update environment variables for production`

### 4. `docs` - Documentación

Se usa cuando agregas o modificas la documentación sin afectar el código funcional.

**Ejemplos:**
- `docs(readme): update installation instructions`
- `docs(api): add missing API endpoint documentation`
- `docs(contributing): clarify contributing guidelines`

### 5. `style` - Cambios de Estilo

Se usa para cambios de formato o estilo que no alteran la funcionalidad del código (ej. formato, espacios, comas).

**Ejemplos:**
- `style(header): apply consistent spacing in header component`
- `style(button): fix button alignment issues`
- `style(css): standardize CSS variables across files`

### 6. `refactor` - Reestructuración de Código

Para cambios en la estructura del código que no modifican la funcionalidad.

**Ejemplos:**
- `refactor(auth): simplify auth module and remove redundant code`
- `refactor(api): modularize API calls`
- `refactor(utils): use helper functions for error handling`

### 7. `perf` - Optimización de Rendimiento

Para cambios que mejoran el rendimiento del sistema.

**Ejemplos:**
- `perf(cache): improve data caching for faster response times`
- `perf(image): compress images for faster loading`
- `perf(query): optimize database query for performance`

### 8. `test` - Agregar o Mejorar Pruebas

Se usa para agregar, actualizar o mejorar pruebas.

**Ejemplos:**
- `test(auth): add tests for login functionality`
- `test(api): cover error scenarios in API tests`
- `test(utils): increase coverage for utility functions`

### 9. `build` - Configuración de Compilación

Para cambios en el sistema de build o dependencias externas.

**Ejemplos:**
- `build(deps): update webpack to version 5`
- `build(config): add minification to production builds`
- `build(ci): configure Docker for deployment`

### 10. `ci` - Integración y Entrega Continua

Se usa para cambios en la configuración de Integración y Entrega Continua (CI/CD).

**Ejemplos:**
- `ci(workflow): update GitHub Actions workflow for deployment`
- `ci(jenkins): add stage for testing`
- `ci(circleci): update config.yml for new branches`

### 11. `revert` - Revertir Cambios

Este tipo se usa para deshacer un commit previo.

**Ejemplos:**
- `revert: undo previous commit affecting the API endpoints`
- `revert: revert "feat(auth): implement login functionality"`

### 12. `merge` - Fusionar Cambios

Usado para mensajes de commits automáticos al fusionar ramas.

**Ejemplos:**
- `merge: branch 'feature/auth' into main`
- `merge: resolve conflicts in 'dashboard'`

### 13. `hotfix` - Corrección Urgente en Producción

Se usa para corregir rápidamente un error en producción.

**Ejemplos:**
- `hotfix(auth): fix login button crash`
- `hotfix(payment): resolve payment processing issue`

### 14. `env` - Cambios en Entornos de Ejecución

Usado para cambios en los entornos (dev, staging, production).

**Ejemplos:**
- `env(staging): update API URL for staging environment`
- `env(production): set environment variables for live environment`

---

## ✍️ Notas Adicionales

- **Scope (Alcance)**: Este es opcional y describe qué parte del proyecto se está afectando. Úsalo para especificar el módulo o componente afectado (ej. `auth`, `api`, `header`).
- **Descripción corta**: Debe ser clara y directa, en tiempo presente y en minúsculas.
- **Descripción adicional**: Si necesitas más detalles, agrega una línea en blanco debajo de la descripción corta y proporciona más contexto.

---

## 🚀 Ventajas de Usar esta Convención

- **Claridad**: Los mensajes de commit son claros y uniformes.
- **Rastreo de cambios**: Facilita identificar qué tipo de cambios se realizaron.
- **Generación automática de versiones**: La convención permite automatizar el versionado semántico.
- **Mejor colaboración**: Los colaboradores entienden rápidamente los cambios realizados.

Siguiendo estas convenciones, los mensajes de commit serán claros, concisos y consistentes, ayudando a mantener la calidad del proyecto y facilitando la colaboración.

--- 

¡Empieza a utilizar la convención de commits y lleva tu proyecto al siguiente nivel! 🚀
