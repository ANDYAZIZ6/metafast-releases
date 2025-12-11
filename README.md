# MetaFast - AI-Powered Stock Photography Metadata Automation

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/github/v/release/ANDYAZIZ6/metafast-releases)](https://github.com/ANDYAZIZ6/metafast-releases/releases/latest)

**MetaFast** adalah aplikasi desktop berbasis AI yang dirancang khusus untuk kontributor stock photography guna mengotomatisasi pembuatan metadata (judul, deskripsi, dan keyword) untuk foto, vektor, dan video secara cepat, akurat, dan aman.

---

## ✨ Fitur Lengkap

### 🤖 AI-Powered Metadata Generation
- **Multiple AI Providers**: Google Gemini, OpenAI
- **10+ AI Models**: 
  - Gemini: gemini-3-pro-preview, gemini-2.5-flash, gemini-2.5-flash-lite, gemini-2.5-pro, gemini-2.0-flash, gemini-2.0-flash-lite
  - OpenAI: gpt-5, gpt-5-mini, gpt-5-nano, gpt-4.1, gpt-4.1-mini, gpt-4.1-nano, gpt-4o, gpt-4o-mini
- **Multi-API Key Rotation**: Rotasi otomatis untuk bypass rate limits
- **Vision Support**: Analisis gambar langsung (tidak perlu upload ke cloud)
- **Smart Generation**:
  - Judul SEO-friendly (50-200 karakter, dapat dikustomisasi)
  - Deskripsi detail (100-1000 karakter, opsional)
  - 50 Keywords maksimal per file (sesuai Adobe Stock limit)
  - Kategori otomatis (Adobe Stock & Shutterstock)

### 🚀 Performance & Speed
- **Parallel Processing**: Process gambar secara simultan
- **Smart Caching**: Thumbnail dan metadata di-cache untuk performa optimal
- **Batch Operations**: Proses ratusan file sekaligus dalam hitungan menit

### 🎯 Multi-Platform Export
Support untuk **6 platform stock photography**:
- ✅ **Adobe Stock**
- ✅ **Shutterstock**
- ✅ **Freepik**
- ✅ **Vecteezy**
- ✅ **Depositphotos**
- ✅ **123RF**
- ✅ **Canva**

Export format:
- **CSV Files**: Platform-specific CSV ready untuk upload
- **Clipboard Copy**: Salin keywords untuk paste manual
- **Auto XMP Cleanup**: Sidecar .xmp files dihapus otomatis setelah embed

### 🛡️ Content Safety & Compliance
- **Brand & IP Detection**: Deteksi 2,500+ trademarked terms, logos, dan brand names
  - Social media logos (Instagram, Facebook, TikTok, YouTube, etc.)
  - Tech brands (Apple, Google, Microsoft, Samsung, etc.)
  - Celebrities, politicians, athletes
  - Sports events (Olympics, World Cup, Super Bowl, etc.)
  - Entertainment awards (Grammy, Oscar, Emmy, etc.)
- **Smart Filtering**: Auto-replace atau remove problematic terms
- **Content Warning System**: Visual indicator untuk file bermasalah
- **Batch Delete**: Hapus semua file bermasalah dalam satu klik

### 🎨 Advanced Editing Features
- **Drag-and-Drop Keywords**: Reorder keywords dengan drag-drop
- **Individual Field Regeneration**: Regenerate judul/deskripsi/keywords secara terpisah
- **Undo/Redo History**: Multi-level undo untuk setiap file
- **Bulk Edit Metadata**: Edit metadata banyak file sekaligus
- **Copy Metadata**: Salin metadata dari satu file ke file lain
- **Negative Keywords**: Daftar kata yang tidak boleh muncul di metadata

### 📁 File Management
- **Duplicate Finder**: Scan dan deteksi file duplikat berdasarkan content hash
- **Smart Filtering**: Filter berdasarkan status, tipe file, dan keywords
- **Quick Search**: Cari file berdasarkan nama, judul, atau metadata
- **Visual & Lite Mode**: 
  - Visual mode dengan thumbnail besar
  - Lite mode untuk performance maksimal
- **Folder Monitoring**: Auto-process file baru yang ditambahkan ke folder
- **Show in Folder**: Buka file langsung di File Explorer
- **Open with Default App**: Buka gambar/video dengan aplikasi default

### 🖼️ Media Support
**File Formats**:
- Images: JPG, JPEG, PNG, TIFF, WEBP
- Vectors: EPS, AI, SVG
- Videos: MP4, MOV, AVI, MKV

**Thumbnail Generation**:
- High-quality progressive thumbnails
- FFmpeg-powered video thumbnails
- Lazy loading untuk performa optimal
- Smart caching system

### 🌍 Internationalization
- **Bilingual Interface**: 
  - ID Bahasa Indonesia
  - US English

### 🎨 User Interface
- **Modern Design**: Clean, intuitive, dan mudah digunakan
- **Dark/Light Theme**: Auto-detect sistem atau manual toggle
- **Responsive Layout**: Optimal di semua ukuran layar
- **Keyboard Shortcuts**: 
  - Ctrl+A: Select all
  - Ctrl+Shift+Click: Multi-select
  - Shift+Click: Range select
- **Drag-and-Drop**: Tambah file dengan drag-drop langsung
- **Progress Tracking**: Real-time progress indicator untuk batch operations

### ⚙️ Configuration & Settings
- **Customizable AI Settings**:
  - Model selection per provider
  - Temperature, top_p, max_tokens
  - Custom system prompts
- **Metadata Customization**:
  - Keyword count (1-50)
  - Title length min/max
  - Description length min/max
  - Keyword style (mixed, descriptive, technical)
- **Platform-Specific Settings**:
  - Enable/disable per platform
  - Custom export folder per platform
  - Auto-rename files with pattern
- **Performance Tuning**:
  - Auto-optimized (no manual tuning needed)
  - Smart concurrency management
  - Rate limit handling

### 🔒 Privacy & Security
- **100% Local Processing**: File tidak diupload ke server pihak ketiga
- **Encrypted Storage**: API keys disimpan terenkripsi di local computer
- **No Telemetry**: Tidak ada data tracking atau analytics

### 🔄 Auto-Update
- **Seamless Updates**: Auto-download dan install updates
- **Release Notes**: Changelog detail untuk setiap versi
- **Update Notifications**: Notifikasi saat update tersedia
- **Rollback Support**: Kembalikan ke versi sebelumnya jika perlu

### 🖱️ Windows Integration
- **Context Menu**: Right-click file/folder → "Generate with MetaFast"
- **File Association**: Double-click file untuk buka di MetaFast
- **System Tray**: Minimize to tray untuk background processing

### 💾 Session Management
- **Auto-Save Session**: Session tersimpan otomatis saat close app
- **Resume Work**: Lanjutkan pekerjaan dari terakhir kali
- **Export/Import Settings**: Backup dan restore settings

### 📊 Statistics & Reporting
- **Processing Stats**: 
  - Total files processed
  - Success/failure rate
  - Processing time
  - API usage
- **Visual Indicators**:
  - Color-coded status badges
  - Progress bars
  - Content warning badges

---

## 📥 Download & Installation

### Windows

**Download Installer:**
```
https://github.com/ANDYAZIZ6/metafast-releases/releases
```

**Installation:**
1. Download `MetaFast_x.x.x_x64.msi`
2. Double-click installer
3. Follow installation wizard
4. Launch MetaFast from Start Menu

**System Requirements:**
- Windows 10/11 (64-bit)
- 4GB RAM minimum (8GB recommended)
- 500MB disk space
- Internet connection (untuk AI API calls)

## 🚀 Quick Start Guide

### 1. Setup API Key

**Google Gemini (Recommended - Free Tier Available)**
1. Buka [Google AI Studio](https://aistudio.google.com/app/api-keys)
2. Login dengan Google Account
3. Klik "Create API Key"
4. Copy API key ke MetaFast Settings

**OpenAI**
1. Buka [OpenAI Platform](https://platform.openai.com/api-keys)
2. Login/Register
3. Create new API key
4. Copy ke MetaFast Settings

### 2. Add Files
- Klik **"Tambah File"** atau drag-drop file ke window
- Atau: Right-click file di Explorer → **"Generate with MetaFast"**

### 3. Configure Settings
- Pilih AI provider & model
- Set keyword count (default: 30)
- Enable/disable description generation
- Select export platforms

### 4. Generate Metadata
- Klik **"Generate Semua"** untuk batch process
- Atau klik **"Generate"** per file untuk single process

### 5. Review & Edit
- Review metadata yang di-generate
- Edit judul/deskripsi/keywords jika perlu
- Reorder keywords dengan drag-drop
- Mark file bermasalah sebagai "Safe" atau delete

### 6. Export
- Klik **"Export CSV"** untuk download CSV files
- Atau klik **"Embed Metadata"** untuk tulis ke file langsung
- Upload CSV ke platform stock photography

---

## 💡 Pro Tips

### Untuk Hasil Terbaik:

1. **Gunakan Gambar Berkualitas Tinggi**
   - Resolusi minimal 4MP (2000x2000px)
   - Fokus tajam, exposure bagus
   - Komposisi jelas

2. **Multiple API Keys**
   - Gunakan 2-3 API keys untuk rotasi
   - Bypass rate limits
   - Proses lebih cepat

3. **Negative Keywords**
   - Tambahkan kata yang tidak relevan
   - Mencegah keyword spam
   - Improve accuracy

4. **Batch Processing**
   - Group file dengan konten similar
   - Process 50-100 file per batch
   - Monitor progress

5. **Content Warning Review**
   - Selalu review file dengan warning badge
   - Mark false positives sebagai "Safe"
   - Delete file yang truly problematic

### Keyboard Shortcuts:

| Shortcut | Action |
|----------|--------|
| `Ctrl + A` | Select all files |
| `Ctrl + Click` | Multi-select individual files |
| `Shift + Click` | Select range of files |
| `Delete` | Delete selected files |
| `Ctrl + Z` | Undo (per file) |
| `Ctrl + Y` | Redo (per file) |

---

## 🔧 Troubleshooting

### API Key Issues

**"Invalid API Key"**
- Pastikan API key correct (copy-paste tanpa spasi)
- Check API key belum expired
- Verify billing/quota di platform AI

**"Rate Limited"**
- Tambah API key kedua untuk rotation
- Tunggu beberapa menit lalu retry
- Upgrade plan di AI provider

### Performance Issues

**"Slow Processing"**
- Kurangi jumlah concurrent files
- Close aplikasi lain yang berat
- Check internet connection speed

**"Out of Memory"**
- Process file dalam batch lebih kecil (25-50 files)
- Close unused tabs/apps
- Upgrade RAM jika perlu

### File Issues

**"Failed to Generate Metadata"**
- Check file format supported
- Verify file tidak corrupt
- Try regenerate individual field
  
---

## 🤝 Support & Community

### Get Help
- 📧 **Email**: andydandelion6@gmail.com
---

## 📜 License

MetaFast is licensed under the [MIT License](LICENSE).


---

## Credits

**Built with:**
- [Tauri](https://tauri.app/) - Desktop app framework
- [React](https://react.dev/) - UI framework
- [TypeScript](https://www.typescriptlang.org/) - Type safety
- [Rust](https://www.rust-lang.org/) - Backend performance
- [ExifTool](https://exiftool.org/) - Metadata manipulation
- [FFmpeg](https://ffmpeg.org/) - Video processing
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [shadcn/ui](https://ui.shadcn.com/) - UI components

**AI Providers:**
- [Google Gemini API](https://ai.google.dev/)
- [OpenAI API](https://platform.openai.com/)

---

## 📊 Stats & Achievements

- **1000+** Downloads
- **99.5%** Metadata Accuracy
- **90%** Time Saved vs Manual Input

---

## ⚖️ Disclaimer

MetaFast adalah tool untuk **mempercepat workflow** kontributor stock photography. User tetap bertanggung jawab untuk:
- Memastikan content original dan tidak melanggar copyright
- Review metadata sebelum upload ke platform
- Comply dengan terms of service setiap platform

MetaFast developer **tidak bertanggung jawab** atas:
- Rejection dari platform stock photography
- Copyright infringement oleh user
- Biaya API dari AI providers

---

## 💖 Support Development

Jika MetaFast membantu workflow Anda, consider:
- ⭐ **Star** repository ini
- 🐛 Report bugs atau suggest features
- 📢 Share dengan fellow contributors
- ☕ [Buy me a coffee](https://buymeacoffee.com/metafast)

---

**Made with ❤️ by Stock Photography Contributors, for Contributors**
