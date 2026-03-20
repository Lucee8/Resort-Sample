# 🏖️ Resort Website Template

> A professional, fully responsive luxury beach resort website — built with pure HTML, CSS & JavaScript. No frameworks, no dependencies. Just open and go.

![Resort Website](https://images.unsplash.com/photo-1571896349842-33c89424de2d?w=1200&q=80)

---

## 🌐 Live Demo

👉 **[View Live Site](https://your-username.github.io/resort-website/)**

> Replace the link above with your actual GitHub Pages URL after deployment.

---

## ✨ Features

- 🌙 **Dark luxury theme** — deep black backgrounds with gold accents
- 📱 **Fully responsive** — works perfectly on mobile, tablet & desktop
- 💬 **WhatsApp integration** — 3 entry points (floating button, contact section, booking bar)
- 📞 **Click-to-call button** — floating call button always visible
- 📅 **Smart booking bar** — date pickers + guest counters that open WhatsApp with pre-filled message
- 🛏️ **6 room cards** — with price badges, features, and hover effects
- 🏊 **8 amenity cards** — with animated hover effects
- 🖼️ **Interactive gallery** — 3 large images + scrollable thumbnail strip
- ⭐ **Guest reviews section** — testimonial cards
- 📋 **Contact & enquiry form** — full form with room selection
- 🦶 **4-column footer** — with social links, room list, quick links
- ⬆️ **Back-to-top button** — appears on scroll
- 🎬 **Scroll animations** — elements fade in as you scroll
- 📌 **Sticky navbar** — darkens on scroll, hamburger on mobile

---

## 📁 Project Structure

```
resort-website/
│
├── index.html          ← Main website file (everything is here)
├── README.md           ← This file
└── assets/             ← (Optional) Add your own images here
    ├── images/
    └── logo.png
```

> This is a **single-file website** — all HTML, CSS, and JavaScript lives inside `index.html`. This makes it super easy to deploy and customize.

---

## 🚀 How to Deploy on GitHub Pages (Step by Step)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click **"New"** (green button) to create a new repository
3. Name it: `resort-website` (or any name you like)
4. Set it to **Public**
5. Click **"Create repository"**

### Step 2 — Upload Your File
1. Inside your new repo, click **"Add file" → "Upload files"**
2. Drag and drop `index.html` (rename `resort_template.html` → `index.html` first!)
3. Also upload this `README.md` file
4. Scroll down and click **"Commit changes"**

### Step 3 — Enable GitHub Pages
1. Go to your repo's **Settings** tab (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Branch"**, select `main` and folder `/root`
4. Click **Save**
5. Wait 1–2 minutes — GitHub will give you a live URL like:
   `https://your-username.github.io/resort-website/`

### Step 4 — Update the Live Demo Link
Come back to this `README.md`, click the ✏️ pencil edit icon, and replace:
```
https://your-username.github.io/resort-website/
```
with your actual URL. Commit the change.

---

## 🎨 How to Customize for Each Client

All customizations are inside `index.html`. Just find and replace:

| What to change | Find this text | Replace with |
|---|---|---|
| Resort name | `Resort Name` | Client's resort name |
| WhatsApp number | `919876543210` | Client's number (with country code, no +) |
| Phone number | `+91 98765 43210` | Client's actual number |
| Email | `stay@resortname.com` | Client's email |
| Location | `Devbag Beach Road, Tarkarli` | Client's address |
| Room names | `Blissful Suite`, etc. | Client's room names |
| Room prices | `Rs.14,099` etc. | Client's actual prices |
| Gold color | `#C9A44A` | Any hex color for branding |
| Photos | Unsplash URLs | Client's actual photos |

### Changing the Logo Letter
Find this in the HTML:
```html
<span>R</span>
```
Replace `R` with the first letter of the client's resort name.

### Changing Photos
Find any Unsplash URL like:
```
https://images.unsplash.com/photo-1631049307264-da0ec9d70304?w=600&q=80
```
Replace with the path to your client's actual image, e.g.:
```
assets/images/room1.jpg
```

---

## 📦 Sections Overview

| Section | Description |
|---|---|
| **Navbar** | Fixed top bar with logo, links, Book Now button, mobile hamburger |
| **Hero** | Split layout — room photo left, welcome text + 4 image grid right |
| **Booking Bar** | Full-width bar with dates, guest counters, room type, Check Availability |
| **Our Rooms** | 6 cards with price badges, features, Book Now button |
| **Amenities** | 8 cards on light background with animated hover effects |
| **Gallery** | 3 large images + scrollable thumbnail row |
| **Reviews** | 3 guest testimonial cards with star ratings |
| **Contact** | Info cards + WhatsApp button + Enquiry form |
| **Footer** | 4-column footer with social, links, rooms, contact |

---

## 💬 WhatsApp Integration Details

The website has **3 WhatsApp touchpoints**:

1. **Floating button** (bottom right) — always visible, links directly to chat
2. **Contact section button** — "Chat on WhatsApp" with a pre-written message
3. **Check Availability button** — sends check-in date, check-out date, adults, children, and rooms as a pre-filled WhatsApp message

To update the WhatsApp number, search for `919876543210` in the HTML and replace all instances with the client's number (Indian format: `91` + 10-digit number, no spaces or `+`).

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, animations, responsive layout |
| Vanilla JavaScript | Interactivity (counters, gallery, scroll effects) |
| Google Fonts | Playfair Display + Jost typography |
| Unsplash | Placeholder images (replace with client photos) |

No npm, no build tools, no frameworks — just a single `.html` file.

---

## 📋 Checklist Before Handing to Client

- [ ] Replace all `Resort Name` with client's name
- [ ] Update WhatsApp number (`919876543210`)
- [ ] Update phone number and email
- [ ] Update address / location
- [ ] Replace all Unsplash images with client's real photos
- [ ] Update room names and prices
- [ ] Change logo letter (the `R` in the circle)
- [ ] Update Google Maps link (if added)
- [ ] Test on mobile
- [ ] Test WhatsApp links open correctly
- [ ] Deploy to GitHub Pages or client's hosting

---

## 📄 License

This template is created for client delivery purposes. Each deployed version is customized for a specific resort client.

---

## 👨‍💻 Built By

**Lucee** — Student & Web Developer  
Building affordable, professional websites for local businesses.

📱 WhatsApp: [+91 XXXXXXXXXX](https://wa.me/91XXXXXXXXXX)  
📷 Instagram: [@your_handle](https://instagram.com/your_handle)

---

> ⭐ If you found this template useful, consider starring the repo!
