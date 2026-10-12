# Fase 1 – Diagnóstico de procesos

Encuesta de Tomasón y panel para ver las respuestas.

## Subir a GitHub

1. Crea un repositorio vacío en GitHub.
2. En tu computadora, dentro de esta carpeta:

```bash
git init
git add .
git commit -m "Fase 1 Tomasón"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main
```

No subas la carpeta `node_modules`.

## Publicar en Vercel

1. En Vercel elige **Add New → Project** e importa el repositorio de GitHub.
2. Deja el comando de build en `npm run build`.
3. No hace falta base de datos. Publica.

La entrevista queda en `/` y el panel en `/panel`.

Las respuestas se guardan en el navegador de quien entrevista. Si cambias de computadora o de celular, no se ven solas en el otro. El botón **Excel** del panel baja todo lo guardado en ese navegador.
