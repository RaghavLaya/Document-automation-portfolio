# Document-automation-portfolio
AI-powered document automation projects using Amazon Q Developer
AI-powered document automation projects built using **Amazon Q Developer** and **Python**.

## 🎯 Overview

This repository showcases automation workflows that transformed manual documentation processes into efficient, repeatable pipelines — reducing cycle time by **90%**.

## 📂 Projects

### 1. Sprint Report Automation

**Problem:** Manual formatting, data extraction, and template population of sprint reports took 4+ hours per cycle.

**Solution:** Built a 3-step Python pipeline automated via Amazon Q Developer:
- `format_report.py` — Auto-detect structure, apply styling, merge headers
- `extract_data.py` — Extract tabular data and populate sprint templates
- `add_missing.py` — Map untracked tickets using requirements traceability matrix

**Result:** Reduced effort from 4+ hours to under 20 minutes (90% reduction).

**Tech:** Python, python-docx, Amazon Q Developer agents, CSV processing

---

### 2. Confluence-to-DITA XML Converter

**Problem:** Manual conversion of 125+ Confluence chapters to DITA XML for enterprise CMS publishing.

**Solution:** Built HTML-based conversion tools with sprint filtering:
- Export Confluence pages to structured XML
- Convert to DITA topics with content filtering
- Sprint-based generation (only affected chapters)
- Import into IXIASOFT CCMS for publishing

**Result:** Incremental updates without manual intervention. Full generation of 125+ chapters automated.

**Tech:** HTML/JavaScript, DITA XML, Confluence API, IXIASOFT CCMS

---

### 3. Jira-Document Synchronization

**Problem:** Manual lookup of Jira tickets to update documentation with latest defect status.

**Solution:** Built Jira REST API integration:
- Extract ticket IDs from Word documents
- Fetch real-time data from Jira
- Compare and display changes (old vs new)
- Update documents only after user confirmation

**Result:** Eliminated manual Jira lookup; real-time sync with change detection.

**Tech:** Python, Jira REST API, python-docx, PAT authentication

---

## 🛠️ Technologies Used

- **AI Assistant:** Amazon Q Developer (custom agent prompts)
- **Language:** Python 3.x
- **Libraries:** python-docx, requests, pdfplumber, pypdfium2
- **APIs:** Jira REST API, Confluence API
- **Formats:** DOCX, DITA XML, CSV, JSON, HTML
- **CMS:** IXIASOFT CCMS
- **Methodology:** Docs-as-Code, Agile

## 📄 License

MIT License

## 📫 Contact

- LinkedIn: [Raghavendra Reddy](https://linkedin.com/in/raghavendra-reddy-10647a3b/)
- Email: raghupagireddy@gmail.com
