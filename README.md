# MARIBACA-ext

Repository ini berisi website statis blueprint MariBaca.

## File Utama

- `index.html` → entry point website
- `maribaca_blueprint.html` → halaman blueprint utama

## Cara Menjalankan Lokal

### Opsi 1 (langsung buka file)
1. Buka `index.html` di browser.

### Opsi 2 (disarankan: local server)
1. Masuk ke folder project:
   ```bash
   cd /home/runner/work/MARIBACA-ext/MARIBACA-ext
   ```
2. Jalankan server Python:
   ```bash
   python3 -m http.server 8080
   ```
3. Buka di browser:
   ```text
   http://localhost:8080
   ```

## Deploy

Karena ini website statis, bisa langsung di-deploy ke layanan static hosting seperti:
- GitHub Pages
- Netlify
- Vercel (static site)
