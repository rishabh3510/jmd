# JMD Maha Meva Group - Official Corporate Website

A production-grade corporate website built for a commercial civil engineering and government contracting firm based in Gurugram, Haryana. This project serves as a live, fully deployed business platform handling client inquiries, showcasing construction portfolios, and maintaining a verified presence on Google Search.

## 🚀 Live Demo
**Production URL:** [https://www.jmdmahamewa.in](https://www.jmdmahamewa.in)

## 🏗️ Tech Stack & Architecture
* **Frontend:** HTML5, CSS3, JavaScript
* **Form Handling:** Web3Forms API for automated client quote requests
* **Hosting & CI/CD:** Vercel (Automated deployments via GitHub)
* **Domain Registrar:** GoDaddy (`.in` domain with DigiLocker KYC compliance)
* **Version Control:** Git & GitHub

## ⚙️ Key Technical Implementations

### 1. Custom Domain & DNS Architecture
* Mapped GoDaddy DNS to Vercel edge networks using custom `A` (IPv4) and `CNAME` records.
* Configured automated SSL/TLS certificate generation for secure HTTPS traffic.

### 2. SEO & Traffic Routing
* **308 Permanent Redirect:** Engineered a strict 308 redirect from the default Vercel staging URL (`jmd-rouge.vercel.app`) to the production `.in` domain to preserve SEO link equity and prevent duplicate content penalties.
* **JSON-LD Schema Markup:** Injected dynamic `Organization` and `WebSite` structured data into the `<head>` to force Google's Knowledge Graph to recognize the official brand name and corporate logo in search results.
* **Open Graph Tags:** Configured meta tags for optimized link unfurling on social media and messaging platforms.

### 3. Google Search Console Integration
* Verified domain ownership via HTML file injection.
* Submitted manual indexing requests to accelerate Google bot crawling for the new branded domain and favicon cache updates.

## 👨‍💻 Developer
Developed and deployed as a real-world commercial project to demonstrate web architecture, cloud deployment pipelines, and advanced SEO configurations. 

**Academic Context:** B.Tech Computer Science and Engineering (2024-2028), Guru Gobind Singh Indraprastha University (GGSIPU).
