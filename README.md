# POC – ReactJS PDF Marking

## About
This project is a **Proof of Concept (POC)** built using **ReactJS** that allows users to **interact with PDF documents** directly in the browser.

Users can:
- Add **questions** on specific PDF pages
- **Highlight** text or areas
- Add **signatures**
- Mark and annotate PDF pages visually

This POC demonstrates client-side PDF rendering and annotation capabilities for future document review and approval workflows.

---

## Tech Stack
- **ReactJS** – Frontend framework
- **PDF.js / react-pdf** – PDF rendering
- **Bootstrap / CSS** – UI styling
- **JavaScript (ES6+)**
- **HTML Canvas / SVG** – Annotations & markings

---

## Features
- Upload and view PDF files
- Navigate between PDF pages
- Highlight text or selected areas
- Add questions/comments to a specific page
- Draw or place a signature
- Visual markers saved per page
- Browser-based (no server-side PDF processing)

---

## Use Cases
- Document review & approval
- Legal or contract annotation
- Educational PDF question marking
- Real estate or financial document validation
- Internal review workflows

---

## Project Structure (Typical)


---

## How It Works

1. User uploads or opens a PDF file
2. PDF is rendered in the browser using **PDF.js**
3. User selects an action:
   - Highlight
   - Add Question
   - Sign
4. Annotation is drawn using **Canvas/SVG overlays**
5. All markings are mapped to:
   - Page number
   - Coordinates
   - Annotation type

> This POC focuses on **UI interaction and annotation logic**, not permanent PDF modification.

---

