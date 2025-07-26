# BrandGenie Project Overview

**Stack:**  
- **Frontend:** React, TailwindCSS  
- **Branding Logic:** GPT-4  
- **Logo Generation:** DALL·E or Looka API  
- **Auth & Storage:** Supabase  

---

## 1. User Input Form
Collects:
- **Business Name**
- **Keywords** (e.g., eco-friendly, modern, tech)
- **Target Audience**
- **Industry**

---

## 2. Branding Generation (via GPT-4)
Generates:
- **Brand Story:** 1–2 paragraph narrative
- **Slogan & Tagline**
- **Ideal Customer Persona**
- **3 Brand Values**
- **Suggested Tone:** (playful, luxury, professional, etc.)

---

## 3. Logo & Visual Identity (via Logo/Image API)
- **2–3 Logo Concepts**
- **Color Palette:** Hex codes
- **Font Pairings:** Google Fonts

---

## 4. Live Brand Kit Preview (React)
- **Style Tile:** Colors, logos, fonts, sample usage
- **Download Button:** Export ZIP (PDF + images)

---

## 5. Project Storage (Supabase)
- Store all projects per user login

---

## 6. Shareable Link Feature
- Share for collaborator review

---

## Monetization
- **Free:** Watermarked assets
- **Paid:** HD assets, commercial rights, editable docs

---

**Next Steps:**  
- Set up React project structure  
- Integrate Supabase for auth/storage  
- Build input form and connect to GPT-4  
- Integrate logo/image API  
- Implement brand kit preview and export  
- Add sharing and monetization logic
