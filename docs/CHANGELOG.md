# CHANGELOG — Riwayat Pengembangan Gawe Ukoro

## v0.1 — Inisiasi Konsep (Juni 2026)
**Ide awal:**
- Kebutuhan alat bantu untuk membuat preset prompt musik AI
- Target platform: Suno, Flow Music (Google DeepMind Lyria 3), Udio
- Konsep awal: tap-to-select chip dengan output prompt bahasa Inggris

**Keputusan arsitektur:**
- Stack: React + Tailwind CSS via CDN
- Hosting: GitHub Pages (gratis, permanen)
- Database: Supabase (private, PostgreSQL)
- Device target: Tablet Android + Termux

---

## v0.2 — Kamus Musik Pertama
**Yang dikembangkan:**
- Kamus genre (39 genre, 8 grup)
- Kamus mood/rasa (21 item)
- Kamus vokal/swara (18 item)
- Kamus tempo/wirama (19 item)
- Kamus instrumen (33 item, 7 grup)
- Kamus produksi (10 item)
- Kamus instrumen daerah Indonesia (original)
  - Instrumen Jawa, Sunda, Bali, Sumatera, 
    Sulawesi, Papua, NTT

---

## v0.3 — Struktur & Sub-Instruksi
**Yang dikembangkan:**
- 12 tipe section struktur lagu
- 50+ sub-instruksi dengan kategorisasi
- Flag system: normal / warn / red
- Sistem durasi ideal per section
- Logic Gate conflict rules (5 aturan)

---

## v0.4 — Curated Mode & Compatibility Map
**Yang dikembangkan:**
- Sistem kompatibilitas 4 level:
  auto-centang / normal / warn / hide
- Compatibility map untuk 22 genre
- Auto-centang rekomendasi saat pilih genre
- Toggle Curated Mode ON/OFF

---

## v0.5 — Database Integration
**Yang dikembangkan:**
- Integrasi Supabase sebagai database
- Tabel preset_gawe_ukoro
- Tabel preset_referensi (14 preset)
- Tabel template_racik (15 template)
- Save/load/delete preset
- Export bundle ke .txt

---

## v0.6 — Logic Gate & Flag System
**Yang dikembangkan:**
- Conflict detection antar sub-instruksi
- Total durasi counter (max 3:00)
- Durasi warning per section
- Contextual hide: tag lokal tersembunyi
  jika tidak ada instrumen lokal

---

## v0.7 — Template Racik
**Yang dikembangkan:**
- 15 template racik orisinal:
  1. Dangdut Koplo Energik
  2. Gamelan Ambient Mistis
  3. Dark Phonk Aggressive
  4. Lo-Fi Chill Acoustic
  5. Cinematic Orchestral Epic
  6. Keroncong Kontemporer
  7. Modern R&B Neo-Soul
  8. Jedag-Jedug Viral
  9. Alternative Rock Melankolis
  10. Smooth Jazz Sensual
  11. Indie Etnik Sunda
  12. Power Ballad Dramatik
  13. Campursari Galau Modern
  14. Synthwave Retro Neon
  15. Ethno-Cinematic Hybrid
- Popup template dengan filter & rating
- Empty state dengan tombol template

---

## v0.8 — Musical Scale & Intensity Curve
**Yang dikembangkan:**
- Parameter Tangga Nada/Scale (11 item):
  Major, Lydian, Mixolydian, Natural Minor,
  Harmonic Minor, Dorian, Phrygian,
  Pentatonic, Slendro, Pelog, Hijaz
- Intensity Curve visual (bar chart)
- Energy level per section (1-5)
- Reverb Size di parameter produksi
- BPM tambahan: 76, 90, 96, 100, 110

---

## RENCANA (Belum Dikerjakan)
- Tab Kamus dengan 168 istilah
- Tooltip bottom sheet
- Gemini API untuk narrative output
- Preview mode untuk PDF
- Tier produk label

