# AsistenciaEdu 📋

Sistema de control de asistencia escolar con roles de Administrador y Docente.

## 🚀 Cómo publicar en Vercel (gratis)

### Opción A — Desde GitHub (recomendado)
1. Crea cuenta gratuita en https://github.com
2. Crea un repositorio nuevo llamado `asistencia-edu`
3. Sube todos estos archivos al repositorio
4. Ve a https://vercel.com y crea cuenta gratuita (puedes entrar con GitHub)
5. Haz clic en "Add New Project" → selecciona tu repositorio
6. Haz clic en "Deploy" — ¡listo! Vercel detecta Vite automáticamente
7. Te dará un link tipo: https://asistencia-edu.vercel.app

### Opción B — Vercel CLI
```bash
npm install -g vercel
npm install
vercel
```

## 📱 Instalar en el celular (PWA)
1. Abre el link de Vercel en Chrome (Android) o Safari (iPhone)
2. Android: menú ⋮ → "Agregar a pantalla de inicio"
3. iPhone: botón compartir □↑ → "Añadir a pantalla de inicio"
4. ¡Ya aparece como app en tu celular!

## 🔑 Cuentas de acceso demo
- **Admin:** admin@colegio.cl / admin123
- **Docente:** mgonzalez@colegio.cl / prof123
- **Docente:** cramirez@colegio.cl / prof123

## 📊 Importar estudiantes desde Excel
El archivo Excel debe tener estas columnas exactas:
| Nombre | RUT/ID | Curso |
|--------|--------|-------|
| Juan Pérez | 11.111.111-1 | 1A |

Descarga la plantilla desde el panel de Administrador → Estudiantes.

## 🛠 Desarrollo local
```bash
npm install
npm run dev
```
