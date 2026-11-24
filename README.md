# 🛏️ Truc Lan Motel — Website

A lightweight, responsive single-page website for **Nhà Nghỉ Trúc Lan (Truc Lan Motel)**,
a budget motel in **Hưng Thịnh, Trảng Bom, Đồng Nai, Vietnam**. Built as a static site and
hosted on **GitHub Pages**.

## ✨ Features

- **Single static page** — pure HTML, CSS, and a few lines of vanilla JavaScript. No build step, no dependencies.
- **Responsive design** — adapts cleanly to phones, tablets, and desktops.
- **Scroll-reveal animations** — sections fade in as you scroll (uses `IntersectionObserver`, with a graceful fallback for older browsers).
- **Modern, clean UI** — sticky header, hero banner, feature cards, price table, guest reviews, photo gallery, and a contact section with an embedded Google Map.
- **SEO & structured data** — meta tags plus [Schema.org](https://schema.org) `Motel` JSON-LD (name, address, phone, geo coordinates, aggregate rating) for better search visibility.
- **Image optimization** — serves WebP with a JPEG fallback via the `<picture>` element.
- **Direct call & directions** — tap-to-call phone links, a Google Maps direction link, and a floating call button.
- **Guest feedback** — links to a Google Forms form for reviews and suggestions.
- **Bilingual** — Vietnamese primary content with an English section for international guests.

## 📍 Location & Contact

> **Address:** Ấp Hưng Phát, 141B Đường 20, Hưng Thịnh, Trảng Bom, Đồng Nai, Vietnam
>
> 📞 **Phone:** [0971 955 211](tel:+84971955211) — `+84 971 955 211` (call-only number)
>
> ⭐ **Rating:** 4.2 / 5 on Google (25 reviews)
>
> 💰 **Price range:** Budget (₫)

## 🗂️ Project Structure

```
.
├── index.html      # Main page: markup, meta tags, Schema.org JSON-LD
├── style.css       # Stylesheet: layout, colors, responsive breakpoints
├── images/
│   ├── motel.jpeg  # Hero / gallery photo (JPEG fallback)
│   └── motel.webp  # Same photo (WebP, served first for modern browsers)
├── CNAME           # Custom domain for GitHub Pages (nhanghitruclan.id.vn)
├── .gitattributes  # Git attributes
└── README.md       # This file
```

## 🚀 Deploying to GitHub Pages

1. Go to the repository **Settings → Pages**.
2. Under **Source**, select the **main** branch and the `/ (root)` folder.
3. Wait for the build to finish, then visit the published URL.

> **Custom domain:** the `CNAME` file currently contains `nhanghitruclan.id.vn`.
> To use a different domain, edit that file to hold your domain name (without `http://` or `www`),
> then point your domain's DNS `A` / `CNAME` records at GitHub Pages.

## 🛠️ Customizing

- **Prices:** in `index.html`, replace `Gọi để báo giá` ("Call for a quote") in the price table with the real price (e.g. `120.000₫`).
- **Photos:** add images to the `images/` folder, then copy a `<figure>` block from the gallery section and update its `src` and `alt` attributes.
- **Contact info:** update the phone number, address, and Google Maps link in the contact section.
- **Reviews:** edit the quote text and author names in the reviews section.

## 🧰 Tech Stack

| Technology | Purpose |
| --- | --- |
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, layout, responsive breakpoints |
| JavaScript (vanilla) | Scroll-reveal animations |
| GitHub Pages | Free static hosting |

## 📄 License

Private / © 2026 Nhà Nghỉ Trúc Lan.

---

Made with ❤️ for Truc Lan Motel.
