# 🎧 StudioRemix PRO

**Aplikasi Audio Remix & Video Visualizer berbasis HTML, CSS, dan JavaScript.**

StudioRemix PRO adalah aplikasi web untuk mengolah audio, mengatur equalizer, menambahkan efek suara, memilih cover, dan membuat video visualizer dengan tampilan pemutar musik bergaya iPhone.

---

## ✨ Features

### 🎵 Audio Player
- Upload file audio.
- Play / Pause.
- Previous / Next (geser 10 detik).
- Pengaturan volume.
- Progress bar audio.
- Mini audio visualizer.

### 🎚️ Advanced Equalizer
- 8-Band Equalizer.
- Preset Flat.
- Preset Bass.
- Preset Vocal.
- Preset DJ.
- Preset Jernih.
- Equalizer ON/OFF.
- Reset Equalizer.

### 🔊 Audio Effects
- Bass Boost.
- Low Pass Filter.
- High Pass Filter.
- Reverb Room.
- Reverb Hall.
- Playback Speed:
  - 0.75x
  - 1.0x
  - 1.25x
  - 1.5x

### ✂️ Audio Trimmer
- Memilih titik awal audio.
- Memilih titik akhir audio.
- Potongan 15 detik.
- Potongan 30 detik.
- Potongan 60 detik.
- Custom audio trimming.
- Preview bagian audio.

### 🖼️ Cover & Music Preview
- Upload cover gambar sendiri.
- Background blur otomatis.
- Mengubah judul lagu.
- Mengubah nama artist.
- Tampilan pemutar musik bergaya iPhone.

### 🎬 Video Renderer
- Render video menggunakan MediaRecorder.
- Resolusi 480p, 720p, dan 1080p.
- Orientasi Portrait (9:16).
- Orientasi Landscape (16:9).
- Pilihan 24, 30, dan 60 FPS.
- Audio visualizer pada video.
- Informasi judul dan artist.
- Progress playback pada video.
- Download hasil render.

Format hasil render mengikuti dukungan browser: MP4 jika tersedia, atau WebM sebagai alternatif.

---

## 🚀 Installation

Tidak memerlukan instalasi package atau framework tambahan.

1. Clone repository:

```bash
git clone https://github.com/rhmdprtma/StudioRemix.git
```

2. Masuk ke folder:

```bash
cd StudioRemix-PRO
```

3. Buka file `index.html` menggunakan browser.

---

## 🌐 GitHub Pages

Untuk menjalankan aplikasi melalui GitHub Pages:

1. Buka repository GitHub.
2. Masuk ke **Settings**.
3. Pilih **Pages**.
4. Pada bagian Build and deployment, pilih Deploy from a branch.
5. Pilih branch `main`.
6. Pilih folder `/root`.
7. Klik Save.

Tunggu proses deployment selesai, kemudian buka URL GitHub Pages repository.

---

## 📱 Browser Compatibility

Disarankan menggunakan browser modern yang mendukung:

- Web Audio API.
- MediaRecorder API.
- Canvas API.
- Canvas captureStream().
- MediaStream API.

Chrome dan Edge versi terbaru direkomendasikan.

**Catatan:** Dukungan format MP4/WebM berbeda-beda tergantung browser dan perangkat. Rendering resolusi tinggi juga membutuhkan resource perangkat lebih besar.

---

## ⚠️ Important Notes

- Gunakan file audio yang didukung browser.
- Pastikan audio sudah selesai dimuat sebelum melakukan render.
- Rendering 1080p 60 FPS dapat membutuhkan RAM dan CPU yang besar.
- Gunakan 720p 30 FPS untuk pengujian awal.
- Aplikasi berjalan di browser dan tidak membutuhkan backend khusus.

---

## 🛠️ Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Web Audio API
- Canvas API
- MediaRecorder API
- MediaStream API

---

## 👨‍💻 Developer

**Tama-ID**

Project: StudioRemix PRO  
Category: Audio Remix & Video Visualizer  
Version: PRO

---

## ⭐ Support

Jika project ini bermanfaat, jangan lupa berikan ⭐ Star pada repository GitHub ini.

**StudioRemix PRO — Remix Your Sound, Create Your Style! 🎧🔥**
