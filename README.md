# Smart Expense & Billing Manager (with AI)

A full-stack application to manage personal and client-based expenses with invoicing, reporting, and integrated AI features (GPT-powered invoice summaries & insights).

## 🚀 Tech Stack

- **Frontend:** Angular 16+, Angular Material, Chart.js
- **Backend:** .NET Core 6+, Entity Framework, MySQL
- **AI Integration:** OpenAI GPT-3.5 API
- **Deployment:** Vercel (Frontend), Render/Azure (Backend)

## ✨ Features (Planned)

- ✅ User Authentication (JWT)
- ✅ Expense Tracking by Category/Month
- ✅ Client Management
- ✅ Invoice Generator (PDF)
- ✅ AI-Powered Invoice Summarizer
- ✅ Dashboard with Charts & Insights
- ✅ AI Expense Analyzer (GPT)

## 📅 Timeline

5 Weeks total → Aug 2025  
- Week 1: Setup + Auth  
- Week 2: Expense CRUD  
- Week 3: Client + Invoicing + AI  
- Week 4: Charts, PDFs  
- Week 5: Final polish & deployment

## 📁 Project Structure

- `/client`: Angular frontend  
- `/server`: .NET backend API  
- `/README.md`: This file  

## 👨‍💻 Author

CK — Full-stack developer | C#, Angular, MySQL  
[LinkedIn](#) | [GitHub](https://github.com/yourusername)

## Installations

- ng new WebApp --routing --style=scss
- npm install -g @angular/cli
- ng add @angular/material
- npm install @angular/forms
- npm install chart.js ng2-charts
- npm install jspdf jspdf-autotable
- npm install axios
- npm install openai

- dotnet new webapi -n WebApi
- dotnet add package Microsoft.EntityFrameworkCore.SqlServer
- dotnet add package Microsoft.EntityFrameworkCore.Tools
- dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
- dotnet add package Microsoft.AspNetCore.Cors
- dotnet add package Microsoft.AspNetCore.Mvc.NewtonsoftJson
- dotnet add package OpenAI
