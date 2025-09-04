# Financial Dashboard (Next.js Prototype)

This project is a **prototype** financial dashboard built with **Next.js 14 (App Router)**, **Tailwind CSS**, and **MUI X Charts**.  
It was created as part of an assignment to recreate a blurred reference design and includes key features such as charts, stat cards, and PDF report generation.

---

## Features
- Top Navigation Bar with multiple menu items and icons.  
- **AUM** and **SIP** main cards with values, MoM % change, and “View Report” buttons.  
- **Time Range Filter Bar** (3 Days, 7 Days, 10 Days, 30 Days).  
- **Stat Cards**: Purchases, Redemptions, Rejected Transactions, SIP Rejections, New SIP.  
- Charts:
  - Clients Bubble Chart  
  - SIP Business (bar + line) Chart  
  - Monthly MIS Multi-Line Chart  
- **Download PDF Report** – one-click export of the dashboard view.  
- **Mock API Endpoint** using Next.js API routes (`/app/api/dashboard/route.ts`).  
- Responsive layout (desktop, tablet, and mobile).  

---

## Tech Stack
- [Next.js 14 (App Router)](https://nextjs.org/)  
- [Tailwind CSS](https://tailwindcss.com/)  
- [MUI X Charts](https://mui.com/x/react-charts/)  
- [html2canvas](https://www.npmjs.com/package/html2canvas) & [jsPDF](https://www.npmjs.com/package/jspdf) for PDF generation  

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd financial-dashboard
    ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open the app in your browser:

   ```
   http://localhost:3000
   ```

---

## 📱 Mobile App Build (Prototype)

This project can also be converted into an **Android/iOS app** using **Capacitor**.
(Currently only the web version has been implemented.)

---

## Notes

* This is **only a prototype** and can be extended or modified for production use.
* The **layout and components are not an exact replica** of the provided blurred image, but are designed to be **similar and functional**.
* Development time: ⏱ **\~4–5 hours**.
* Dark mode toggle is scaffolded but not yet functional.

---

## 📷 Screenshot

<img width="1919" height="1079" alt="Screenshot 2025-09-04 134850" src="https://github.com/user-attachments/assets/58178fd4-ae78-4f0e-8db0-73ea976112cd" />


---
