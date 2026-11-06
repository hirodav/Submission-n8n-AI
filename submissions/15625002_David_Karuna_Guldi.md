# Submission n8n Study Jam - GDGoC Universitas Widyatama

## 👤 Informasi Peserta
- **Nama Lengkap**: David Karuna Guldi
- **NIM**: 15625002
- **Program Studi**: Teknik Robotika dan Kecerdasan Buatan
- **Fakultas**: Teknik dan Ilmu Komputer
- **Universitas**: Universitas Komputer Indonesia (UNIKOM)
- **Username GitHub**: [@hirodav](https://github.com/hirodav)
- **URL Repositori Tugas**: [https://github.com/hirodav/GDGoC-n8n-StudyJam](https://github.com/hirodav/GDGoC-n8n-StudyJam)

---

## 📊 Progres Tugas (P1 - P5)

| Pertemuan | Topik Tugas | Tautan File Workflow (.json) | Bukti Eksekusi (Screenshot) | Status |
| :---: | :--- | :---: | :---: | :---: |
| **P1** | Pengenalan n8n & Workflow Automation Dasar | [P1_David_Karuna_Guldi.json](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-01/P1_David_Karuna_Guldi.json) | [P1_David_Karuna_Guldi.png](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-01/P1_David_Karuna_Guldi.png) | Selesai |
| **P2** | Webhook Triggers & Data Transformation | - | - | Belum |
| **P3** | Advanced API Integration & Error Handling | - | - | Belum |
| **P4** | AI Agent & LLM Chain Automation di n8n | - | - | Belum |
| **P5** | Capstone Final Project: Smart Autonomous AI | - | - | Belum |

---

## 🖼️ Bukti Eksekusi P1

**1. Hoppscotch: Status 200 OK** (POST ke webhook n8n, body `Nama` dan `Pesan`, response `status` dan `message`)

![Hoppscotch 200 OK](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-01/P1_David_Karuna_Guldi_hoppscotch.png?raw=true)

**2. Canvas n8n: tiga node hijau, "Workflow executed successfully"**

![Canvas n8n sukses](https://github.com/hirodav/GDGoC-n8n-StudyJam/blob/main/Pertemuan-01/P1_David_Karuna_Guldi_canvas.png?raw=true)

---

## 💡 Ringkasan & Solusi Otomasi (Workflow Highlights)
- **Tujuan Workflow**: Webhook Aspirasi. Pesan dikirim dari Hoppscotch, n8n merapikan datanya, lalu membalas dengan nama dan pesan pengirim.
- **Node Kunci yang Digunakan**: Webhook (POST, Respond: Using 'Respond to Webhook' Node), Edit Fields, Respond to Webhook.
- **Logika Alur Kerja**: Webhook menerima body JSON berisi `Nama` dan `Pesan`. Edit Fields membuat field `status` dan `message` ("Terima Kasih {{ $json.body.Nama }}, Pesan kamu {{ $json.body.Pesan }}"). Respond to Webhook mengirim item pertama itu kembali sebagai balasan HTTP.

---

## 🌟 Refleksi & Kesan Belajar
Di P1 aku belajar bahwa workflow = trigger + action, dan webhook seperti bel rumah yang membuat n8n langsung tahu ada data masuk. Kendala yang sempat muncul: parameter Respond di node Webhook masih default menjadikan balasan tidak lewat node Respond to Webhook, dan key JSON `pesan` berbeda huruf besar-kecil dari `Pesan` sehingga nilainya kosong. Keduanya selesai setelah diperbaiki.
