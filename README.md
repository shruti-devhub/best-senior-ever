# 🌟 Tribute Website for Anshi Singh

A beautiful, modern, and responsive tribute website dedicated to Anshi Singh. This website features elegant animations, a photo gallery, video clips section, and a memories timeline.

## ✨ Features

- **Modern & Effective Theme** - Elegant design with a warm color palette
- **Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **Photo Gallery** - Beautiful masonry grid with lightbox effect
- **Video Section** - Showcase precious video clips with custom player
- **Memories Timeline** - Scroll through cherished moments
- **Animations & Effects** - Smooth scroll animations, floating particles, hover effects
- **Navigation** - Fixed navbar with smooth scrolling

## 📁 Project Structure

```
f.s/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Animations & interactions
├── assets/             # Your photos and videos
│   ├── photo1.jpg      # Main hero photo
│   ├── photo2.jpg      # About section photo
│   ├── photo3-8.jpg    # Gallery photos
│   ├── video1-3.mp4    # Video clips
│   ├── video-thumb*.jpg # Video thumbnails
│   └── memory*.jpg     # Timeline photos
└── README.md           # This file
```

## 🖼️ How to Add Your Photos & Videos

### 1. Adding Photos

Replace the placeholder images in the `assets/` folder:

- **photo1.jpg** - Main hero section photo (recommended: 800x900px)
- **photo2.jpg** - About section photo (recommended: 700x900px)
- **photo3.jpg to photo8.jpg** - Gallery photos (recommended: 600x600px each)
- **memory1.jpg to memory3.jpg** - Timeline photos (recommended: 400x400px each)

### 2. Adding Videos

Place your video files in the `assets/` folder:

- **video1.mp4** - First video clip
- **video2.mp4** - Second video clip  
- **video3.mp4** - Third video clip

**Recommended video format:**
- Format: MP4 (H.264)
- Resolution: 1280x720 (720p) or 1920x1080 (1080p)
- Duration: 30 seconds to 2 minutes per clip

### 3. Adding Video Thumbnails (Optional)

For better appearance, add thumbnail images:

- **video-thumb1.jpg** - Thumbnail for video 1
- **video-thumb2.jpg** - Thumbnail for video 2
- **video-thumb3.jpg** - Thumbnail for video 3

Recommended size: 800x500px

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #c9a87c;      /* Main accent color */
    --primary-dark: #a88b5e;       /* Darker accent */
    --secondary-color: #2c3e50;    /* Secondary color */
    --bg-light: #faf8f5;           /* Light background */
}
```

### Changing the Name

Search for "Anshi Singh" in `index.html` and replace it with the desired name:

- Line ~20: Logo/Brand name
- Line ~30: Hero title
- Line ~90: About section heading
- Line ~300: Footer message

### Adding More Gallery Photos

In `index.html`, add more `.gallery-item` divs inside the `.gallery-grid`:

```html
<div class="gallery-item reveal-up" data-delay="6">
    <img src="assets/photo9.jpg" alt="Memory 9">
    <div class="gallery-overlay">
        <i class="fas fa-expand"></i>
        <span>Caption</span>
    </div>
</div>
```

### Adding More Video Clips

Add more `.video-card` divs in the `.video-grid` section.

## 🚀 How to View the Website

### Option 1: Open Directly
Simply double-click `index.html` to open it in your browser.

### Option 2: Using a Local Server
For better performance and to avoid CORS issues with some features:

```bash
# If you have Python installed
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

### Option 3: VS Code Live Server
1. Open the folder in VS Code
2. Install "Live Server" extension
3. Right-click `index.html` and select "Open with Live Server"

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## 🤝 Credits

- Font: Google Fonts (Playfair Display, Poppins)
- Icons: Font Awesome 6
- Animations: Custom CSS & JavaScript

## 💝 Made with Love

This website was created with care and love to celebrate Anshi Singh. Feel free to customize it to make it even more special!

---

**Note:** The website includes placeholder images and SVG graphics. Replace them with actual photos of Anshi Singh for the best experience.

