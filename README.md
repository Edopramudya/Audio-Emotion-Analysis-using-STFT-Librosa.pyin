# Analisis Emosi Audio Menggunakan STFT & Librosa.pyin  

## 📌 Penjelasan Aplikasi  
Aplikasi ini digunakan untuk menganalisis sinyal audio dengan mengekstrak fitur utama seperti **frekuensi dasar (F0)** dan **intensitas suara (RMS)** menggunakan **Short-Time Fourier Transform (STFT)** dan **Librosa.pyin**. Hasil analisis ditampilkan dalam bentuk numerik serta visualisasi seperti **grafik F0, intensitas suara, dan spektrogram STFT**.  

Aplikasi ini dapat digunakan dalam berbagai bidang, seperti:  
- **Pengenalan suara** → Mengidentifikasi pola suara berdasarkan frekuensi dan intensitas  
- **Analisis emosi** → Menilai variasi suara untuk mendeteksi emosi seperti marah dan netral  
- **Pemrosesan musik & audio** → Membantu dalam analisis rekaman suara dan pengolahan sinyal audio  

## 🔧 Software & Tools yang Digunakan  
- **Python** (Bahasa pemrograman utama)  
- **Librosa** (Ekstraksi fitur audio)  
- **NumPy** (Operasi numerik)  
- **Matplotlib** (Visualisasi data)  

## ⚙️ Cara Penggunaan  
1. **Persiapan**  
   - Pastikan Python telah terinstal  
   - Instal pustaka yang diperlukan dengan menjalankan:  
     ```bash
     pip install librosa numpy matplotlib
     ```
2. **Menjalankan Analisis**  
   - Simpan file audio yang ingin dianalisis bisa upload dengan ganti file yang diinginkan ataupun realtime
   - Jalankan skrip dengan perintah:  
     ```bash
     python main.py --file data/audio_sample.wav
     ```
   - Hasil analisis akan ditampilkan dalam bentuk angka serta grafik  

3. **Interpretasi Hasil**  
   - **Frekuensi Dasar (F0):** Mengindikasikan pitch utama dalam audio  
   - **Intensitas Suara (RMS):** Mengukur seberapa kuat suara dalam rekaman  
   - **Spektrogram STFT:** Menampilkan perubahan frekuensi terhadap waktu  

Dengan aplikasi ini, pengguna dapat memahami lebih dalam tentang karakteristik suara dan pola frekuensi dalam berbagai konteks. 🚀
