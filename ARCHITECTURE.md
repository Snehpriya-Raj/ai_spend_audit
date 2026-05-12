# AI Spend Audit - Architecture

## 🏗️ System Overview

AI Spend Audit is a frontend-heavy web application that analyzes AI tool expenses and stores data using Supabase.

---

## ⚙️ Tech Architecture

Frontend:
- HTML
- Tailwind CSS
- JavaScript

Backend:
- Supabase (Database + API)

Hosting:
- GitHub Pages / Vercel

---

## 🔄 Application Flow

1. User opens the application
2. Enters:
   - AI Tool name
   - Monthly spend
   - Team size
   - Use case
3. Clicks "Generate Audit"
4. JavaScript processes data:
   - Calculates savings
   - Generates recommendation
5. Result is displayed on UI
6. Data is stored in Supabase

---

## 🗄️ Database Structure (Supabase)

Table: audits

Fields:
- tool (string)
- spend (number)
- team_size (number)
- use_case (string)

---

## 📊 Data Flow Diagram

User Input → JavaScript Logic → UI Update → Supabase Database

---

## 🔐 Security

- API keys stored in frontend (basic demo level)
- Supabase handles authentication & data storage

---

## 🚀 Deployment

- Hosted on GitHub Pages / Vercel
- Static frontend with external backend (Supabase)

---

## 📌 Summary

This project demonstrates:
- Frontend development skills
- API integration (Supabase)
- Real-time UI updates
- SaaS-like architecture
