🧾 PDF Invoice Generator
A simple yet powerful desktop application built with Python and Tkinter to generate professional PDF invoices. Designed for freelancers, small businesses, and anyone who wants to skip the hassle of manual formatting.


🎯 Key Features
- GUI-based input for company and customer details
- Upload company logo for branded invoices
- Auto-generates structured PDF invoices using ReportLab
- Lightweight, fast, and easy to use
- Customizable layout and fields


🛠️ Tech Stack

COMPONENTS          |   DESCRIPTION

Python              |   Core programming language
Tkinter             |   GUI framework for desktop app
ReportLab           |   PDF generation library
OS & Filedialog     |   File browsing and path handling

📦 Installation
git clone https://github.com/amaan-dev/pdf-invoice-generator.git
cd pdf-invoice-generator
pip install reportlab


No external dependencies beyond ReportLab. Tkinter comes pre-installed with Python.

🚀 How to Run
python invoice_generator.py


A GUI window will open. Fill in your company and customer details, upload your logo, and click Submit Details to generate a PDF invoice.

📄 Output
- The invoice is saved as Invoice.pdf in the current directory.
- Includes company branding, customer info, item table, and signature field.

🧩 Customization Tips
- Modify layout and fonts in the generate_invoice() method
- Add more fields or dynamic item rows for advanced use
- Integrate with databases or CSVs for bulk invoice generation


💡 Why I Built This
As a creative freelancer, I wanted a quick way to generate clean, branded invoices without relying on bulky online tools. This project blends functionality with simplicity—and it's open-source so others can build on it too.
By the way I build it for my College Project.

📬 Contact
Made with 💻 by Amaan
For feedback, feature requests, or freelance inquiries: [amaan201803@outlook.com]

Want help adding screenshots, a GIF demo, or turning this into an executable .exe for Windows? I’ve got your back.
