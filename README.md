# mdv (Minimal DevOps CLI)

`mdv` adalah CLI sederhana untuk mempermudah konfigurasi VPS berbasis AlmaLinux/RHEL (bisa juga di Ubuntu/Debian).
Didesain untuk:
- Manajemen port (firewall)
- Manajemen domain (hosts override)
- Publish aplikasi Node.js via Nginx reverse proxy
- SSL otomatis (Let's Encrypt)
- Export/Import konfigurasi (biar gampang migrasi VPS)

## 🚀 Instalasi

```bash
curl -L https://raw.githubusercontent.com/marhaendev/mdv/main/mdv -o /usr/local/bin/mdv
chmod +x /usr/local/bin/mdv


📋 Contoh Pemakaian
Port Management
mdv port list
mdv port e 3000
mdv port d 3000

App Management
mdv app add app.example.com 3000
mdv app ssl app.example.com
mdv app list

Config Export/Import
mdv config export myvps.json
mdv config import myvps.json

📄 License

MIT License
