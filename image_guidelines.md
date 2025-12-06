# Website Image Requirements & Generation Prompts

Here are the recommended image assets, dimensions, and AI prompts to generate high-quality visuals that match your website's **Dark Anime/Modern** aesthetic (Theme colors: `#0f172a`, `#6366f1`, `#ec4899`).

## 1. Social Share Image (Open Graph / Twitter)
Used when your link is shared on Facebook, Twitter, Discord, etc.
- **File Name:** `og-image.jpg`
- **Dimensions:** `1200 x 630` pixels
- **Format:** JPG (Quality 80-90%)
- **Context:** Needs to look good with text overlay or standalone.

**AI Generation Prompt:**
> digital art, anime style, panoramic view of a futuristic cyber city at night with neon purple and blue lights, silhouette of a character watching from a high vantage point, sleek, modern, 4k resolution, Makoto Shinkai style clouds, vibrant violet and deep blue color palette --ar 1.91:1

## 2. PWA Icon / Favicon
Used for the browser tab, mobile home screen app icon, and splash screen.
- **File Name:** `icon-512.png` (and `icon-192.png`)
- **Dimensions:** `512 x 512` pixels (Square)
- **Format:** PNG (Transparent background preferred for logo, or full fill for app icon)
- **Context:** Must be simple and recognizable at small sizes.

**AI Generation Prompt:**
> minimalist anime style logo, letter "A" or abstract play button symbol, vector art, flat design, glowing neon violet and pink gradients, dark slate background #0f172a, modern UI icon, high quality, centered --no text

## 3. Website Logo
Used in the header navigation.
- **File Name:** `logo.png`
- **Dimensions:** `300 x 80` pixels (approx)
- **Format:** PNG (Transparent background)
- **Context:** Horizontal layout, distinct from background.

**AI Generation Prompt:**
> modern typography logo design, text "AnimeGuide", futuristic sans-serif font, glowing violet gradient letters, simple anime mascot head icon to the left, vector style, white background (to be removed), clean lines, professional branding

## 4. Hero Background (Optional)
If you decide to replace the CSS gradient with an image.
- **File Name:** `hero-bg.jpg`
- **Dimensions:** `1920 x 1080` pixels
- **Format:** JPG (Compressed)
- **Context:** Will be darkened/blurred behind text.

**AI Generation Prompt:**
> abstract anime background, motion blur, speed lines, deep space with violet nebula and digital artifacts, dark blue atmosphere, subtle geometric shapes, immersive, cinematic lighting, 8k wallpaper --ar 16:9

---

## How to use these
1. **Generate**: Use the prompts above in your preferred AI image generator (Midjourney, DALL-E, etc.).
2. **Resize**: Crop/Resize to the exact dimensions listed.
3. **Save**: Save to your project folder (`C:\Users\Awais Bashir\Downloads\gachiakuta\`).
4. **Link**: Update `index.html` and `manifest.json` to reference these files.
