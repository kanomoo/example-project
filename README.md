# Academic & Software Engineering Projects Repository

A comprehensive repository consolidating academic project reports, pitching presentation decks, automated document generation scripts, and practical software engineering coursework.

---

## 📂 Repository Structure

```text
├── KMUTNB_Academic_Project_Dataset/     # Standard Academic Theses & Project Reference Dataset
│   ├── 01_Official_Guidelines_and_Templates/
│   ├── 02_Full_Theses_Thai/
│   ├── 03_Full_Theses_English/
│   ├── 04_Senior_Projects_and_Previous_Cohorts/
│   └── DATASET_INDEX.md
├── Project_Smart_Queue_Food/            # Smart Queue Food Management System
│   ├── assets/                          # Technical diagrams, BMC graphics, architecture diagrams, UI mockups
│   ├── scripts/                         # Python automation scripts for report and presentation generation
│   ├── รายงานโครงงาน_Smart_Queue_Food_ฉบับสมบูรณ์.docx
│   ├── รายงานโครงงาน_Smart_Queue_Food_ฉบับสมบูรณ์.pdf
│   ├── สไลด์นำเสนอ_Smart_Queue_Food_Pitching.pptx
│   └── สไลด์นำเสนอ_Smart_Queue_Food_Pitching.pdf
├── ComPro/                              # Computer Programming coursework & TCAS project documentation
├── Design_Thinking/                     # Design Thinking projects (AEROSEED Kinetic Tyre Dust Air Purifier)
├── FunIT_เว็บไซต์/                       # WordPress web development projects (Sports Club, Animal Lovers Club)
├── การพัฒนาสื่อการสอน/                    # Instructional Media Development reports (Chapters 1–5, Appendices A–G)
├── โครงการปี2_ลอยกระทงและวิจัย/           # Year 2 Project Reports, Loy Krathong event research, & vocational club plans
├── จิตวิทยา/                             # Psychology course project reports and survey questionnaires
├── ตัวอย่างรายงาน/                       # Standard thesis and academic report templates for reference
└── ระบบเช็คชื่อสแกนใบหน้า/               # Face Recognition Attendance System (Full report Chapters 1–5, Appendices)
```

---

## 🚀 Featured Projects & Datasets

### 1. KMUTNB Academic Project & Thesis Dataset
A comprehensive benchmark dataset comprising official KMUTNB thesis writing manuals, certification and progress evaluation templates (DOCX/PDF), and complete 5-chapter master's and doctoral theses in Thai and English. Specially curated as an empirical dataset for academic formatting skills (`academic-project-report`).

### 2. Smart Queue Food (Intelligent Queue & Order Management System)
An automated queue management and food ordering platform designed for cafeteria and food court environments to minimize customer waiting times, optimize vendor workflows, and improve service efficiency.
- **Documentation & Pitch Deck**: Comprehensive academic report and professional pitching presentation deck adhering strictly to KMUTNB project and thesis standards.
- **Automated Document Generation (`scripts/`)**:
  - `build_report.py`: Automated DOCX report compilation engine enforcing KMUTNB margins, typography, two-pass dynamic table of contents, and APA-compliant tables.
  - `build_presentation.py`: Automated PPTX slide generator delivering high-impact pitch decks.
  - `generate_graphics.py`: Programmatic generation and rendering of technical diagrams (System Architecture, Business Model Canvas, Positioning Map, and Risk Matrix).

### 3. Face Recognition Attendance System
An automated classroom attendance monitoring system leveraging computer vision and facial recognition. Includes complete academic documentation covering project proposals, Chapters 1 through 5, and full appendices.

### 4. Design Thinking: AEROSEED Kinetic Tyre Dust Air Purifier
An eco-innovative air purification system utilizing vehicle kinetic energy to capture and filter fine tyre particulate matter, developed using Human-Centered Design Thinking methodologies to tackle urban air pollution.

---

## 🛠️ Technical Configuration & Environment

- **Git Configuration**:
  - Configured `core.quotepath = false` to ensure Unicode/Thai filenames are accurately preserved and displayed across Git interfaces.
  - Configured `.gitattributes` to handle binary assets (`.pdf`, `.docx`, `.pptx`, image files) properly, eliminating extraneous diffs and preserving file integrity.
  - Configured `.gitignore` to prevent tracking of OS metadata (`.DS_Store`, `Thumbs.db`), Python bytecode caches (`__pycache__`), and temporary Microsoft Office lock files (`~$*`).

