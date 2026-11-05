<div align="center">

# ◧ CSV Lens

**Drop a CSV and instantly get a clean, sortable, searchable table and an automatic chart — 100% in your browser.**

[**→ Live demo**](https://unitenist.github.io/csv-lens/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![No backend](https://img.shields.io/badge/backend-none-17916b)
![License](https://img.shields.io/badge/License-MIT-green)

⭐ If this saved you a few minutes, a star is appreciated!

</div>

---

## Why

Sometimes you just want to *look* at a CSV — sort it, search it, see a quick chart — without importing it into a spreadsheet or uploading it to some random website. CSV Lens does exactly that, and it never sends your data anywhere: all parsing happens in your browser.

## ✨ Features

- 📂 **Drag & drop** a `.csv` (or click to browse, or try the built-in sample)
- 🔎 **Sortable & searchable** table with sticky headers
- 📊 **Automatic chart** — bar, line or pie; pick the label and value columns
- 🧠 **Smart column typing** — numeric columns are detected and right-aligned
- ⬇️ **Export** the (filtered) data as JSON
- 🌓 **Light / dark theme**
- 🔒 **Private by design** — no upload, no sign-up, no backend

## 🚀 Usage

Just open the [live demo](https://unitenist.github.io/csv-lens/) and drop a file in.

To run it locally, no build step is needed — it is a single HTML file:

```bash
git clone https://github.com/unitenist/csv-lens.git
cd csv-lens
# open index.html in your browser, or serve it:
python3 -m http.server 8000   # then visit http://localhost:8000
```

## 🧱 Built with

- Vanilla JavaScript (no framework)
- [PapaParse](https://www.papaparse.com/) for CSV parsing
- [Chart.js](https://www.chartjs.org/) for charts

## 🤝 Contributing

Issues and pull requests are welcome — ideas for new chart types, better type detection, or UI polish are all appreciated.

## 📄 License

MIT — see [LICENSE](LICENSE).
