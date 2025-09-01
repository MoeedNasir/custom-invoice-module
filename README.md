# custom-invoice-module
a tailored invoicing system supporting dynamic billing workflows, improved financial tracking,  and PDF report generation. 

Custom Invoice Report (Odoo 18)
Overview

The Custom Invoice Report module extends Odoo’s invoicing functionality by introducing a tailored report layout with dynamic fields, improved styling, and multilingual support. It enhances financial reporting for clients and internal teams by providing more detailed, user-friendly, and professional PDF invoices.

Features:
Custom PDF Invoice Layout – Redesigned structure for clarity and professionalism.
Multi-language Support – Report translations for multiple languages.
Integrated with Accounting – Works seamlessly with Odoo’s native Invoicing/Accounting module.
Dynamic Fields – Auto-populates key fields such as customer details, payment terms, taxes, and totals.
Clean UI/UX – Improved formatting for better readability.

Module Structure:
custom_invoice_report/
│── __init__.py
│── __manifest__.py
│── report/
│   ├── custom_invoice_template.xml
│   └── custom_invoice_report.xml
│── views/
│   └── invoice_report_views.xml
│── static/
│   └── description/
│       └── icon.png

Installation:
Copy the module folder custom_invoice_report into your Odoo addons directory.
Restart the Odoo server:
./odoo-bin -c odoo.conf -d <your_database_name> -u custom_invoice_report
Activate Developer Mode in Odoo.
Update the app list and install Custom Invoice Report.


Usage:
Go to Invoicing → Customers → Invoices.
Open any confirmed invoice.
Click Print → Custom Invoice Report.
A professionally formatted invoice PDF will be generated.


Configuration:
Ensure that languages are installed in Odoo for translation support.
Modify the custom_invoice_template.xml if you want to adjust the report layout or add/remove fields.

Compatibility:
Odoo 18 Community & Enterprise
Python 3.10+
PostgreSQL 13+


Author:
Developed by Moeed Nasir
Role: Odoo Technical Developer
