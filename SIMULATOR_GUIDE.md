# 📊 Fraud Trading Simulator — Panduan Edukasi

> ⚠️ **SIMULASI EDUKASI - BUKAN DATA REAL** ⚠️
> 
> Tool ini dibuat untuk menunjukkan bagaimana oknum membuat video trading palsu. Tujuannya adalah edukasi pemula agar tidak tertipu oleh scam trading.

---

## 🎯 Apa Itu Simulator Ini?

Simulator ini mendemonstrasikan **bagaimana video trading palsu dibuat**. Dengan tool ini, Anda bisa:

1. ✅ Membuat siklus trading berulang yang terlihat "konsisten profit"
2. ✅ Mengatur pergerakan price yang dinamis dari open → close
3. ✅ Menampilkan floating PnL yang berfluktuasi
4. ✅ Kalkulasi otomatis dengan leverage unlimited (yang mustahil di broker real)
5. ✅ Mengkonfigurasi tampilan (font, warna, ticker)

**Dengan watermark permanent** yang tidak bisa dihapus: **"SIMULASI EDUKASI - BUKAN DATA REAL"**

---

## 🚀 Cara Menggunakan

### 1. **Buka Simulator**
```
Open file: simulator.html di browser
```

### 2. **Konfigurasi Ticker**
- Default: `XAUUSD`
- Ubah sesuai kebutuhan

### 3. **Tambah Siklus**
- Tetapkan jumlah siklus (1-10)
- Klik **"+ TAMBAH SIKLUS"**

### 4. **Isi Detail Setiap Siklus**

**Contoh: Open di 4.000.000 → Close di 4.005.000**

| Field | Nilai | Keterangan |
|-------|-------|-----------|
| Tipe Order | BUY | Atau SELL untuk short |
| Total Layer | 1 | Jumlah entry berbeda |
| Total Lot | 0.01 | Ukuran lot per layer |
| Open Price | 4000000 | Harga entry |
| Close Price | 4005000 | Harga target close |
| Durasi | 10 | Berapa lama animasi (detik) |

### 5. **Konfigurasi Font (Opsional)**
- Ukuran Font
- Ketebalan (100-900)
- Warna Teks
- Warna Profit (hijau)
- Warna Loss (merah)

### 6. **Jalankan Simulasi**
- Klik **"MULAI SIMULASI"**
- Lihat price bergerak dinamis dari open → close
- Floating PnL terupdate real-time

### 7. **Kontrol**
- **PAUSE** — hentikan sementara
- **RESUME** — lanjutkan
- **RESET** — mulai dari awal

---

## 📌 Fitur Utama

### ✨ Animasi Price Dinamis
Price tidak langsung loncat dari open ke close. Sebaliknya:
- Bergerak smooth dengan easing
- Ada random fluctuation (noise market-like)
- Terlihat organik seperti market real

### 💰 PnL Calculation
```
PnL = (Current Price - Open Price) × Lot × Layer × Direction

Untuk BUY:  PnL = (Current - Open) × Lot × Layer
Untuk SELL: PnL = (Open - Current) × Lot × Layer
```

Leverage: **Unlimited** (simulasi saja)
- Margin Bebas tidak dikurangi
- Ini menunjukkan **red flag** scammer

### 📊 Stats Real-Time
- **Total PnL** — profit/loss kumulatif
- **Equity** — total akun balance
- **Margin Bebas** — tersisa

### 🎨 Customizable UI
Ubah tampilan sesuai selera:
- Font size, weight
- Warna teks, profit, loss
- Watermark tidak bisa dihapus

---

## 🚨 Red Flags yang Ditunjukkan

Tool ini mendemonstrasikan **ciri-ciri video scam**:

| Red Flag | Mengapa Mustahil |
|----------|-----------------|
| **Leverage unlimited** | Broker regulated max 1:125 |
| **Selalu close profit** | Market tidak selalu profit |
| **Pattern berulang** | Setup real tidak 100% sama |
| **Floating loss lalu close profit** | Itu gambling, bukan trading |
| **No drawdown** | Equity curve selalu naik |
| **No slippage** | Entry/exit perfect selalu |

---

## 📸 Contoh Penggunaan

### Skenario 1: Sniper Bot Palsu
```
Siklus 1:
- Tipe: BUY
- Layer: 1, Lot: 0.01
- Open: 2000, Close: 2050 (+2.5%)
- Durasi: 8 detik
→ Result: +50 USD

Siklus 2:
- Tipe: BUY
- Layer: 1, Lot: 0.01
- Open: 2050, Close: 2100 (+2.4%)
- Durasi: 8 detik
→ Result: +50 USD

Total: +100 USD dari 2 siklus
```

### Skenario 2: Fake Scaling
```
Siklus 1: 1L × 0.01 lot, +50 USD
Siklus 2: 2L × 0.02 lot, +100 USD (2× return)
Siklus 3: 4L × 0.04 lot, +200 USD (4× return)
→ Terlihat "exponential growth"
```

---

## ⚠️ Disclaimer

**Simulator ini hanya untuk edukasi!**

- ❌ Jangan dipakai untuk scam
- ❌ Jangan urus output sebagai "bukti profit real"
- ✅ Gunakan untuk tunjuk ke pemula bagaimana scam bekerja
- ✅ Gunakan untuk research & analisis

---

## 🔍 Cara Spot Video Trading Palsu (Setelah Lihat Simulator Ini)

1. **Cek leverage** — jika unlimited/terlalu tinggi = red flag
2. **Cek watermark** — jika bersih tanpa disclosure = suspicious
3. **Cek drawdown** — equity curve harus ada yang merah (loss)
4. **Cek entry point** — jika entry/exit perfect selalu = manipulation
5. **Verify di broker** — crosscheck dengan real time chart broker
6. **Check MyFXBook** — real trader verified track record di sini
7. **Hati-hati signal seller** — 90% adalah scam

---

## 💡 Tips untuk Pemula Trader

- 📊 Lihat simulator ini untuk mengerti **mekanisme scam**
- 📚 Fokus **risk management**, bukan profit besar
- 🏦 Trading di broker **regulated FCA/SEC/OJK**
- 📈 Target **2-5% konsisten per bulan**, bukan 100% sebulan
- 🛡️ **Jangan pakai leverage gila** (max 1:50 untuk pemula)
- ❌ **Hindari signal seller** — belajar analisa sendiri
- ✅ **Backtest sendiri** — jangan percaya orang lain

---

## 📞 Support

Pertanyaan? Silakan buka issue di repository.

---

**Created:** 2026-07-01  
**Purpose:** Educational Anti-Fraud Demonstration  
**Author:** IPISTORE Trading Education
