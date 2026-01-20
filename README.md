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

- 🌍 Website / Portfolio  
  👉 https://iyankz.github.io

- 🐙 GitHub Repositories  
  👉 https://github.com/Iyankz

---

## 🧱 Unified ISP Operational Platform

Seluruh tools berikut **bukan aplikasi terpisah**,  
melainkan dirancang sebagai **satu ekosistem operasional ISP terpadu**.

---

## 🧰 GETOLS  
**Gateway for Extended OLT Services**

###  Makna Nama GETOLS

Nama **GETOLS** memiliki **dua makna yang saling melengkapi**:  
makna budaya lokal dan makna teknis sistem.

#### 🔹 Makna Bahasa Sunda
Dalam bahasa Sunda, **getol** berarti:

> **rajin, tekun, konsisten dalam bekerja**

Makna ini mencerminkan filosofi GETOLS sebagai sistem yang:
- Bekerja **terus-menerus di belakang layar**
- Menangani **pekerjaan operasional yang berulang**
- Mengurangi **beban manual engineer**
- Membantu operator fokus pada **analisis dan pengambilan keputusan**

GETOLS bukan untuk menggantikan engineer,  
tetapi menjadi **rekan kerja digital** yang setia dan disiplin.

#### 🔹 Makna Teknis
Secara teknis, **GETOLS** merupakan singkatan dari:

> **Gateway for Extended OLT Services**

Huruf **“S”** pada GETOLS merepresentasikan:
- **Multi OLT**
- **Multi Vendor**
- **Multi Services**

---

### ⚙️ Deskripsi Sistem

🇮🇩 **GETOLS** adalah **platform gateway open-source** yang dirancang untuk  
**menyederhanakan, menyatukan, dan mengamankan operasional OLT & ONU multi-vendor**  
melalui **satu pintu eksekusi command** yang **terkontrol, terstandarisasi, dan teraudit**.

GETOLS berperan sebagai **operational control plane**,  
mengabstraksi perbedaan sintaks dan perilaku vendor OLT,  
sehingga engineer dan tim NOC bekerja dengan **workflow yang konsisten dan aman**.

Fitur utama:
- 🤖 Telegram Bot untuk eksekusi cepat
- 🌐 Web Dashboard untuk manajemen & observabilitas
- 🧩 Command Abstraction Layer lintas vendor
- 🔐 RBAC & audit trail

🇬🇧 **GETOLS** is an **open-source operational gateway** that unifies  
**multi-vendor OLT & ONU operations** through a **single, secure, and auditable entry point**.

👉 https://github.com/Iyankz/GETOLS

---

##  LeuitLog  
**Lightweight SIEM & Syslog Recorder**

🇮🇩 **LeuitLog** adalah **Lightweight SIEM & Syslog Recorder** yang dirancang untuk  
**ISP, Data Center, dan infrastruktur Linux**, dengan fokus pada  
**visibilitas log, keamanan operasional, dan kedaulatan data**.

Terinspirasi dari konsep **Leuit (lumbung padi)**,  
LeuitLog berfungsi sebagai **lumbung digital**, di mana:

- 🌾 **Log diperlakukan sebagai aset berharga**
- 🛡️ **Serangan dipantau secara aktif**
- 🏠 **Kedaulatan data dijaga sepenuhnya** (on-premise, tanpa vendor lock-in)

Fungsi utama:
- Sentralisasi syslog perangkat jaringan & server
- Audit trail aktivitas engineer & sistem
- Investigasi insiden & forensik operasional

🇬🇧 **LeuitLog** is a **Lightweight SIEM & Syslog Recorder** for  
**ISPs, data centers, and Linux infrastructure**,  
focused on **log visibility, security monitoring, and full data sovereignty**.

👉 https://github.com/Iyankz/LeuitLog

---

## 📡 PingTD  
**Ping · Traceroute · DNS Monitoring**

🇮🇩 **PingTD** adalah sistem monitoring konektivitas jaringan berbasis  
**Ping, Traceroute, dan DNS checking** untuk kebutuhan **NOC harian dan validasi SLA**.

Digunakan untuk:
- Monitoring backbone, upstream, dan endpoint
- Validasi dampak perubahan konfigurasi
- Baseline SLA dan histori kesehatan jaringan

🇬🇧 **PingTD** is a network connectivity monitoring system based on  
**Ping, Traceroute, and DNS checks** for **daily operations and SLA validation**.

👉 https://github.com/Iyankz/PingTD

---

## 🤖 botlinkmaster  
**Telegram Network Monitoring Bot**

🇮🇩 **botlinkmaster** adalah **Bot Telegram** untuk monitoring  
**router & switch multi-vendor**, termasuk **monitoring optical power (Tx/Rx)**.

Dirancang untuk:
- Respons cepat NOC
- Engineer lapangan & on-call
- Notifikasi real-time tanpa login ke perangkat

🇬🇧 **botlinkmaster** is a **Telegram bot** for  
**multi-vendor network device monitoring**, including **optical power (Tx/Rx)**.

👉 https://github.com/Iyankz/botlinkmaster

---

## 🧭 How Everything Fits Together

- **GETOLS** → *Do*  
  Gateway & kontrol operasional OLT/ONU
- **botlinkmaster** → *Alert*  
  Monitoring cepat & notifikasi
- **LeuitLog** → *See*  
  Log visibility, audit, security
- **PingTD** → *Measure*  
  Network health & SLA

Prinsip utama:
- Engineer **tidak langsung login ke perangkat**
- Semua aksi melalui **sistem terkontrol**
- Semua aktivitas **tercatat dan teraudit**
- Semua dampak **terukur dan tervalidasi**

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

- 📧 Email: iyankz.mekanik98@gmail.com  
- 💬 Telegram: https://t.me/iyankz23  
- 💼 LinkedIn: https://linkedin.com/in/yayang-ardiansyah  
- 🐙 GitHub: https://github.com/Iyankz

---

> 🇮🇩 *Dari “tukang narik kabel”  
> menjadi pembangun dan pengelola sistem ISP.*

> 🇬🇧 *From pulling cables  
> to building and operating ISP systems.*

🔥 **NEVER SURRENDER**
