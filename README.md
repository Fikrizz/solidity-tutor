# 📚 Solidity Tutor

> Belajar smart contract dari nol, gaya santai

Chat-based learning + 12 lessons + exercise generator. Buat developer Indonesia yang mau masuk Web3.

## ✨ Features

- 💬 Chat interactive sama AI tutor
- 📖 12 materi terkurasi (beginner → advanced)
- 🎯 Generate latihan: fill-in-blank / bug-fix / from-scratch / quiz
- 📝 Code examples siap copy ke Remix
- ⚡ Topik: ERC20, ERC721, Reentrancy, Gas Optimization, Upgradeable
- 🇮🇩 Bahasa Indonesia santai

## 🚀 Quick Deploy

### Option 1: Vercel (paling cepat)
1. Fork/clone repo ini
2. Connect ke [Vercel](https://vercel.com/new)
3. Deploy — done. URL hidup dalam 30 detik.

### Option 2: Drag & Drop
1. Download `index.html`
2. Drag ke [vercel.com/new](https://vercel.com/new) atau Netlify Drop
3. Live URL siap

### Option 3: Local
```bash
cd solidity-tutor
python3 -m http.server 8000
# buka http://localhost:8000
```

## 🔑 Pakai MiMo API Key (recommended)

1. Klik tombol **⚙ Settings** di header
2. Paste API key dari [api.xiaomimimo.com](https://api.xiaomimimo.com)
3. Pilih model — `mimo-v2.5-reasoning` lebih akurat, `mimo-v2.5` lebih cepat
4. **Test Connection** → **Save**

Tanpa API key, app fallback ke Pollinations free endpoint (terbatas, demo only).

## 🏗️ Stack

- **Frontend:** Single-file HTML, vanilla JS, zero dependencies
- **AI:** Xiaomi MiMo V2.5 (primary) → Pollinations (fallback)
- **Storage:** localStorage (settings only, no server)
- **Deploy:** Static file, kompatibel Vercel / Netlify / GitHub Pages / IPFS

## 📦 Built for

[**MiMo 100T Creator Program**](https://100t.xiaomimimo.com) — Xiaomi's developer incentive untuk app yang pakai MiMo AI.

## 📄 License

MIT — bebas fork, modify, gunakan komersial.

---

Made by [@Fikrizz](https://github.com/Fikrizz) · Powered by Xiaomi MiMo
