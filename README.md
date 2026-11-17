 Oracle Procure-to-Pay (Accounts Payable) Prototype

A small Procure-to-Pay prototype built to practice Oracle database and
application skills alongside business analysis and ERP documentation.

 Business problem
Many small teams handle supplier invoices by email and spreadsheets. This
causes duplicate payments, slow approvals, and no clear view of what is owed.

 What the system does
- Stores suppliers, purchase orders, invoices, and payments
- Lets an AP Clerk enter invoices against a purchase order
- Lets an AP Manager approve or reject invoices
- Posts approved invoices to a simple general ledger
- Provides reports such as overdue invoices and spend by supplier

 User roles
- AP Clerk: enters and tracks invoices
- AP Manager: reviews and approves or rejects invoices
- Finance Controller: reviews reports and GL postings

Tech stack (planned)
Oracle Autonomous Database, SQL and PL/SQL, Oracle APEX, REST (ORDS),
Python, Git

Project structure
- docs/ requirements, process maps, ER diagram, screenshots
- sql/ table scripts, sample data, PL/SQL, queries
- python/ sample data generator and REST client script
- test/ UAT test cases

