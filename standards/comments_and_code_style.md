# Comentarios y Estilo de Código

### 📘 Comentarios

- Usa comentarios solo cuando la lógica no sea evidente.
- Prefiere comentarios `por qué` sobre `qué hace`.

❌ Mal ejemplo:
```js
// Hacer loop
for (...) {}

✅ Buen ejemplo:

// Se itera el array para evitar mutar el objeto original
for (...) {}

🧽 Código limpio
Usa const y let, evita var.

Declara solo lo necesario.

Nombra variables descriptivamente.

// ❌ Mal
let x = 0;

// ✅ Bien
let selectedIndex = 0;

