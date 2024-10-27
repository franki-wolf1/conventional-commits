# Convención de Commits

Esta guía de convención de commits sigue el estándar de *Conventional Commits*, una estructura que facilita la claridad y el seguimiento de cambios en proyectos colaborativos. La convención proporciona un formato para tus mensajes de commit, permitiendo una mayor consistencia, facilidad de generación de versiones y un historial de cambios claro.

---

## Estructura del Commit

Un mensaje de commit debería tener la siguiente estructura:


---

## Tipos de Commits

A continuación se muestran los principales tipos de commits, su uso y algunos ejemplos.

### 1. `feat` - Nueva Funcionalidad

Este tipo se usa cuando introduces una nueva funcionalidad al proyecto.

**Ejemplos:**
- `feat(user): add user profile section`
- `feat(auth): implement login and logout functionality`
- `feat(dashboard): add real-time data visualization`

### 2. `fix` - Corrección de Errores

Usado cuando corriges un bug o error en el código.

**Ejemplos:**
- `fix(api): correct response status code for error handling`
- `fix(route): resolve issue with incorrect route parameters`
- `fix(nav): correct broken link in header navigation`

### 3. `chore` - Mantenimiento General

Este tipo se utiliza para tareas de mantenimiento que no afectan la lógica del código.

**Ejemplos:**
- `chore(deps): update dependencies to latest versions`
- `chore(lint): fix linting errors in code`
- `chore(env): update environment variables for production`

### 4. `docs` - Cambios en la Documentación

Se usa cuando actualizas o agregas documentación sin modificar el código funcional.

**Ejemplos:**
- `docs(readme): update installation instructions`
- `docs(api): add missing API endpoint documentation`
- `docs(contributing): clarify contributing guidelines`

### 5. `style` - Cambios de Estilo

Este tipo se usa para modificaciones de formato o estilo que no afectan el funcionamiento del código.

**Ejemplos:**
- `style(header): apply consistent spacing in header component`
- `style(button): fix button alignment issues`
- `style(css): standardize CSS variables across files`

### 6. `refactor` - Reestructuración de Código

Indica cambios en la estructura del código sin alterar la funcionalidad.

**Ejemplos:**
- `refactor(auth): simplify auth module and remove redundant code`
- `refactor(api): modularize API calls`
- `refactor(utils): use helper functions for error handling`

### 7. `perf` - Optimización de Rendimiento

Se utiliza para cambios que mejoran el rendimiento.

**Ejemplos:**
- `perf(cache): improve data caching for faster response times`
- `perf(image): compress images for faster loading`
- `perf(query): optimize database query for performance`

### 8. `test` - Agregar o Mejorar Pruebas

Usado cuando añades o mejoras pruebas unitarias o de integración.

**Ejemplos:**
- `test(auth): add tests for login functionality`
- `test(api): cover error scenarios in API tests`
- `test(utils): increase coverage for utility functions`

### 9. `build` - Cambios en el Sistema de Build

Para cambios en la configuración de compilación o dependencias externas.

**Ejemplos:**
- `build(deps): update webpack to version 5`
- `build(config): add minification to production builds`
- `build(ci): configure Docker for deployment`

### 10. `ci` - Configuración de CI/CD

Indica modificaciones en archivos de configuración de Integración y Entrega Continua.

**Ejemplos:**
- `ci(workflow): update GitHub Actions workflow for deployment`
- `ci(jenkins): add stage for testing`
- `ci(circleci): update config.yml for new branches`

### 11. `revert` - Revertir Cambios

Para revertir un commit anterior.

**Ejemplos:**
- `revert: undo previous commit affecting the API endpoints`
- `revert: revert "feat(auth): implement login functionality"`

---

## Notas Adicionales

- **Scope (Alcance)**: Este es opcional y describe qué parte del proyecto se está afectando. Úsalo cuando quieras especificar el módulo o componente afectado (por ejemplo, `auth`, `api`, `header`, etc.).
- **Descripción corta**: Debe ser clara y directa, en tiempo presente y en minúsculas.
- **Descripción adicional**: Si necesitas más detalles, agrega una línea en blanco debajo de la descripción corta y proporciona más contexto.

---

Siguiendo estas convenciones, los mensajes de commit serán claros, concisos y consistentes, ayudando a mantener la calidad del proyecto y facilitando la colaboración.
