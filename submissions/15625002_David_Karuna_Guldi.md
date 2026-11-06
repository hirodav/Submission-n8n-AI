# Submission n8n Study Jam - GDGoC Universitas Widyatama

## 👤 Informasi Peserta
- **Nama Lengkap**: David Karuna Guldi
- **NIM**: 15625002
- **Program Studi**: Teknik Robotika dan Kecerdasan Buatan
- **Username GitHub**: [@hirodav](https://github.com/hirodav)
- **URL Repositori Tugas**: [https://github.com/hirodav/GDGoC-n8n-StudyJam](https://github.com/hirodav/GDGoC-n8n-StudyJam)

---

## 📊 Matriks Progres Tugas (P1 - P5)

| Pertemuan | Topik Tugas | Tautan File Workflow (.json) | Bukti Eksekusi (Screenshot) | Status |
| :---: | :--- | :---: | :---: | :---: |
| **P1** | Pengenalan n8n & Workflow Automation Dasar | [P1_David_Karuna_Guldi.json](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-01/P1_David_Karuna_Guldi.json) | [P1_David_Karuna_Guldi.png](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-01/P1_David_Karuna_Guldi.png) | Selesai |
| **P2** | Webhook Triggers & Data Transformation | - | - | Belum |
| **P3** | Advanced API Integration & Error Handling | - | - | Belum |
| **P4** | AI Agent & LLM Chain Automation di n8n | - | - | Belum |
| **P5** | Capstone Final Project: Smart Autonomous AI | - | - | Belum |

---

## 💡 Ringkasan & Solusi Otomasi (Workflow Highlights)
- **Tujuan Workflow**: Webhook Aspirasi. Pesan dikirim dari Hoppscotch, n8n merapikan datanya, lalu membalas dengan nama dan pesan pengirim.
- **Node Kunci yang Digunakan**: Webhook (POST, Respond: Using 'Respond to Webhook' Node), Edit Fields, Respond to Webhook.
- **Logika Alur Kerja**: Webhook menerima body JSON berisi `Nama` dan `Pesan`. Edit Fields membuat field `status` dan `message`. Respond to Webhook mengirim item pertama itu kembali sebagai balasan HTTP.

---

## 🌟 Refleksi & Kesan Belajar
Di P1 aku belajar bahwa workflow = trigger + action, dan webhook seperti bel rumah yang membuat n8n langsung tahu ada data masuk.
