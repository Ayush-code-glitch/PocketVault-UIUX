# 🪙 PocketVault — Micro-Savings & Budgeting App for College Students

> **YuvaIntern UI/UX Internship Capstone Project**  
> **Designer:** Ayush Kapadia  
> **Domain:** FinTech / Micro-Savings & Expense Tracking  
> **Tools:** Figma, FigJam, UI Design Tokens, User Journey Mapping  

---

## 📌 Project Overview

College students often rely on fixed, irregular pocket money or stipends transferred via UPI. Traditional banking apps are cluttered with complex technical jargon, while conventional budgeting apps demand tedious manual logging, causing young users to abandon them within days.

**PocketVault** solves this with an intuitive, friction-free micro-savings mobile app. It converts spare UPI change into automated goal-driven savings vaults while giving students an instant, guilt-free look at what is safe to spend each day.

---

## 📱 Key Screens & Prototype Flow

### 1. Home Dashboard — "The Daily Compass"
* **"Safe-to-Spend Today" Card:** Replaces overwhelming total balance anxiety with a clear, dynamic daily spending allowance (`₹240`) to prevent mid-month burnouts[cite: 2, 4].
* **Active Vaults Carousel:** Visual progress tracking for real-life student goals (e.g., *Sony XM5*, *Goa Trip*)[cite: 2, 4].
* **Frictionless Expense Tagging:** Auto-detects UPI outflows and enables 1-tap category tagging[cite: 2, 4].



---

### 2. Goal Creation Modal — "3-Step Target Builder"
* **Target & Date Horizon:** Dynamic input fields with sensible preset amounts tailored to student budgets (`₹2,000`, `₹5,000`, `₹10,000`)[cite: 3, 5].
* **Dynamic Micro-Calculator:** Translates large lump sums into bite-sized daily figures (e.g., *"Save ₹45/day — about skipping one cold coffee every two days"*)[cite: 5].



---

### 3. Micro-Savings Rules Engine — "Automated Funding"
* **Spare-Change Roundups:** Automatically rounds UPI payments to the nearest ₹10 or ₹50 and routes the difference into the target vault[cite: 6].
* **Daily Pocket Drip:** Enables fixed recurring daily stashes (e.g., ₹20/day)[cite: 6].
* **Safety Guardrail:** Automatically pauses automated rules if account balance drops below ₹500[cite: 6].



---

### 4. Spending Analysis — "No-Guilt Analytics"
* **Categorical Donut Breakdown:** High-contrast color-coding for primary student expenses (Food & Canteen, College & Printouts, Outings, Transit)[cite: 3, 7].
* **Positive Trend Feedback:** Replaces anxiety-inducing red warning alerts with supportive behavioral nudges[cite: 3, 7].



---

## 🎨 Design System & Visual Tokens

| Token | Value / Spec | UX Rationale |
| :--- | :--- | :--- |
| **Primary Brand** | `#10B981` (Emerald Mint) | Friendly growth/wealth cue without corporate bank stuffiness |
| **Dark Surface** | `#0F172A` (Slate 900) | Gen-Z preferred dark-mode aesthetic with high text contrast |
| **Card Radii** | `16px` to `20px` | Tactile, modern card containers |
| **Typography** | `Inter` / `Plus Jakarta Sans` | High legibility for monetary numerical values |

---

## 🛠️ Step-by-Step UX Methodology

1. **User Research & Persona Building:** Studied allowance management friction among undergraduates receiving UPI pocket money.
2. **Information Architecture (IA):** Minimized click-depth to reach savings vaults and expense logs within 1–2 taps.
3. **Wireframing:** Low-fidelity grayscale layout testing focusing strictly on visual hierarchy before styling.
4. **Visual UI & Interactive Design:** Built consistent Figma component variants, dark-mode tokens, and micro-interactions.
5. **Testing & Validation:** Validated goal setup clarity and automated round-up comprehension across peer testers.

---

## 🚀 How to View & Evaluate

1. Clone or inspect this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/PocketVault-UIUX.git
