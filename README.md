---

# 📊 CSV Tools by Jose 

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/xraisen/csv-tools/main.yml?style=for-the-badge)  
![Latest Release](https://img.shields.io/github/v/release/xraisen/csv-tools?style=for-the-badge)  
![Platforms](https://img.shields.io/badge/platforms-Windows%20|%20macOS%20-lightgrey?style=for-the-badge)  
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)  

A **professional CSV processing suite** with an intuitive GUI—designed for **fast, efficient** CSV handling on Windows, and macOS.

---

## ✨ Features  

### 🔧 CSV Processor (email/phone)
![CSV Processor](https://github.com/xraisen/CSV-Tools/blob/main/screenshots/Screenshot_1.png)

- **Smart deduplication** – merge rows while retaining unique values  
- **Multiple output modes** – combine (comma-separated) or split (multi-row)  
- **Auto-detects** email/phone columns  
- **Drag-and-drop** column selection & reordering  
- **Batch processing** for multiple files  

### ✂️ CSV Splitter  
![CSV Splitter](https://github.com/xraisen/CSV-Tools/blob/main/screenshots/Screenshot_2.png)

- **Flexible splitting** – by row count or file size  
- **Real-time progress tracking**  
- **Auto-organized output folders** with timestamps  
- **Retains headers** in split files  

### 🤖 CSV Search + AI (Gemini)
![CSV Search + AI (Gemini)](https://github.com/xraisen/CSV-Tools/blob/main/screenshots/Screenshot_3.png)

- **Advanced Search** – search large CSV files efficiently with chunk-based processing  
- **Integrated AI Analysis** – leverages Gemini models to analyze and manipulate search results  
- **Dynamic Data Manipulation** – supports sorting, filtering, deduplication, grouping, and counting based on AI instructions  
- **User-friendly Web Interface** – combines a modern UI with AI-driven insights for seamless CSV data exploration  

This tool is built as **csvsearchai.py** and is included in the overall CSV Tools suite.

---

## 🚀 Get Started  

### 📥 Installation  

#### Direct Downloads CSV Processor 
[![Windows](https://img.shields.io/badge/Windows-EXE-blue?logo=windows&style=for-the-badge)](https://github.com/xraisen/CSV-Tools/releases/download/release/csvprocessor.exe)  
[![macOS](https://img.shields.io/badge/macOS-DMG-silver?logo=apple&style=for-the-badge)](https://github.com/xraisen/CSV-Tools/releases/download/release/csvprocessor)  

#### Direct Downloads CSV Splitter
[![Windows](https://img.shields.io/badge/Windows-EXE-blue?logo=windows&style=for-the-badge)](https://github.com/xraisen/CSV-Tools/releases/download/release/csvsplitter.exe)  
[![macOS](https://img.shields.io/badge/macOS-DMG-silver?logo=apple&style=for-the-badge)](https://github.com/xraisen/CSV-Tools/releases/download/release/csvsplitter)  

#### Package Managers  
```powershell
# Windows (Chocolatey)
choco install csv-tools

# macOS (Homebrew)
brew tap xraisen/tools && brew install csv-tools
```  

---

## 🖥️ How to Use  

### CSV Processor  
1. **Import** CSV file(s)  
2. **Select** target columns (email, phone, or custom)  
3. **Configure**: deduplication, output format, file naming  
4. **Run** & monitor progress  
5. **Export** processed files  

### CSV Splitter  
1. **Load** large CSV  
2. **Choose** split method: by rows or size  
3. **Set** output preferences  
4. **Execute** & track progress  

### CSV Search + AI (Gemini)  
1. **Upload** a CSV file and select the search column  
2. **Perform** a search using keywords across the CSV data  
3. **Analyze** search results with integrated AI powered by Gemini models  
4. **Manipulate** data dynamically (sort, filter, deduplicate, group, or count) based on AI suggestions  
5. **Export** the modified data or continue exploring via the web interface  

---

## 🛠️ Developer Guide  

### Requirements  
- Python 3.11+  
- pipenv (recommended)  

### Setup  
```bash
git clone https://github.com/xraisen/csv-tools.git
cd csv-tools
pipenv install --dev
pipenv shell
```  

### Build System  
```bash
# Development build
python build.py --dev

# Production build
python build.py --release --sign

# Platform-specific
python build.py --platform=win,mac
```  

---

## 🤝 Contributing  

We welcome contributions!

1. Review our [Contribution Guidelines](CONTRIBUTING.md)  
2. Fork the repository  
3. Create a feature branch (`git checkout -b feature/your-feature`)  
4. Commit changes (`git commit -am 'Add feature'`)  
5. Push to branch (`git push origin feature/your-feature`)  
6. Open a Pull Request  

For major changes, please open an issue first.

---

## 📜 License  

Distributed under the **MIT License**. See `LICENSE` for details.

---

## 📬 Contact  

**xRaisen** - xraisen@gmail.com  

### Resources  
- [GitHub Repo](https://github.com/xraisen/csv-tools)  
- [Issue Tracker](https://github.com/xraisen/csv-tools/issues)  
- [Documentation](https://github.com/xraisen/csv-tools/wiki)  
- [Changelog](https://github.com/xraisen/csv-tools/releases)  

---

### 🔥 Changes & Improvements  
- **More concise, action-oriented descriptions**  
- **Enhanced readability & flow**  
- **Streamlined installation steps**  
- **Clearer project structure**  
- **Polished formatting & spacing**  
- **New CSV Search + AI (Gemini)**: Enhanced search capabilities and integrated AI analysis for dynamic CSV manipulation

---

Feel free to reach out if you have any questions or need further assistance. Enjoy using CSV Tools by Jose!