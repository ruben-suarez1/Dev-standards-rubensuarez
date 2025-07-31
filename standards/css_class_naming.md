# Naming de Clases CSS en VTEX

### 🎯 Estructura recomendada

component--element__modifier


> Sigue el patrón VTEX CSS Handles y/o BEM si es código custom.

**Ejemplo VTEX handle:**
```css
.product-card__badge--highlighted

Ejemplo custom:

.filters__dropdown--open

🧩 Buenas prácticas
Prefiere semántica visual: banner, wrapper, image, label.

Evita clases tipo .style1, .boxRed, .divxx.

Usa --modifier para variantes.


---

## ✅ 4. `commit_message_guidelines.md`

```md
# Guía para Mensajes de Commit

### 📌 Convención: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

### 🔧 Formato base

<type>: <mensaje corto en infinitivo>


### 🧰 Tipos comunes

- `feat:` nueva funcionalidad
- `fix:` corrección de bug
- `chore:` tareas no funcionales (config, build)
- `refactor:` cambios internos sin modificar comportamiento
- `docs:` documentación
- `style:` cambios de estilo (espacios, sangrías, etc)
- `test:` pruebas

### ✅ Ejemplos

feat: agregar imágenes al menú de marcas mobile
fix: corregir ordenamiento alfabético en PLP
refactor: extraer lógica de filtros a nuevo hook


---

## ✅ 5. `branch_naming_convention.md`

```md
# Convención de nombres para ramas

### 📍 Formato

<tipo>/<id-tarea>-<descripcion-corta>


### Tipos

- `feature/`
- `bugfix/`
- `hotfix/`
- `chore/`
- `refactor/`

### ✅ Ejemplos

feature/123-agregar-popup-guia-tallas
bugfix/321-fix-badges-pdp-mobile
refactor/101-reorganizar-componentes-home


> Usa siempre el ID de tarea si usas Jira/Basecamp/Asana.

