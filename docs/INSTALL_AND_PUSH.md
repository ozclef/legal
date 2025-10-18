# Instrucciones rápidas para preparar y subir a GitHub

1. Crea (o entra) en la carpeta del proyecto:
   - `cd /ruta/al/proyecto`

2. Inicializar repositorio (si no existe):
   - `git init`
   - `git remote add origin git@github.com:TU_USUARIO/TU_REPO.git`

3. Agrega archivos y haz commit firmado:
   - `git add .`
   - `git commit -S -m "chore: publicar archivos legales y plantilla inicial"`

4. Subir rama main:
   - `git branch -M main`
   - `git push -u origin main`

5. Crea release firmado (ver RELEASE_INSTRUCTIONS.md)
