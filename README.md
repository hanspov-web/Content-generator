# Content Idea Generator - Progressive Web App (PWA)

A mobile-optimized app that generates social media content ideas with photo prompts, captions, hashtags, and platform-specific guidelines. Save ideas to your library and track what you've posted!

## ✨ Features

- **Content Generation**: Generate complete content ideas for Instagram, TikTok, Pinterest, and Facebook
- **Multi-Platform Support**: Get platform-specific guidelines for each post
- **Content Library**: Save and organize ideas by content pillar
- **Posted Tracking**: Mark content as posted and keep track of what's been used
- **Offline Support**: Works without internet connection once installed
- **Mobile-Optimized**: Designed for phone use with installable PWA

## 📱 How to Install on Your Phone

### Option 1: Deploy Online (Recommended - Easiest)

**Using Netlify (Free):**

1. Go to https://app.netlify.com/drop
2. Drag and drop ALL these files:
   - index.html
   - manifest.json
   - service-worker.js
   - icon-192.png (if you created one)
   - icon-512.png (if you created one)
3. You'll get a URL like: https://random-name-12345.netlify.app
4. Open that URL on your phone
5. Follow the "Add to Home Screen" instructions below

**Using GitHub Pages (Free):**

1. Create a GitHub account at https://github.com
2. Create a new repository (name it anything, like "content-generator")
3. Upload all the files to the repository
4. Go to Settings > Pages
5. Select "main" branch and click Save
6. You'll get a URL like: https://yourusername.github.io/content-generator
7. Open that URL on your phone
8. Follow the "Add to Home Screen" instructions below

### Option 2: Run Locally (For Testing)

1. Install Python (if you don't have it)
2. Put all files in a folder
3. Open Terminal/Command Prompt in that folder
4. Run: `python -m http.server 8000`
5. On your phone (connected to same WiFi):
   - Find your computer's IP address
   - Open browser and go to: http://YOUR-IP:8000
6. Follow "Add to Home Screen" instructions

### Add to Home Screen

**iPhone (Safari):**
1. Open the website
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"

**Android (Chrome):**
1. Open the website
2. Tap the three dots menu
3. Tap "Add to Home Screen" or "Install App"
4. Tap "Install"

## 🎨 Customizing Your App Icons

The app works with a default emoji icon, but for a custom icon:

1. Create or find a logo (512x512 pixels recommended)
2. Use a tool like:
   - https://realfavicongenerator.net/
   - Canva (create 512x512px design, export as PNG)
3. Save as:
   - `icon-192.png` (192x192 pixels)
   - `icon-512.png` (512x512 pixels)
4. Upload these with the other files when deploying

## 📝 Files Included

- **index.html** - Main app file (contains all the code)
- **manifest.json** - PWA configuration
- **service-worker.js** - Enables offline functionality
- **README.md** - This file (instructions)
- **icon-192.png** - App icon (you need to create this)
- **icon-512.png** - App icon (you need to create this)

## 🚀 Quick Start Guide

1. **Deploy the app** using Netlify Drop or GitHub Pages (see above)
2. **Open the URL** on your phone
3. **Install it** to your home screen
4. **Start generating content!**
   - Select content pillars
   - Choose platforms
   - Click "Generate Content Idea"
   - Save to your library
   - Mark as posted when you use them

## 💾 Data Storage

- All data is stored **locally on your device** using localStorage
- Your content library persists between sessions
- Nothing is sent to external servers
- If you clear your browser data, you'll lose your library

## 🔧 Customization

Want to customize the app? You can edit `index.html`:

- **Colors**: Search for color codes like `#9333EA` (purple) and `#EC4899` (pink)
- **Content Ideas**: Find the `contentIdeas` object and add your own topics
- **Hashtags**: Modify the `baseHashtags` object with your preferred hashtags
- **Platforms**: Add or remove platforms in the `platforms` array

## ⚠️ Troubleshooting

**App won't install:**
- Make sure you're using HTTPS (required for PWA)
- Try using Chrome or Safari (best PWA support)
- Check that manifest.json and service-worker.js are in the same folder

**Library not saving:**
- Check that your browser allows localStorage
- Try clearing cache and reinstalling
- Make sure you're not in incognito/private mode

**Icons not showing:**
- Make sure icon files are named exactly: icon-192.png and icon-512.png
- Verify icons are in the same folder as index.html
- Try clearing cache and reinstalling

## 📱 Best Practices

1. **Generate in batches**: Create 10-15 ideas at once during your planning time
2. **Filter by pillar**: Focus on one content pillar when planning your week
3. **Export for backup**: Use the export button to save ideas as text files
4. **Review before posting**: The generated content is a template - customize it!

## 🎯 Tips for Content Creation

- Use the photo prompts as inspiration, not strict rules
- Customize captions to match your voice and brand
- Mix and match hashtags based on what's working for you
- Check trending sounds on each platform before posting
- Batch create content for the week every Sunday

## 📄 License

This app is free to use for personal and commercial purposes. You can modify it to fit your needs!

## 🆘 Need Help?

If you run into issues:
1. Check the troubleshooting section above
2. Make sure all files are uploaded correctly
3. Try a different browser (Chrome or Safari work best)
4. Clear your browser cache and try again

---

**Enjoy creating content! 🎉**
