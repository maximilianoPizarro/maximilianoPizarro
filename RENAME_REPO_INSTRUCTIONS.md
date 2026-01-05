# 📝 Instrucciones para Publicar en la Ruta Raíz `/`

Para que tu sitio esté disponible en `https://maximilianopizarro.github.io/` (en lugar de `/maximilianoPizarro/`), necesitas renombrar tu repositorio.

## ✅ Pasos para Renombrar el Repositorio

### 1. Renombrar en GitHub

1. Ve a tu repositorio en GitHub
2. Click en **Settings** (Configuración)
3. Scroll hasta **Repository name** (Nombre del repositorio)
4. Cambia el nombre a: **`maximilianoPizarro.github.io`**
   - ⚠️ **IMPORTANTE**: Debe ser exactamente `TU-USUARIO.github.io`
5. Click en **Rename**

### 2. Actualizar la Configuración Local

Después de renombrar, actualiza `docs/_config.yml`:

```yaml
baseurl: ""  # Cambiar de "/maximilianoPizarro" a ""
url: "https://maximilianopizarro.github.io"
```

### 3. Actualizar el Remote de Git

```bash
# Ver el remote actual
git remote -v

# Actualizar la URL del remote
git remote set-url origin https://github.com/maximilianopizarro/maximilianoPizarro.github.io.git

# Verificar
git remote -v
```

### 4. Hacer Push de los Cambios

```bash
git add docs/_config.yml
git commit -m "Update baseurl for root domain"
git push origin main
```

### 5. Configurar GitHub Pages

1. Ve a **Settings** → **Pages**
2. En **Source**, selecciona:
   - Branch: `main`
   - Folder: `/docs`
3. Click en **Save**

### 6. Esperar y Verificar

- Espera 5-10 minutos
- El sitio estará disponible en: `https://maximilianopizarro.github.io/`

## ⚠️ Notas Importantes

- **El nombre del repositorio DEBE ser exactamente**: `maximilianoPizarro.github.io`
- GitHub Pages solo sirve desde la raíz si el repo se llama `username.github.io`
- Después de renombrar, GitHub redirigirá automáticamente las URLs antiguas

## 🔄 Si No Puedes Renombrar el Repositorio

Si por alguna razón no puedes renombrar el repositorio, el sitio seguirá funcionando en:
`https://maximilianopizarro.github.io/maximilianoPizarro/`

Y la configuración actual con `baseurl: "/maximilianoPizarro"` es correcta.

