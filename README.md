# FiltrumTAXInvoice

![Filtrum Logo](https://www.filtrum.co.in/images/logo.png)  
*My First-Ever Commercial Software Project — Built Single-Handedly*

---

## About This Project

**FiltrumTAXInvoice** is a **complete Invoice Management and Purchase Order System** developed for **[Filtrum Tools & Components Pvt. Ltd.](https://www.filtrum.co.in/)** — a leading manufacturer of automotive and industrial filters based in India.

> **This was my very first commercial project.**  
> I built it **100% single-handedly**, from database design to deployment.

It was the **seed** that grew my confidence in building **enterprise-grade applications** on my own.

---

## Client
**Filtrum Tools & Components Pvt. Ltd.**  
Website: [https://www.filtrum.co.in](https://www.filtrum.co.in)  
Industry: Automotive & Industrial Filters Manufacturing

---

## Tech Stack

| Layer             | Technology Used               |
|-------------------|-------------------------------|
| **Frontend**      | ASP.NET Web Forms (C#)        |
| **Backend**       | C#, ADO.NET                   |
| **Database**      | Microsoft SQL Server          |
| **Architecture**  | 3-Tier (UI → BAL → DAL)       |
| **Reporting**     | ASPX Print Reports (Multi-page) |

---

## Key Features

- **Customer Management**  
- **Purchase Order (PO) Creation & Management**  
- **Smart PO-to-Invoice Linking** (Select items from PO)  
- **Dynamic Tax Calculation**  
  - Excise Duty  
  - Cess, E-Cess, SH-Cess  
  - VAT / CST (Per customer)  
- **Auto Serial Number Generation**  
  - Domestic: `0001`, `0002`...  
  - Foreign: `F001`, `F002`...  
- **Amount in Words** (Rupees & Paise)  
- **Print-Ready Invoices**  
  - 1-page (≤4 items)  
  - 2-page (5–8 items)  
- **Grid-based Item Selection** with editable quantity & rate  
- **Session-based Multi-page Printing**  
- **Invoice History & Audit Trail**

---


---

## How It Works

1. Select **Customer** → Auto-fill address, taxes, ECC  
2. Select **PO** → Loads items in grid  
3. **Check items** → Max 8 per invoice  
4. Click **"Total"** → Calculate net, duties, VAT  
5. **Save** → Generate unique invoice number  
6. **Print** → Redirect to formatted report  

---

## My Journey

- Built **solo** with no team  
- First time handling **real tax rules**  
- Learned **enterprise patterns** from scratch  
- Delivered **production-ready software**  
- **First paid project** → Career-defining moment  

---

## Setup (Legacy System)

> Requires: Windows, IIS, SQL Server, Visual Studio

```bash
1. Restore SQL database
2. Update connection string in web.config
3. Open in Visual Studio
4. Run InvoiceManagement.aspx



---

### Steps to Use:
1. **Download** the file from the link above  
2. Place it in your project root  
3. Commit & push to GitHub

Your repo will look **professional and heartfelt** — perfect for showcasing your journey!
