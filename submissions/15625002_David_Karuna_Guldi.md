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
| **P2** | Webhook Triggers & Data Transformation | [P2_David_Karuna_Guldi.json](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-02/P2_David_Karuna_Guldi.json) | [P2_David_Karuna_Guldi.png](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-02/P2_David_Karuna_Guldi.png) | Belum |
| **P3** | Advanced API Integration & Error Handling | [P3_David_Karuna_Guldi.json](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-03/P3_David_Karuna_Guldi.json) | [P3_David_Karuna_Guldi.png](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-03/P3_David_Karuna_Guldi.png) | Belum |
| **P4** | AI Agent & LLM Chain Automation di n8n | [P4_David_Karuna_Guldi.json](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-04/P4_David_Karuna_Guldi.json) | [P4_David_Karuna_Guldi.png](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-04/P4_David_Karuna_Guldi.png) | Belum |
| **P5** | Capstone Final Project: Smart Autonomous AI | [P5_David_Karuna_Guldi.json](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-05/P5_David_Karuna_Guldi.json) | [P5_David_Karuna_Guldi.png](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-05/P5_David_Karuna_Guldi.png) | Belum |

---

## 💡 Ringkasan & Solusi Otomasi (Workflow Highlights)
Tuliskan penjelasan singkat mengenai alur kerja yang telah kamu bangun:
- **Tujuan Workflow**: Webhook Aspirasi. Pesan dikirim dari Hoppscotch, n8n merapikan datanya, lalu membalas dengan nama dan pesan pengirim.
- **Node Kunci yang Digunakan**: Webhook, Edit Fields, Respond to Webhook.
- **Logika Alur Kerja**: Webhook menerima body JSON berisi Nama dan Pesan, Edit Fields membuat field status dan message, lalu Respond to Webhook mengirim hasilnya kembali sebagai balasan HTTP.

---

## 🌟 Refleksi & Kesan Belajar
Di P1 aku belajar bahwa workflow = trigger + action, dan webhook seperti bel rumah yang membuat n8n langsung tahu ada data masuk.
