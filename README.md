# TUGAS BESAR ADVANCED NETWORK SECURITY  
## Implementasi Honeypot Cowrie untuk Deteksi Serangan Jaringan

---

## 👥 Kelompok 10
- **Iryan Tegar**  
  NIM: 105841113023  

- **Putri Amelia Nur**  
  NIM: 105841114423  

---

## 📘 Deskripsi Singkat
Repository ini berisi dokumentasi dan laporan Tugas Besar mata kuliah **Advanced Network Security**.  
Penelitian ini membahas **implementasi honeypot Cowrie** pada server berbasis Linux untuk mendeteksi dan menganalisis berbagai jenis serangan jaringan, seperti **port scanning**, **bruteforce SSH**, dan **DoS attack**.

Honeypot digunakan sebagai sistem umpan (decoy) untuk menarik penyerang dan mencatat seluruh aktivitas serangan tanpa mengganggu layanan utama server.

---

## 🧪 Jenis Pengujian Serangan
- **Port Scanning** menggunakan Nmap  
- **Bruteforce Attack SSH** menggunakan Hydra  
- **DoS Attack** menggunakan LOIC  

---

## 🗂️ Struktur Folder Repository
TUGAS_BESAR_ADVANCEDNETWORKSECURITY/
│
├── dokumentasi/
│ ├── screenshot/
│ │ ├── nmap/ # Screenshot hasil port scanning
│ │ ├── hydra/ # Screenshot serangan bruteforce
│ │ ├── loic/ # Screenshot simulasi DoS attack
│ │ └── cowrie-log/ # Screenshot log honeypot Cowrie
│ │
│ └── diagram/ # Diagram topologi sistem
│
├── laporan/
│ └── Laporan_Final.pdf # Laporan akhir tugas besar
│
├── topologi/
│ └── Topologi_Sistem.png # Gambar topologi implementasi
│
└── README.md # Dokumentasi repository


---

## 🖥️ Lingkungan & Tools
- **Server** : Ubuntu Server (VPS)
- **Honeypot** : Cowrie (Low Interaction SSH Honeypot)
- **Sistem Penyerang (Simulasi)** : Kali Linux (VMware Workstation)
- **Tools Pengujian** :
  - Nmap
  - Hydra
  - LOIC

---

## 🎯 Tujuan Penelitian
- Menganalisis efektivitas honeypot Cowrie dalam mendeteksi serangan jaringan
- Mengamati pola serangan berdasarkan log yang dihasilkan
- Memisahkan jalur serangan dan jalur administrasi server secara aman

---

## 📌 Catatan
Seluruh pengujian dilakukan **dalam lingkungan terkontrol** dan **untuk keperluan akademik**, tanpa melibatkan sistem pihak lain.

---

© 2026 – Kelompok 10 | Advanced Network Security
