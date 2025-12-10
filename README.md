# FloodWatch - WebGIS Monitoring Banjir Real-time

## 📋 Deskripsi Project
FloodWatch adalah sistem monitoring banjir berbasis WebGIS yang memungkinkan pemantauan real-time kondisi banjir di berbagai kota di Indonesia. Sistem ini mengintegrasikan data spasial dengan interface yang user-friendly untuk memberikan informasi cepat dan akurat kepada masyarakat.

## 🚀 Fitur Utama

### 1. **Real-time Monitoring**
- Update data ketinggian air setiap 5 detik
- Simulasi perubahan kondisi banjir secara dinamis
- Dashboard statistik live (total titik banjir, zona merah)

### 2. **Crowdsourcing (Lapor Banjir)**
- Masyarakat dapat melaporkan banjir dengan klik pada peta
- Input lokasi dan ketinggian air secara real-time
- Validasi data otomatis dan feedback instan

### 3. **Sistem Peringatan**
- Alert panel dengan kategori KRITIS dan WASPADA
- Notifikasi berdasarkan ketinggian air (>50cm = Kritis, 30-50cm = Waspada)
- Update peringatan otomatis sesuai kondisi terkini

### 4. **Rute Evakuasi Otomatis**
- Klik zona merah untuk melihat rute evakuasi terdekat
- Algoritma pencarian zona aman terdekat
- Visualisasi rute dengan garis putus-putus berwarna biru

### 5. **Search & Navigation**
- Pencarian kota dengan autocomplete
- Fly-to animation ke lokasi yang dipilih
- Filter berdasarkan nama kota

### 6. **Responsive Design**
- Mobile-friendly dengan collapsible sidebar
- Glassmorphism UI design yang modern
- Touch-friendly controls untuk mobile

## 🛠️ Teknologi yang Digunakan

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Mapping**: Leaflet.js
- **UI/UX**: Custom CSS dengan Glassmorphism effect
- **Icons**: FontAwesome 6.4.0
- **Fonts**: Google Fonts (Poppins, Inter)
- **Data**: JSON files (simulasi database)

## 📊 Struktur Data

### Markers (Titik Banjir)
```json
{
  "id": 1,
  "location": "Bundaran HI (Jakarta)",
  "city": "Jakarta",
  "lat": -6.2000,
  "lng": 106.8300,
  "date": "2024-12-10",
  "height": 50
}
```

### Zones (Zona Risiko)
```json
{
  "city": "Jakarta",
  "name": "Zona Merah Jakarta",
  "riskLevel": "High",
  "color": "red",
  "coords": [[-6.1900, 106.8200], ...],
  "description": "Zona Merah (JKT) - Risiko Tinggi"
}
```

## 🎯 Target Pengguna

1. **Masyarakat Umum**: Informasi kondisi banjir real-time
2. **Pemerintah Daerah**: Monitoring dan pengambilan keputusan
3. **Tim SAR/Rescue**: Koordinasi evakuasi dan bantuan
4. **Media**: Sumber informasi terpercaya untuk pemberitaan

## 🔮 Pengembangan Selanjutnya

- Integrasi dengan API cuaca real-time
- Notifikasi push untuk mobile app
- Machine learning untuk prediksi banjir
- Integration dengan social media untuk crowdsourcing
- Historical data analysis dan reporting

## 📱 Cara Penggunaan

1. **Monitoring**: Buka aplikasi untuk melihat kondisi real-time
2. **Lapor Banjir**: Klik pada peta → isi form → submit
3. **Cari Lokasi**: Gunakan search box untuk mencari kota
4. **Rute Evakuasi**: Klik zona merah untuk melihat rute aman
5. **Layer Control**: Toggle on/off layer sesuai kebutuhan

---

**Developed by**: [Armaya Wira Sandi]
**NIM**: [231240001437]
**Mata Kuliah**: [Sistem Informasi Geografis]  

