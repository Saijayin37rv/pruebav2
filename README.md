# ClickCar - Servidor de Pruebas

Este servidor sirve los archivos estáticos en la carpeta `PRUEBAS` y expone un endpoint sencillo `/api/status`.

Requisitos
- Node.js 14+ (recomendado 18+)

Instalación

1. Abrir terminal en `c:\Users\fjavi\PROYECTOS\PRUEBAS`
2. Ejecutar:

```powershell
npm install
```

Ejecución

- Para ejecutar el servidor:

```powershell
npm start
```

- Para desarrollo con reinicio automático (requiere nodemon):

```powershell
npm run dev
```

Notas
- El servidor sirve `index.html` y todos los recursos en la carpeta.
- Si quieres servir desde otro puerto, exporta la variable de entorno `PORT`.
- Para pruebas de geolocalización, usa `http://localhost:3000` (o el puerto que configures) en lugar de abrir el archivo `file://`.
