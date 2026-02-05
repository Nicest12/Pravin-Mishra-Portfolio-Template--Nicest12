# DMI Portfolio Website (Static HTML/CSS)

This repository contains a clean, professional-looking **static portfolio website** used in **DevOps Micro Internship (DMI)** Week 1 to practice:
- Linux basics
- Nginx hosting
- Deployment proof / ownership
- Production-style checks

✅ Students deploy this website on an Ubuntu VM using Nginx and keep it live for 24 hours.

---

## Who is this for?
- DMI students (beginner → intermediate)
- Anyone learning how to host a static site with Nginx on Linux

---

## What you will build
A portfolio-style website hosted on:
- **Ubuntu VM**
- **Nginx**
- Accessible via: `http://<public-ip>`

---

## Mandatory Ownership Proof (DMI Rule)
Before you deploy, you MUST edit the footer and add your details:

Original:

```html
<p>Crafted with <span>cloud</span> excellence by Pravin Mishra</p>
```

Add this line (example):

```html
 </p>Pravin Mishra Portfolio v1.0 — Deployed on <span id="deployDate"></span> — By Nwogu Nice Ihuoma</p>

A small code snippet (footer section + JS if used)
  <script>
      const today = new Date();

      const months = ["Jan", "Feb", "Mar", "Apr", "May", "Jun",
                      "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];

      const day = String(today.getDate()).padStart(2, '0'); // 2-digit day
      const month = months[today.getMonth()]; // Month abbreviation
      const year = today.getFullYear(); // 4-digit year

      // Format: DD Mon YYYY
      const formattedDate = `${day} ${month} ${year}`;

      document.getElementById("deployDate").textContent = formattedDate;
    </script>
```

✅ This proof must be visible in your browser screenshot submission.