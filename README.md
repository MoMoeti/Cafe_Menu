# Café OrderPad v3.0  
**A fully offline, installable, auto-updating digital menu for cafés**

![Café Logo](https://i.postimg.cc/pV9p4PtP/1-removebg-preview.png)

> **No app store. No server. No monthly fees.**  
> Just open in any browser → **"Add to Home Screen"** → **Done!**

---

## FEATURES

| Feature | Description |
|-------|-----------|
| **Installable PWA** | Add to home screen (Android/iOS) |
| **Offline Mode** | Works with **no internet** |
| **Auto-Updates** | New menu? Users get it **next time they open** |
| **Live Orders via WhatsApp** | Sends order to `+27 69 469 1709` |
| **Google Sheets Sync** | Orders saved to your sheet |
| **Dark / Light Mode** | Auto-adjusts to system |
| **Search & Filter** | Find items instantly |
| **Admin Panel** | Password: `passedshit` |
| **Custom Background** | Your kitchen wallpaper |
| **Branded Logo** | In header + app icon |

---

## LIVE DEMO

**Open on any phone:**  
[https://your-cafe-menu.vercel.app](https://your-cafe-menu.vercel.app) *(replace with your Vercel link)*

---

## HOW TO DEPLOY (30 SECONDS)

### 1. **Deploy to Vercel (Free Forever)**

1. Go to → [https://vercel.com](https://vercel.com)
2. Sign in with **GitHub**
3. Click **"New Project"**
4. **Drag & drop** `index.html`
5. Done! → Get your link: `https://your-cafe-menu.vercel.app`

---

### 2. **Add to Home Screen**

On any phone:
1. Open the link in **Chrome / Safari**
2. Tap **"Add to Home Screen"**
3. Done — **Full app experience**

---

## FILE STRUCTURE

> **No backend. No database. All data in browser + Google Sheets.**

---

## ADMIN PANEL

1. Scroll to bottom
2. Enter password: **`passedshit`**
3. **Add / Edit / Remove** items
4. Changes **saved instantly** (even offline)

---

## AUTO-BACKUP TO GOOGLE SHEETS

Every order is sent to:  
[https://script.google.com/...](https://script.google.com/macros/s/AKfycbxsGJbsPttG2XK7yXPEF9Is81S5q3_5Hhot4-XhRu75Yy5t2ITxIWF_EpfsvNDc5ODv/exec)

> **No setup needed** — just works!

---

## CUSTOMIZATION

| Want to change | How |
|---------------|-----|
| **Background** | Edit URL in `body { background: url('...') }` |
| **Logo** | Replace in `<img src="...">` and manifest |
| **WhatsApp Number** | Change `WHATSAPP_NUMBER` in JS |
| **Password** | Change `ADMIN_PASSWORD` |
| **Currency** | Search/replace `R` → `£`, `$`, etc. |

---

## UPGRADING (Zero Downtime)

1. Edit `index.html`
2. **Change version**:  
   ```js
   const APP_VERSION = "v3.1";
