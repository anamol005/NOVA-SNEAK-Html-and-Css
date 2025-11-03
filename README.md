# NOVA SNEAKS —  Sneaker Store Website

This repository contains my HTML + CSS assignment project.  
The goal was to recreate the provided Home, Products, and Contact page layouts, using my own colors, images, typography, and visual structure.

This project is built as a 3-page static website.

---

## 🔗 Website Pages

| Page     | File          | Description |
|----------|---------------|-------------|
| Home     | `index.html`  | Hero section, featured sneakers, call-to-action |
| Products | `products.html` | Full sneaker listing + filters + add-to-cart |
| Contact  | `contact.html` | Basic contact details + form layout |

All pages are connected through navigation and function similar to a real e-commerce store.

---

## 🎨 Design Choices

### Typography
I used **Poppins** from Google Fonts — clean, modern & readable.

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
body {
  font-family: "Poppins", sans-serif;
}
```
| Usage                  | Color     |
| ---------------------- | --------- |
| Background (body)      | `#0b0b0c` |
| Panel / Card           | `#121214` |
| Accent Red             | `#E10600` |
| Main Text              | `#efefef` |
| Muted / Secondary text | `#a7a7ad` |

🧩 Features Implemented

- Navigation works between all pages
- Products filtering (Street / Performance / Luxury)
- Add-to-cart system using LocalStorage
- Dynamic cart badge count
- Remove item animation in cart page
- Lazy loaded + compressed images (performance improvement)
- Custom images (imported manually)
- Spacing & padding adjusted properly (no “text touching edges” issue)
- NOT responsive (not required in assignment)


| Requirement                      | Result          |
| -------------------------------- | --------------- |
| CSS included                     | ✅               |
| Layout resembles provided layout | ✅               |
| Navigation works                 | ✅               |
| Images load correctly            | ✅               |
| Contrast test (WAVE)             | ✅ Pass          |
| HTML validation (Validator)      | ✅ Pass          |
| Lighthouse performance improved  | ✅               |
| Default font NOT used            | ✅ using Poppins |

📂 Files in this project

- index.html
- products.html
- contact.html
- style.css
- /img folder

## 🧾 About

NOVA SNEAKS is a fictional sneaker brand website built for an HTML+CSS assignment.
Focus: modern clean UI + minimal code + simple realistic e-commerce behavior.
