# poo-python-curso

# 🐍 Curso de Programación Orientada a Objetos en Python

Bienvenido al repositorio del curso de **Programación Orientada a Objetos (POO) con Python**.

Este curso está diseñado para trabajar usando **GitHub Codespaces**, sin necesidad de instalar nada en tu computador.

---

# 🚨 Paso obligatorio: hacer un Fork

Antes de comenzar:

En GitHub:

1. Haz clic en el botón **Fork** (arriba a la derecha)
2. Se creará una copia en tu cuenta

👉 A partir de ahora trabajarás en **tu propio repositorio**

---

# 🚀 Cómo empezar

## 1. Crear tu entorno

En tu repositorio (el fork):

1. Haz clic en **Code**
2. Ve a la pestaña **Codespaces**
3. Haz clic en **Create codespace**

⏳ La primera vez puede tardar unos minutos.

---

## 2. Entorno listo automáticamente

El entorno incluye:

* Python 3.12
* Jupyter Notebook
* Librerías necesarias (`numpy`, `pandas`, `matplotlib`)

No necesitas instalar nada manualmente.

---

# 📁 Estructura del repositorio

```id="q4p9tw"
.
├── src/                     # Código del profesor (NO modificar)
├── notebooks/               # Notebooks de clase (NO modificar)
├── ejercicios/
│   ├── enunciados/          # Problemas propuestos (NO modificar)
│   └── soluciones_estudiante/  # TU TRABAJO
├── requirements.txt
└── .devcontainer/
```

---

# ⚠️ Reglas importantes

🔴 **NO modifiques:**

* `src/`
* `notebooks/`
* `ejercicios/enunciados/`

🟢 **Trabaja únicamente en:**

```id="v5htj9"
ejercicios/soluciones_estudiante/
```

---

# 🔄 Actualizar el contenido del curso

Debes conectar tu repositorio con el del profesor (esto se hace una sola vez).

## 1. Agregar repositorio del profesor

```bash id="3g7j9k"
git remote add upstream https://github.com/arleyfernandotorresgalindo/poo-python-curso.git
```

---

## 2. Traer actualizaciones

```bash id="9p0c6w"
git fetch upstream (Traer lo del profe).
git rebase upstream/main (Ponerme al día).
git push origin main --force (Subir mi versión limpia).
```

👉 Esto actualiza tu repositorio con los cambios del profesor

---

# 📓 Uso de Jupyter

1. Ve a la carpeta `notebooks/`
2. Abre un archivo `.ipynb`
3. Selecciona el kernel:

   ```
   Python 3.12
   ```

---

# 📌 Flujo de trabajo recomendado

1. Revisa el material en `notebooks/`
2. Lee los ejercicios en `ejercicios/enunciados/`
3. Resuelve en:

```id="z1sh3z"
ejercicios/soluciones_estudiante/
```

---

# 🛠️ Guardar tu trabajo

```bash id="u8t9dr"
git add .
git commit -m "Solución ejercicio 1"
git push
```

---

# ❓ Problemas comunes

### No carga Jupyter

```bash id="7m6l5k"
pip install ipykernel
```

### No aparecen cambios del profesor

```bash id="u0k2rp"
git pull upstream main
```

---

# 🎯 Objetivo del repositorio

Este entorno está diseñado para:

✅ evitar problemas de instalación
✅ trabajar con un entorno unificado
✅ enfocarse en aprender programación

---

## 👨‍🏫 Autor

Curso diseñado por el profesor que siempre cree en usted: Arley Fernando Torres Galindo.

---

¡Éxitos en el curso! 🚀
