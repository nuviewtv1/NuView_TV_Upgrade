# NuView TV - Website Upgrade & Interactive EPG Program Guide

This repository contains the interactive TV Program Guide (EPG) built for the **NuView TV** website upgrade ([www.nuviewtv.co.za](https://www.nuviewtv.co.za)).

---

## 📺 Features Included

1. **Real EPG Data Integration**:
   - 185 programmes extracted directly from NuView TV's official schedule.
   - Covers 6 days (25 September 2026 – 30 September 2026) in GMT+2 (SAST).
   - Accurate program runtimes, titles, genres, and both short & full descriptions.

2. **Dynamic "Now Playing" Banner**:
   - Live pulse indicator detecting the active show based on current South African Standard Time (SAST).
   - Automatically refreshes every 60 seconds.

3. **Day Switcher & Tabs**:
   - Filter programmes by day with date labels and smart "Today" auto-selection.

4. **Live Search**:
   - Instant search filter to find shows by title or topic.

5. **Show Details Modal**:
   - Click any show card to view extended synopsis, timings, and category details.

6. **Branding & Responsive Theme**:
   - Styled to match NuView TV’s signature dark purple palette (`#0d0015`, `#240046`, `#7b2ff7`).
   - Fully responsive for desktop, tablets, and smartphones.

---

## 🚀 How to Integrate with WordPress / Elementor

### Option A: Direct Embed (Custom HTML Block)
1. Open the page in WordPress / Elementor.
2. Add a **Custom HTML** block.
3. Paste the contents of `nuviewtv-guide.html` into the block and save.

### Option B: iFrame / Standalone Hosting
Upload `index.html` to your server (or GitHub Pages) and embed:
```html
<iframe src="https://yourdomain.com/path-to/index.html" width="100%" height="900px" style="border:none;"></iframe>
```

---

## 📂 File Structure
- `index.html` / `nuviewtv-guide.html`: Complete, self-contained standalone application containing HTML, CSS, JavaScript, and embedded schedule data.
