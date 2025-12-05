# 📖 GUÍA: Cómo Publicar SegurSenior en GitHub Pages

## Paso 1: Crear Cuenta en GitHub
1. Ve a [github.com](https://github.com)
2. Click en "Sign up" (Registrarse)
3. Completa: correo, contraseña, nombre de usuario
4. Verifica tu correo
5. ¡Listo!

## Paso 2: Instalar Git en tu PC
1. Ve a [git-scm.com](https://git-scm.com)
2. Descarga la versión para Windows
3. Instala con las opciones por defecto
4. Abre PowerShell y verifica:
```powershell
git --version
```

## Paso 3: Crear Repositorio en GitHub
1. Inicia sesión en GitHub
2. Click en el `+` arriba a la derecha → "New repository"
3. Nombre: `segurseni or` (sin espacios)
4. Descripción: "Aplicación educativa para seguridad emocional"
5. Selecciona: Public
6. **NO** marques "Initialize with README" (ya tenemos uno)
7. Click "Create repository"

## Paso 4: Preparar tu Carpeta Local
1. Abre PowerShell
2. Navega a tu carpeta:
```powershell
cd "c:\Users\JHAIR\Desktop\html-01\hhh"
```

3. Configura Git con tu nombre y email:
```powershell
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

## Paso 5: Inicializar Git Localmente
```powershell
git init
git add .
git commit -m "Primer commit: SegurSenior app"
```

## Paso 6: Conectar con GitHub
En GitHub, después de crear el repositorio, copia el comando que dice "push an existing repository from the command line". Será algo como:

```powershell
git remote add origin https://github.com/TU_USUARIO/segurseni or.git
git branch -M main
git push -u origin main
```

Pega esto en PowerShell (reemplaza `TU_USUARIO` con tu usuario de GitHub)

## Paso 7: Habilitar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Click en "Settings" (Configuración)
3. En el menú izquierdo, busca "Pages"
4. En "Source", selecciona: "Deploy from a branch"
5. En "Branch", selecciona: "main" y "/root"
6. Click "Save"
7. Espera 1-2 minutos

## Paso 8: ¡Tu App está Lista!
GitHub te mostrará la URL en la sección Pages:
```
https://tu-usuario.github.io/segurseni or
```

**Copia este link y compártelo con quien quieras** ✅

---

## 🔄 Hacer Cambios Después

Si quieres actualizar tu app:

```powershell
cd "c:\Users\JHAIR\Desktop\html-01\hhh"
git add .
git commit -m "Descripción de los cambios"
git push
```

---

## 📱 Acceso Desde Móvil

Los amigos pueden abrir el link en cualquier navegador (Chrome, Safari, etc.) desde:
- 📱 Celular
- 💻 Computadora
- 📲 Tablet

¡No necesitan instalar nada!

---

## ❓ Problemas Comunes

**Problema:** "fatal: Authentication failed"
**Solución:** GitHub te pedirá autenticación. Usa tu token en lugar de contraseña:
1. Ve a GitHub → Settings → Developer settings → Personal access tokens
2. Genera un nuevo token
3. Usa ese token como "contraseña"

**Problema:** "No tienes permisos"
**Solución:** Asegúrate de que el repositorio es tuyo y estés logueado en git

---

## ✨ ¡Listo!

Tu app SegurSenior está en línea y lista para compartir con el mundo.

**Ejemplo de URL:** `https://jhair.github.io/segurseni or`

Comparte el link con amigos y familiares. ¡Que disfruten! 🎉
