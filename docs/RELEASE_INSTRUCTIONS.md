# Instrucciones para crear un release firmado (pasos recomendados)

1. Asegúrate de tener tu clave GPG configurada y git firmando commits:
   - `git config --global user.signingkey <TU_KEYID>`
   - `git config --global commit.gpgSign true`

2. Crear tag firmado:
   - `git tag -s v1.0 -m "v1.0 — Release inicial del Sistema de Caducidades"`

3. Subir tag y rama principal:
   - `git push origin main`
   - `git push origin v1.0`

4. En GitHub, ir a "Releases" y crear un nuevo release usando el tag `v1.0`.
   - Añade notas legales y descarga el ZIP del release para guardarlo offline.

5. Guarda copias locales del release (zip/tar) con checksums.
