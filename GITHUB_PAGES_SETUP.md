# 🔧 Configuración de GitHub Pages - Solución al Error 404

Si estás viendo un error 404 en `https://maximilianopizarro.github.io/`, sigue estos pasos:

## ✅ Pasos para Solucionar el 404

### Opción 1: Configurar GitHub Pages desde la Interfaz Web (Recomendado)

1. **Ve a tu repositorio en GitHub**: `https://github.com/maximilianopizarro/maximilianopizarro.github.io` (o el nombre de tu repo)

2. **Ve a Settings** (Configuración) → **Pages** (en el menú lateral izquierdo)

3. **En "Source" (Fuente)**:
   - Selecciona: **Deploy from a branch** (Desplegar desde una rama)
   - Branch: Selecciona `main` (o `master` si es tu rama principal)
   - Folder: Selecciona `/docs`
   - Click en **Save**

4. **Espera 5-10 minutos** para que GitHub Pages construya el sitio

5. **Verifica** que el sitio esté disponible en: `https://maximilianopizarro.github.io/`

### Opción 2: Usar GitHub Actions (Automático)

Si ya creaste el workflow `.github/workflows/pages.yml`, GitHub Actions construirá automáticamente el sitio.

1. **Ve a la pestaña "Actions"** en tu repositorio
2. Verifica que el workflow se ejecute después de hacer push
3. Si hay errores, revisa los logs

### Verificar la Configuración

1. **Nombre del repositorio**: 
   - Debe ser exactamente: `maximilianopizarro.github.io` (con tu nombre de usuario)
   - Si el repo tiene otro nombre, GitHub Pages no funcionará en la URL principal

2. **Estructura de archivos**:
   ```
   maximilianopizarro.github.io/
   ├── docs/
   │   ├── _config.yml
   │   ├── index.md
   │   ├── _layouts/
   │   ├── _includes/
   │   └── assets/
   └── README.md
   ```

3. **Archivos importantes**:
   - ✅ `docs/_config.yml` existe
   - ✅ `docs/index.md` existe
   - ✅ `docs/Gemfile` existe
   - ✅ `.github/workflows/pages.yml` existe (para GitHub Actions)

## 🔍 Troubleshooting

### El sitio sigue dando 404 después de 10 minutos:

1. **Verifica el nombre del repositorio**:
   ```bash
   # El repo debe llamarse exactamente:
   maximilianopizarro.github.io
   ```

2. **Verifica la configuración de Pages**:
   - Settings → Pages → Source debe estar en `/docs`

3. **Revisa los logs de GitHub Actions**:
   - Ve a la pestaña "Actions"
   - Revisa si hay errores en el build

4. **Verifica que los archivos estén en la rama correcta**:
   ```bash
   git branch  # Debe estar en main o master
   git status  # Verifica que los archivos estén commiteados
   ```

### Si el repositorio tiene otro nombre:

Si tu repositorio NO se llama `maximilianopizarro.github.io`, entonces:

1. **Opción A**: Renombra el repositorio a `maximilianopizarro.github.io`
2. **Opción B**: El sitio estará en: `https://maximilianopizarro.github.io/NOMBRE-DEL-REPO/`
   - En este caso, actualiza `baseurl` en `docs/_config.yml`:
     ```yaml
     baseurl: "/NOMBRE-DEL-REPO"
     ```

## 📝 Comandos Útiles

```bash
# Verificar que los archivos estén en el repo
git status

# Agregar todos los archivos
git add .

# Commit
git commit -m "Setup GitHub Pages with Jekyll"

# Push
git push origin main
```

## 🎯 Verificación Final

Después de configurar, verifica:

- [ ] Settings → Pages → Source está en `/docs`
- [ ] El workflow de GitHub Actions se ejecuta sin errores
- [ ] Esperaste al menos 5-10 minutos
- [ ] El repositorio se llama `maximilianopizarro.github.io`

Si todo está correcto, el sitio debería estar disponible en:
**https://maximilianopizarro.github.io/**

---

**Nota**: Si después de seguir estos pasos el sitio sigue sin funcionar, comparte:
1. El nombre exacto de tu repositorio
2. Una captura de pantalla de Settings → Pages
3. Los logs de GitHub Actions (si hay errores)

