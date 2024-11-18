# Developer Resume

My professional resume maintained in JSON Resume format. This repository contains my current resume with automated export capabilities for different formats.

## 📄 Formats Available
- JSON (source format)
- PDF (generated)
- HTML (generated)

## 🛠 Technical Details
This resume is built using:
- [JSON Resume](https://jsonresume.org/), a JSON-based open source standard for resumes
- Node.js based tooling for validation and export
- Various JSON Resume themes for different styling options

## 🚀 Getting Started

### Prerequisites
- Node.js
- npm

### Installation
1. Clone the repository
```bash
git clone https://github.com/MrDando/resume.git
cd resume
```

2. Install dependencies
```bash
npm install
```

### Usage
To validate the JSON:
```bash
npx resume validate
```

To export to PDF:
```bash
npx resume export resume.pdf --theme elegant
```

To export to HTML:
```bash
npx resume export resume.html --theme elegant
```

## 📝 Maintaining

The resume data is stored in `resume.json`. To update the resume:
1. Modify `resume.json`
2. Validate changes using `npx resume validate`
3. Generate new exports using the commands above
4. Commit only the JSON file (PDF/HTML files are git-ignored)

## 🎨 Themes
Currently using the `elegant` theme. Other popular themes include:
- stackoverflow
- flat
- modern

To try a different theme:
```bash
npm install jsonresume-theme-[theme-name]
npx resume-cli export resume.pdf --theme [theme-name]
```

## 📬 Contact
Feel free to reach out if you have any questions:
- LinkedIn: [Danijel Stanić](https://linkedin.com/in/stanic-danijel)

## 📃 License
This project is open source and available under the [MIT License](LICENSE).