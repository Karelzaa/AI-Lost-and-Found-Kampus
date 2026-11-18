# AI-Lost-and-Found-Kampus
Kelompok 5 Project AI Computer Platform

# Anggota Kelompok :
1.	Carol Lorenza Br Girsang (233303030343)
2.	Ronata S. Meliala (233303030364)
3.	Nestor Famataro Harefa (233303030329)
4.	Simon Rafael (233303030321)
5.	Teopilus Brahmana (233303030350)
6.	Aygift Gustian Damanik (233303030371)

# Lost & Found Unpri

Aplikasi web Lost & Found untuk kampus Universitas Prima Indonesia (Unpri). Pengguna bisa melaporkan barang hilang atau ditemukan, mencari barang, mengajukan klaim, dan berkonsultasi dengan asisten AI.

## Fitur
- Asisten AI (Ollama) untuk melapor, mencari, dan mengecek status klaim lewat chat
- Form lapor barang hilang atau ditemukan, dengan foto opsional
- Pencarian barang dan pencocokan otomatis antar laporan
- Verifikasi klaim oleh admin
- Statistik laporan dan ekspor data ke CSV

## Teknologi
Python, Streamlit, Ollama (llama3.2), SQLite, Pandas

## Cara menjalankan
1. Instal dependensi:
   ```
   pip install -r requirements.txt
   ```
2. Instal Ollama, lalu unduh modelnya:
   ```
   ollama pull llama3.2
   ```
3. Jalankan aplikasi:
   ```
   streamlit run app_unpri.py
   ```

## Akun admin
Password admin dibaca dari variabel lingkungan `ADMIN_PASSWORD`. Kalau tidak diatur, default-nya `admin123`, jadi ganti sebelum aplikasi dipakai sungguhan.
