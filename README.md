# **Camarines Norte Provincial Government College Education Assistance Program (CNPGCEAP) Management System. **

**(_Title could still change_) <mark>(Version 0.0.1) </mark>**

## Project Description

The **CNPGCEAP Management System** is a comprehensive web-based application developed to modernize and streamline the management of the Camarines Norte Provincial Government College Education Assistance Program.

Currently, the Community Affairs Office (CAO) manages educational assistance using manual, paper-based processes that are time-consuming, error-prone, and lack analytical capabilities. Staff members spend days or weeks manually encoding student information, then re-encode the same data when preparing payroll and disbursement documents.

---

## Features

- **AI-Powered OCR Technology** - Automatically extract student data (names, schools, municipalities) from PDF or paper documents provided by students
- **Bulk Data Upload & Processing** - Import and process thousands of scholar records simultaneously via Excel files
- **Intelligent Duplicate Detection** - Automatically identify and alert users about duplicate entries during data upload
- **Advanced Search & Filtering** - Search beneficiaries by name, school, municipality, barangay, district, or any demographic criteria
- **Real-Time Analytics Dashboard** - Visual insights and charts showing program distribution, beneficiary demographics, and trends
- **Centralized Scholar Database** - Single source of truth containing personal details, school information, and complete disbursement history
- **Automated Payroll Generation** - Generate payroll and disbursement documents directly from the database without manual re-encoding
- **Role-Based Access Control** - Three user levels (Viewer, Payroll Staff, Admin) with clearly defined permissions
- **Audit Trail & Login History** - Track all system activities, user logins, and data modifications for transparency and accountability
- **Customizable Report Generation** - Create detailed reports filtered by multiple criteria (municipality, school, date range, etc.)
- **Data Export Functionality** - Export scholar data and reports to Excel, PDF, or CSV formats

---

## Installation Steps (\*_No live codebase yet, so let's just pretend_)

### Prerequisites

Before installing, ensure you have the following software installed:

```
- Composer
- PHP 7.4 or higher
- MySQL 8.0 or higher
- MySQL Workbench 8.0 or higher
- Node.js 14.x or higher (optional, if using Node.js as backend)
```

### Installation Instructions

1. **Clone the repository from GitHub**

```bash
   git clone https://github.com/kaiserkrow/example-code-base-ths101.git
   cd example-code-base-ths101
```

2. **Install PHP dependencies using Composer**

```bash
   composer install
```

3. **Create and configure the environment file**

```bash
   cp .env.example .env
```

Then edit the `.env` file and add your database credentials:

```
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=cnepghseap_db
   DB_USERNAME=your_username
   DB_PASSWORD=your_password
```

4. **Note to self: Update step 4 if resources are available**

```bash
"
   We dont have any more ideas after this for our installation steps. (so let's pretend that the web app is installed).
   No available installation guides, because the system is still in progress. Thanks.
"
```

---

## Screenshot

## **While there's no screenshots available, enjoy a picture of the main developer's cat as a placeholder :smiley_cat:**

## ![image](docs/img/placeholder.jpg)

_Screenshot: She's the main developer's partner in crime. Her name is Kremy, a splendid feline with a hint of spiciness._

**Academic Context:**  
This project is developed as part of the THS 101 (Thesis Writing 101) coursework by 4th-year Computer Science students at Mabini Colleges, Inc., in partnership with the Community Affairs Office of the Provincial Government of Camarines Norte.
