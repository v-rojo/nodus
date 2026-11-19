# NODUS La Guaira

Sitio estático de una sola página (`index.html`), sin dependencias ni paso de compilación.

## Ver en local

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python3 -m http.server 8000
```

## Deploy en GitHub Pages

1. Sube el código a la rama `main`.
2. En GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Cada push a `main` publica el sitio con `.github/workflows/deploy.yml`
   (también se puede lanzar a mano desde la pestaña **Actions**).

La URL quedará como `https://<usuario>.github.io/nodus/`.
