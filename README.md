# template-prompt
Bantu aku membangun aplikasi WhatsApp Bot menggunakan Baileys + Node.js + Express.js.  
Aku ingin bot ini punya fitur dasar seperti:
- Koneksi ke WhatsApp Web via QR Code
- Menerima pesan dan merespons otomatis (auto-reply)
- Mengirim pesan manual ke nomor tertentu
- Broadcast pesan ke banyak nomor
- Bisa dijalankan sebagai server Express.js

Struktur project-nya mohon dibuat modular:
- Folder `controllers` untuk logic
- Folder `services` untuk koneksi Baileys
- Folder `routes` untuk API endpoint
- File utama di `index.js` atau `server.js`

Gunakan kode yang clean, komentar secukupnya, dan sertakan:
- package.json dependencies
- Instruksi setup singkat (misal: `npm install`, `node server.js`)
- Cara menyimpan session auth (pakai file JSON atau sejenisnya)

Berikan juga:
1. Contoh auto-reply jika pesan mengandung kata "halo"
2. Contoh endpoint REST API untuk kirim pesan ke nomor WhatsApp tertentu
3. Cara handle reconnect jika sesi logout atau koneksi drop

Anggap aku udah familiar dengan Node.js, tapi belum terlalu paham Baileys. Jelaskan konsep pentingnya secara singkat di awal.
