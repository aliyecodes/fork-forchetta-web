#  🇬🇧 Fork & Forchetta – Frontend

This is the frontend of the Fork & Forchetta recipe manager.
A lightweight and responsive web app built with HTML, CSS (Bootstrap/Bootswatch), and Vanilla JavaScript.
It communicates with the backend API (Node.js + Express + MongoDB + Cloudinary) hosted on Render.

---
## 📌 Portfolio Note  

For this project, I chose **MongoDB** as the database because it provides flexible document storage, making it ideal for recipes with variable fields (e.g., ingredients, instructions, optional images). For media storage, I used **Cloudinary**, which ensures file persistence, automatic optimization, and fast CDN delivery.  

On the **security side**, I implemented **rate-limiting** to mitigate brute-force or spam requests and added a **payload size limit** to prevent oversized uploads.  

To improve reliability and developer experience, I applied **Zod validation** for input schemas, wrote **end-to-end tests**, and optimized the frontend with **Lighthouse** audits.  

These decisions ensure that Fork & Forchetta is not only functional but also scalable, secure, and user-friendly. 


## 🚀 Live
- Frontend (Vercel): https://fork-forchetta.vercel.app
- API (Render): https://fork-forchetta-api.onrender.com

---

## ✨ Features
- Add, edit, and delete recipes  
- Upload images via Cloudinary  
- Search & filter recipes  
- Pagination support  
- Language switch: English / Italian  
- Responsive design with Bootswatch United theme  
- **Integration tested via e2e tests**

---

## 🛠️ Tech Stack
- HTML5, CSS3
- Bootstrap 5 + Bootswatch United
- Vanilla JavaScript (Fetch API)
- Deployed on Vercel

---

## 📸 Screenshots

![Recipe List](./assets/screenshot-1.png)  
![Add Recipe](./assets/screenshot-2.png)  
![Flip Card](./assets/screenshot-3.png)  

---

## Demo GIF
![Add Recipe Flow](./assets/demo.gif)

---

## ⚡ How to Run Locally
```bash
git clone https://github.com/aliyecodes/fork-forchetta-web.git
cd fork-forchetta-web
# Open index.html in the browser
# OR use a local dev server (recommended):
npx serve

    Make sure the backend API is running locally at http://localhost:5000.

---

# 🇮🇹 Fork & Forchetta – Frontend

Questa è la parte frontend del progetto Fork & Forchetta.
Un’applicazione web leggera e responsive realizzata con HTML, CSS (Bootstrap/Bootswatch) e JavaScript Vanilla.
Il frontend comunica con l’API backend (Node.js + Express + MongoDB + Cloudinary) ospitata su Render.

---

## Portfolio Note  
Per questo progetto ho scelto **MongoDB** come database perché offre un’archiviazione flessibile dei documenti, ideale per ricette con campi variabili (es. ingredienti, istruzioni, immagini opzionali). Per l’archiviazione dei media ho utilizzato **Cloudinary**, che garantisce persistenza dei file, ottimizzazione automatica e distribuzione veloce tramite CDN.  

Dal lato **sicurezza**, ho implementato un **rate-limit** per ridurre il rischio di attacchi brute-force o spam e ho aggiunto un **limite alla dimensione dei payload** per prevenire upload eccessivi.  

Per migliorare l’affidabilità e l’esperienza di sviluppo, ho applicato la **validazione con Zod** sugli input, scritto **test end-to-end** e ottimizzato il frontend con le analisi di **Lighthouse**.  

Queste scelte assicurano che Fork & Forchetta non sia solo funzionale, ma anche scalabile, sicuro e facile da usare.

---

## 🚀 Live
- Frontend (Vercel): https://fork-forchetta.vercel.app
- API (Render): https://fork-forchetta-api.onrender.com

## ✨ Funzionalità
- Aggiungere, modificare e cancellare ricette
- Caricare immagini tramite Cloudinary
- Ricerca e filtro delle ricette
- Supporto per la paginazione
- Cambio lingua: Inglese / Italiano
- Design responsive con tema United di Bootswatch
- Test di integrazione tramite e2e

## 🛠️ Stack Tecnologico
- HTML5, CSS3
- Bootstrap 5 + Bootswatch United
- JavaScript Vanilla (Fetch API)
- Deploy su Vercel

## 📸 Screenshots

![Recipe List](./assets/screenshot-1.png)  
![Add Recipe](./assets/screenshot-2.png)  
![Flip Card](./assets/screenshot-3.png)  

## Demo GIF
![Add Recipe Flow](./assets/demo.gif)

## ⚡ Avvio Locale
```bash
git clone https://github.com/aliyecodes/fork-forchetta-web.git
cd fork-forchetta-web
    # Puoi aprire index.html direttamente nel browser
    # O usare un server locale (consigliato):
npx serve
