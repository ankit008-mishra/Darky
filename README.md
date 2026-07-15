# 🌑 Darky — Premium Glass Theme for YouTube Music

> A sleek, dark glass-morphism theme for YouTube Music with smooth animations and an immersive visual experience.

---

## 📸 Screenshots

![Darky Theme Preview](1.png)

![Darky Glass Details](1.webp)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🌫️ **Glass Morphism UI** | Frosted glass effect on navbar, sidebar, player bar, and all menus |
| 🎨 **True Dark Aesthetic** | Deep blacks with subtle transparency for a premium look |
| 🔍 **Seamless Search** | Glass-integrated search dropdown with smooth transitions |
| 📜 **Scroll-Proof Sidebar** | Persistent frosted glass navigation that stays clean while scrolling |
| 🎵 **Immersive Player** | Full-screen layout with dynamic background and smooth panel transitions |
| 🎤 **Lyrics Engine** | Apple Music-inspired progressive blur with word-by-word highlighting |
| 🎛️ **Floating Player Bar** | Bottom glass bar with hover effects and smooth controls |
| ⚡ **Smooth Animations** | Hover lifts, scale effects, fade-ins, and elastic transitions throughout |
| 🖼️ **Dynamic Thumbnails** | Scale and darken effects on album art hover |
| 🍎 **Apple-Style Tabs** | Custom SVG icons for Queue, Lyrics, Comments, and Autoplay tabs |
| 📱 **Responsive Design** | Adapts cleanly across different screen sizes |

---

## 🎬 Animation Highlights

### UI Animations
- **Navbar** — Slide-down fade-in on page load
- **Sidebar Items** — Staggered fade-in from left
- **Cards** — Fade-in-up with hover lift effect
- **Buttons** — Scale bounce on hover, shrink on click
- **Menus** — Scale-in pop with glass blur backdrop
- **Queue Items** — Staggered slide-in from right
- **Player Bar** — Slide-up entrance animation
- **Skeleton Loaders** — Shimmer effect while content loads

### Lyrics Animations
- **Active Line** — Clears blur, scales up, glows white
- **Past Lines** — Fade out with progressive blur
- **Future Lines** — Cascading blur: `2px → 3.5px → 5px → 6.5px → 8px → 9.5px`
- **Word Bounce** — Each word pops up as it syncs with the song
- **Color Transitions** — Smooth white glow on active synced words

---

## 🛠️ Installation

### Method 1: Stylus Extension (Recommended)

1. **Install Stylus** browser extension:
   - [Chrome Web Store](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
   - [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

2. **Open Stylus** → Click **"Write new style"**

3. **Add the CSS**:
   - Copy all the code from `Darky_Animated.user.css`
   - Paste it into the Stylus editor

4. **Set the URL**:
   - Add this rule: `URLs on the domain` → `music.youtube.com`

5. **Save** and visit [music.youtube.com](https://music.youtube.com)

### Method 2: UserScript Manager (Tampermonkey / Greasemonkey)

1. Install **Tampermonkey** or **Greasemonkey** extension
2. Create a new userscript
3. Paste the CSS inside a `GM_addStyle()` block
4. Set `@match` to `https://music.youtube.com/*`
5. Save and refresh YouTube Music

### Method 3: Better Lyrics Extension (If submitting to store)

1. Install the **Better Lyrics** extension
2. Go to Extension Options → **Themes** tab
3. Click **Install from URL** or **Browse Themes**
4. Paste your theme repository URL
5. Click Install

---

## 📝 File Structure

```
Darky-Theme/
├── Darky_Animated.user.css    # Main theme file
├── README.md                   # This file
├── 1.png                       # Screenshot 1 (PNG)
└── 1.webp                      # Screenshot 2 (WebP)
```

---

## 🎨 What This Theme Changes

### Navigation Bar
- Transparent glass background with blur
- Rounded search box with hover glow
- Apple-style tab icons (Queue, Lyrics, Comments, Autoplay)

### Sidebar
- Frosted glass background
- Rounded menu items with hover slide effect
- Active item highlight with subtle pulse

### Player Page
- Dynamic blurred album art background
- Square album artwork with shadow
- Centered layout with smooth panel resizing
- Glass song info block below artwork

### Player Bar (Bottom)
- Floating glass pill design
- Progress bar at top with hover expansion
- Smooth button hover scales
- Like button heartbeat animation when active

### Menus & Popups
- 3-dot menu: Glass blur with rounded corners
- Profile menu: Dark glass with smooth hover
- Add to Playlist: Scale-in bounce animation
- Share menu: Glass backdrop with hover effects
- Settings: Blurred modal with clean layout

### Lyrics Panel
- Right-aligned text
- Progressive downward blur cascade
- Word-by-word bounce on sync
- White glow on active words

---

## ⚠️ Known Limitations

> **Lyrics Scroll Animation**
>
> I tried to implement a perfectly smooth scroll animation for the lyrics panel similar to native Apple Music, but I couldn't get the scroll interpolation to feel buttery smooth. The current implementation uses CSS transitions and blur filters which work well, but the auto-scroll snapping and momentum scrolling still feel slightly jittery compared to a true native app experience.
>
> If anyone knows a better way to handle smooth lyric scrolling with proper easing and no frame drops, contributions are welcome!

---

## 🙏 Credits

- **Theme Author:** [ankit008-mishra](https://github.com/ankit008-mishra)
- **Font:** San Francisco Pro (Apple-style typography)
- **Inspired by:** Apple Music, Glass Morphism Design Language
- **Built for:** YouTube Music + Better Lyrics Extension

---

## 📜 License

This theme is free to use and modify. Credit the original author if redistributing.

---

> *"Design is not just what it looks like and feels like. Design is how it works."* — Steve Jobs
