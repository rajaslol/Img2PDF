# README

# Snap2PDF 📸

A client-side utility for converting image assets to PDF format using the browser as the execution engine.

### Engineering Overview

Snap2PDF performs image processing and document assembly entirely within the client runtime. By leveraging the **jsPDF** library and native browser APIs, the application eliminates server-side dependencies and ensures data sovereignty by preventing file transmission to external infrastructure.

### Installation

Snap2PDF is a static, local-first application. No server-side runtime or package manager is required. 

```bash
# Clone the repository
git clone [https://github.com/rajaslol/snap2pdf.git](https://github.com/rajaslol/snap2pdf.git)

# Navigate to the directory
cd snap2pdf

# Launch the application
# Simply open index.html in your preferred web browser:
open index.html
