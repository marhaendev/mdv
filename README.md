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
curl -L https://raw.githubusercontent.com/<username>/mdv/main/mdv -o /usr/local/bin/mdv
chmod +x /usr/local/bin/mdv
