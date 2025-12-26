# 🌐 Trans Fund

**Trans Fund** is a simple and intuitive web platform that allows users to donate and support projects securely using Razorpay. It helps creators and causes raise funds in a transparent and efficient way.

🔗 **Live App:** https://trans-fund-nine.vercel.app/

---

## 🚀 Features

- 💸 Secure payments with Razorpay  
- 🧾 Donate to projects easily  
- ⚡ Real-time order creation using Edge Functions  
- 🎨 Clean and responsive UI  
- 🌍 Deployed on Vercel with Supabase backend  

---

## 🧠 How It Works

1. User enters donation amount and selects a project.
2. Frontend calls Supabase Edge Function.
3. Edge Function creates a Razorpay order.
4. Order details are sent back to frontend.
5. User completes payment via Razorpay Checkout.

---

## 🧩 Tech Stack

- **Frontend:** React / Next.js  
- **Backend:** Supabase Edge Functions (Deno)  
- **Payments:** Razorpay  
- **Hosting:** Vercel & Supabase  
- **Language:** JavaScript / TypeScript  

---

## 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/trans-fund.git
cd trans-fund
