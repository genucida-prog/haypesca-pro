# HayPesca Pro - GitHub Pages

App profesional de pesca en España v3.2

## Como desplegar sin API

1. Crea repo en GitHub: haypesca-pro
2. Sube todos los archivos de esta carpeta (index.html, manifest.json, iconos)
3. En GitHub: Settings > Pages > Source: Deploy from branch > main / root
4. Tu app estara en https://TU_USUARIO.github.io/haypesca-pro/

## Que funciona sin API key

- ✅ Mapa satelite Esri World Imagery (gratis, sin key) - ya integrado en el codigo
- ✅ Geolocalizacion real del movil
- ✅ Registro, chats por provincia, foro, bitacora (localStorage - cada usuario ve lo suyo, si quieres compartido usa Firebase gratis)
- ✅ Identificacion peces por foto + medicion por camara
- ✅ Meteo mock (cambiar a Open-Meteo gratis sin key: ver codigo en index.html buscar open-meteo)
- ✅ Icono instalable en movil (PWA) - Add to Home Screen

## Si quieres chats compartidos para todos (gratis)

Opcional, sin API de Google:
- Crea proyecto en Firebase (console.firebase.google.com) - gratis
- Firestore + Auth
- Copia config y pega en index.html donde dice firebaseConfig

Sin esto, los chats funcionan pero solo los ves tu. Con Firebase los ven todos.

## Estructura
- index.html = app completa
- manifest.json = para instalar en movil
- *.webp = imagenes peces e icono

Listo para compilar!
