# 🇩🇪 German Tax Accounting Software

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=15,27,6&height=210&section=header&text=German%20Tax%20Accounting&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Steuererkl%C3%A4rung%2C%20Made%20Simple&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.8.0-1D1D1F?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Web%20%7C%20Desktop%20%7C%20CLI-D4AF37?style=for-the-badge&logo=linux&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-B8860B?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Compliance](https://img.shields.io/badge/compliance-ELSTER%20%7C%20DATEV-3D3D3D?style=for-the-badge&logo=accenture&logoColor=white)](https://www.elster.de)

<br/>

### 📊 A complete German tax accounting suite for freelancers, small businesses & tax advisors

*🧾 EÜR • 💶 USt-Voranmeldung • 📤 ELSTER Export • 🏦 DATEV Compatible*

<br/>

<a href="https://share.google/g8hnMlI7uABNbbWuX">
  <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-1D1D1F?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0D0D0F" alt="Live Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/g8hnMlI7uABNbbWuX">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-D4AF37?style=for-the-badge&logo=github&logoColor=black&labelColor=A88A2C" alt="Get Source" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/g8hnMlI7uABNbbWuX">
  <img src="https://img.shields.io/badge/📚_DOCS-B8860B?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=8C6709" alt="Docs" height="45"/>
</a>

</div>

<img width="1671" height="941" alt="1ea53bbf-96a4-413b-a02d-061b934262f5" src="https://github.com/user-attachments/assets/7fd4c820-0be8-4fe8-affa-a568d5352644" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**German Tax Accounting Software** is a **modern, open-source tax accounting solution** tailored to German regulations. It handles income-expense accounting (EÜR), VAT returns (Umsatzsteuer-Voranmeldung), and prepares data for **ELSTER** and **DATEV** — the two systems every German business interacts with.

Designed with compliance in mind, it supports the tax rules freelancers and small businesses actually need, without the bloat of enterprise software.


<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🧾 **EÜR** | 💶 **USt-VA** | 📤 **ELSTER Export** |
|:---:|:---:|:---:|
| Full income-expense<br/>accounting | Monthly & quarterly<br/>VAT returns | Ready-to-upload<br/>XML exports |

| 🏦 **DATEV** | 📊 **Reports** | 🔐 **Audit Trail** |
|:---:|:---:|:---:|
| CSV/DATEV-compatible<br/>bookkeeping exports | BWA, GuV &<br/>custom reports | Every change<br/>logged & traceable |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Software

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🇩🇪 **Germany-First Design** | Built around German tax law (AO, UStG, EStG) from day one |
| 🧾 **EÜR + USt-VA** | Both essential German tax workflows fully supported |
| 📤 **ELSTER & DATEV Ready** | Exports match the formats the Finanzamt and advisors expect |
| 🧠 **Smart Validation** | Flags missing receipts, mismatched VAT, and common filing mistakes |
| 🔐 **Audit-Safe** | Every entry is immutable once booked — proper Storno handling |
| 💾 **Portable & Local** | Runs fully offline — your tax data never leaves your machine |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 App Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🇩🇪  German Tax Accounting  v2.8.0              ║
╠══════════════════════════════════════════════════╣
║  Geschäftsjahr 2026     Zeitraum: Q1             ║
║  ──────────────────────────────────────────      ║
║  💼 EÜR Übersicht                                ║
║  Einnahmen:    42.750,00 €                       ║
║  Ausgaben:     18.320,45 €                       ║
║  Gewinn:       24.429,55 €                       ║
║                                                  ║
║  💶 USt-Voranmeldung (März)                      ║
║  Umsatz:       15.320,00 €  (19%)                ║
║  Vorsteuer:     2.845,00 €                       ║
║  Zahllast:        281,00 €                       ║
║                                                  ║
║  📤 Export                                        ║
║  [ ELSTER XML ]  [ DATEV CSV ]  [ PDF BWA ]      ║
║                                                  ║
║  ✅ Prüfung OK   🧾 148 Belege   🔐 Audit trail  ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🇩🇪 german-tax-accounting/
├── 🎯 src/
│   ├── accounting/            # EÜR & bookkeeping
│   │   ├── entries.py
│   │   └── storno.py
│   ├── vat/                   # USt-Voranmeldung
│   ├── exports/               # ELSTER & DATEV
│   │   ├── elster_xml.py
│   │   └── datev_csv.py
│   ├── reports/               # BWA, GuV, PDF
│   └── ui/                    # Desktop & web UI
├── 🧪 tests/                  # Tax-rule test suite
└── 📖 docs/                   # Setup, compliance & FAQ
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a tax rule that needs updating? Want to support a new export format?

<div align="center">

<a href="https://share.google/g8hnMlI7uABNbbWuX">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/g8hnMlI7uABNbbWuX">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-1D1D1F?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/g8hnMlI7uABNbbWuX">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-D4AF37?style=for-the-badge&logo=github&logoColor=black" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🇩🇪 Made with 📊 by the German Tax Software Team

*If this tool made your Steuererklärung easier — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=15,27,6&height=120&section=footer" width="100%"/>

</div>
