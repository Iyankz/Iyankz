# 👋 Yayang Ardiansyah (Iyankz)

**Operations Manager · Network Architect · ISP Systems Builder**

🇮🇩  
Saya membangun, mengoperasikan, dan menskalakan infrastruktur ISP dunia nyata —  
mulai dari monitoring, automasi, keamanan, hingga operasional jaringan skala besar.

🇬🇧  
I build, operate, and scale real-world ISP infrastructure —  
from monitoring and automation to security and large-scale network operations.

🔥 **NEVER SURRENDER**

---

## ⚡ Ringkasan Singkat | At a Glance

🇮🇩
- 👔 Mengelola **3 ISP di Sukabumi**
- 🌐 Konsultan ISP untuk berbagai wilayah di Indonesia
- 🧠 Berpengalaman di industri ISP sejak **2017** (Layer 1 → Management)
- 🏗️ Membangun sistem operasional ISP berbasis produksi
- 🛡️ Fokus: stabilitas, automasi, keamanan, dan kepatuhan

🇬🇧
- 👔 Managing **3 ISPs in Sukabumi**
- 🌐 ISP consultant across Indonesia
- 🧠 Experience in the ISP industry since **2017** (Layer 1 → Management)
- 🏗️ Builder of production-grade ISP operational systems
- 🛡️ Focus: stability, automation, security, and compliance

---

## 🌐 Portfolio & Source of Truth

- 🌍 **Landing Page / Portfolio**  
  👉 https://iyankz.github.io

- 📦 **All repositories & source code**  
  👉 https://github.com/Iyankz?tab=repositories

---

## 🧱 Core Systems | Sistem Inti

Seluruh tools berikut dirancang **bukan sebagai aplikasi terpisah**,  
melainkan sebagai **Unified ISP Operational Platform**.

---

### 🧰 Getols  
**Gateway for Extended OLT Services**

🇮🇩 **GETOLS (Gateway for Extended OLT Services)** adalah **platform gateway open-source** yang dirancang untuk **menyederhanakan, menyatukan, dan mengamankan operasional OLT & ONU multi-vendor** melalui **satu pintu eksekusi command** yang **terkontrol, terstandarisasi, dan teraudit**.

GETOLS berperan sebagai **operational control plane** yang mengabstraksi perbedaan sintaks, perilaku, dan metode akses antar vendor OLT, sehingga engineer dan tim NOC dapat bekerja dengan **workflow yang konsisten** tanpa harus berinteraksi langsung dengan perangkat.

GETOLS menggabungkan:
- 🤖 **Telegram Bot** — eksekusi cepat untuk engineer lapangan & incident handling
- 🌐 **Web Dashboard** — manajemen terpusat, visualisasi, dan observabilitas
- 🧩 **Command Abstraction Layer** — normalisasi perintah lintas vendor OLT/ONU
- 🔐 **RBAC & Audit Trail** — kontrol akses, pembatasan perintah, dan pencatatan aktivitas

Fokus utama:
- Sentralisasi akses & kontrol operasional OLT/ONU
- Reduksi human error akibat perbedaan command vendor
- Peningkatan keamanan melalui gateway terkontrol
- Mendukung workflow NOC dan engineer lapangan secara real-time

🇬🇧 **GETOLS (Gateway for Extended OLT Services)** is an **open-source gateway platform** designed to **simplify, unify, and secure multi-vendor OLT & ONU operations** through a **single, controlled, and auditable command execution entry point**.

👉 https://github.com/Iyankz/GETOLS

---

### 🔥 LeuitLog  
**Lightweight SIEM & Syslog Recorder**

🇮🇩 **LeuitLog** adalah **Lightweight SIEM & Syslog Recorder** yang dirancang untuk **ISP, Data Center, dan infrastruktur Linux**, dengan fokus pada **visibilitas log, keamanan operasional, dan kedaulatan data**.

Terinspirasi dari konsep **Leuit (lumbung padi)**, LeuitLog berfungsi sebagai  
**lumbung digital**, tempat log diperlakukan sebagai **aset berharga**.

Prinsip utama LeuitLog:
- 🌾 **Log sebagai aset** — disimpan dan dianalisis untuk nilai jangka panjang
- 🛡️ **Serangan dipantau aktif** — brute force, anomaly, dan aktivitas mencurigakan
- 🏠 **Kedaulatan data penuh** — berjalan **on-premise**, tanpa vendor lock-in

Fungsi utama:
- Sentralisasi syslog perangkat jaringan & server
- Audit trail aktivitas engineer & sistem
- Investigasi insiden & forensik operasional
- Dukungan lingkungan produksi skala ISP & DC

🇬🇧 **LeuitLog** is a **Lightweight SIEM & Syslog Recorder** designed for **ISPs, data centers, and Linux infrastructure**, focused on **log visibility, operational security, and full data sovereignty**.

Inspired by the **Leuit (traditional rice barn)** concept, LeuitLog acts as a  
**digital granary**, where logs are treated as **valuable assets**.

👉 https://github.com/Iyankz/LeuitLog

---

### 📡 PingTD  
**Ping · Traceroute · DNS Monitoring**

🇮🇩 **PingTD** adalah sistem monitoring konektivitas jaringan berbasis  
**Ping, Traceroute, dan DNS checking** untuk kebutuhan **NOC harian dan validasi SLA**.

Digunakan untuk:
- Monitoring backbone, upstream, dan endpoint
- Validasi dampak perubahan konfigurasi jaringan
- Baseline SLA dan histori kesehatan jaringan

🇬🇧 **PingTD** is a network connectivity monitoring system based on  
**Ping, Traceroute, and DNS checks** for **daily NOC operations and SLA validation**.

👉 https://github.com/Iyankz/PingTD

---

### 🤖 botlinkmaster  
**Telegram Network Monitoring Bot**

🇮🇩 **botlinkmaster** adalah **Bot Telegram** untuk **monitoring perangkat jaringan (router & switch)** dengan dukungan **multi-vendor**, termasuk **monitoring optical power (Tx/Rx)**.

Bot ini dirancang untuk **respons cepat NOC dan engineer lapangan**, terutama pada kondisi on-call atau incident response, tanpa perlu membuka dashboard atau login langsung ke perangkat.

Fitur utama:
- Monitoring router & switch multi-vendor
- Optical power monitoring (SFP / interface fiber)
- Notifikasi real-time ke Telegram
- Command ringan & status checking

🇬🇧 **botlinkmaster** is a **Telegram bot** designed for **multi-vendor network device monitoring**, including **optical power (Tx/Rx) monitoring**, optimized for **fast operational response**.

👉 https://github.com/Iyankz/botlinkmaster

---

## 🧭 Unified ISP Operational Platform

Keempat sistem ini membentuk **satu ekosistem operasional ISP terpadu**:

- **Getols** → *Do*  
  Eksekusi & kontrol operasional OLT/ONU
- **botlinkmaster** → *Alert & Quick Action*  
  Monitoring cepat & notifikasi real-time
- **LeuitLog** → *See*  
  Visibilitas, audit, dan keamanan
- **PingTD** → *Measure*  
  Kesehatan jaringan & SLA

Prinsip arsitektur:
- Engineer **tidak langsung login ke perangkat**
- Semua aksi melalui **gateway & bot terkontrol**
- Semua aktivitas **tercatat & teraudit**
- Semua perubahan **terukur dampaknya**

---

## 🧠 Sertifikasi & Pembelajaran | Certifications

🇮🇩  
Saya memiliki **50+ sertifikasi dan pelatihan profesional**  
di bidang networking, security, cloud, monitoring, dan operasional ISP.

🇬🇧  
I hold **50+ professional certifications and trainings**  
covering networking, security, cloud, monitoring, and ISP operations.

---

## 📬 Kontak | Contact

- 📧 Email: [iyankz.mekanik98@gmail.com](mailto:iyankz.mekanik98@gmail.com)
- 💬 Telegram: https://t.me/iyankz23
- 💼 LinkedIn: https://linkedin.com/in/yayang-ardiansyah
- 🐙 GitHub: https://github.com/Iyankz

---

> 🇮🇩 *Dari “tukang narik kabel”  
> menjadi pembangun dan pengelola sistem ISP.*

> 🇬🇧 *From pulling cables  
> to building and operating ISP systems.*

🔥 **NEVER SURRENDER**
