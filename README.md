Praktikum 05 Web Service Engineering
Nama dan NIM: Najib Rabbani Syarif, 240104040058 (TI24)
Lingkungan: Node.js 24.21.0, npm 11.19.0, Express 5.3.0

Instalasi dari proyek yang sudah mempunyai lockfile:
npm ci
npm run docs

Terminal pertama:
npm start

Terminal kedua:
node client.cjs GET /api/buku/1

API: http://127.0.0.1:3200/api/buku
Dokumen: http://127.0.0.1:3200/openapi.json
Swagger UI: http://127.0.0.1:3200/docs/

Batas: tanpa login, data array dalam memori.
Data tambahan hilang setelah server dimulai ulang.
Hentikan server dengan Ctrl+C pada terminal pertama.
