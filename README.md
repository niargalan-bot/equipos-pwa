# ⚽ Armar Equipos Parejos – PWA

Aplicación web progresiva (PWA) para armar equipos balanceados entre amigos.  
Funciona en cualquier navegador moderno y se puede **instalar como app en el celular**.

## 🚀 Demo
👉 [Abrir la app](https://TU_USUARIO.github.io/equipos-pwa/)

## ✨ Funcionalidades
- Cargar jugadores con atributos (overall, ataque, defensa, arquero, resistencia, pie, posición).
- Seleccionar quiénes van al próximo partido.
- Armar automáticamente 2 equipos parejos (5vs5, 6vs6 o 7vs7).
- Guardado en **localStorage** (no se pierde al cerrar).
- Exportar/Importar lista de jugadores en JSON.
- **Instalable como app** (PWA, con soporte offline básico).

## 📱 Instalación en celular
1. Abrir la URL en **Chrome (Android)**.
2. Tocar menú **⋮ → “Añadir a pantalla de inicio”**.
3. O aceptar el banner “Instalar” cuando aparezca.
4. ¡Listo! La app queda en el inicio y se abre a pantalla completa.

## 🛠️ Desarrollo
Estructura mínima del proyecto:
```
/index.html
/manifest.webmanifest
/sw.js
/icon-192.png
/icon-512.png
```

El `service worker (sw.js)` hace cache de los archivos básicos para uso offline.  
El `manifest.webmanifest` define los íconos, colores y nombre de la app.

## ✅ Checklist de pruebas en el celular
1. **Abrir la URL**: comprobá que carga sin errores.  
2. **Agregar jugadores**: probá cargar 2–3 jugadores.  
3. **Cargar ejemplo**: verificá que se agregan jugadores de prueba.  
4. **Armar equipos**: seleccioná jugadores y tocá “Armar 2 equipos” → deberían aparecer los equipos balanceados.  
5. **Instalar PWA**:  
   - En Android → Chrome menú ⋮ → Añadir a pantalla de inicio.  
   - Verificá que se abre en pantalla completa y tiene ícono.  
6. **Modo offline**: abrí la app, luego poné el celu en modo avión y volvé a abrir → debería funcionar (con los datos que ya tengas).  
7. **Exportar/Importar**: probá exportar lista a JSON y volver a importarla.  

## 👥 Créditos
App creada para organizar picaditos entre amigos ⚽
