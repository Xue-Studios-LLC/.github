# Xue Studios LLC — Configuración de Organización GitHub

Esta carpeta independiente contiene los archivos base para el repositorio especial `.github` de tu organización en GitHub ([github.com/Xue-Studios-LLC](https://github.com/Xue-Studios-LLC)).

---

## 📁 Estructura

- **`profile/README.md`**: Portada pública institucional para el perfil de la organización. Aclara explícitamente que todo el código y la documentación se encuentran en **fase de Beta Privada** y no compromete fechas fijas.
- **`SECURITY.md`**: Política de reporte responsable de vulnerabilidades a `support@oim.media`.
- **`CODE_OF_CONDUCT.md`**: Código de conducta de la comunidad (Contributor Covenant v2.1).

---

## 🚀 Publicar en GitHub

1. En GitHub, crea el repositorio `.github` dentro de la organización **Xue-Studios-LLC** (público, vacío).
2. Abre una terminal en esta carpeta (`c:\Users\Jxue\Documents\Xue-Studios-LLC`) y ejecuta:
   ```bash
   git init
   git remote add origin https://github.com/Xue-Studios-LLC/.github.git
   git add .
   git commit -m "feat: inicializar perfil de la organizacion, seguridad y codigo de conducta"
   git branch -M main
   git push -u origin main
   ```
