# Islam Together — Eliminación de Cuenta y Datos (Account & Data Deletion)

Repositorio estático listo para **GitHub Pages** con la página oficial de **Eliminación de Cuenta y Datos** de la aplicación **Islam Together** (`com.islamtogether.app`), exigida por **Google Play Console** en el formulario de *Seguridad de los datos (Data Safety)*.

---

## 🚀 Cómo publicarlo en GitHub Pages

1. Crea un nuevo repositorio público en GitHub llamado, por ejemplo, `islamtogether-delete-account`.
2. Desde una terminal dentro de esta carpeta (`islamtogether-delete-account`), ejecuta:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Account & Data Deletion page for Google Play"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/islamtogether-delete-account.git
   git push -u origin main
   ```
3. En GitHub, entra en **Settings → Pages**.
4. En **Build and deployment → Source**, selecciona **Deploy from a branch**, elige la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
5. En 1 minuto tendrás tu URL pública lista:
   `https://TU_USUARIO.github.io/islamtogether-delete-account/`

---

## 📍 Dónde pegar esta URL en Google Play Console

- **Contenido de la aplicación (App content) → Seguridad de los datos (Data safety) → Eliminación de cuentas de la aplicación:**
  - En *"Añade un enlace que los usuarios puedan utilizar para solicitar que se elimine su cuenta y los datos asociados"*, pega la URL de este GitHub Pages.
  - Si también te pide el enlace de eliminación parcial de datos, puedes pegar esta misma URL (ya que el formulario incluye selector para eliminación total de cuenta o eliminación parcial de datos).
