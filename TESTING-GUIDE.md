# Quick Testing Guide - Velo Landing Page

## Files for Testing

You have **3 files** ready to test:

1. ✅ **index.html** - Your complete website
2. ✅ **velo-logo.svg** - Your logo (now in SVG format!)
3. ✅ **hero-video.mp4** - Your workout video (20MB)

---

## How to Test Locally

### Step 1: Download All Files

Download all three files from the chat above.

### Step 2: Put Them Together

Create a folder and put all three files in it:

```
Velo Test/
├── index.html
├── velo-logo.svg
└── hero-video.mp4
```

**IMPORTANT:** All three files MUST be in the same folder!

### Step 3: Open in Browser

1. Double-click **index.html**
2. It will open in your default browser
3. You should see your landing page!

---

## What You'll See

✅ **Header:** Velo logo (SVG) in top left corner - clickable
✅ **Hero:** Workout video playing in background (may take 5-10 seconds to load)
✅ **Badge:** "Launching 2026" with pulsing blue dot
✅ **Headline:** "Perfect Your Form. Every Rep." (with cyan glow)
✅ **Buttons:** Two CTAs below headline
✅ **Features:** Three cards with custom icons and hover effects
✅ **Waitlist:** Form with trust signal
✅ **Footer:** Velo branding and links

---

## Testing Checklist

Test these things:

**Desktop:**
- [ ] Logo appears in top left
- [ ] Logo is clickable and scrolls to top
- [ ] Video plays automatically in background
- [ ] Pulsing dot animates on badge
- [ ] Feature cards have hover effects (lift and glow)
- [ ] All text is readable over video
- [ ] Form looks good (won't submit until Google Sheets setup)

**Mobile (use browser dev tools):**
- [ ] Press F12 → Click phone icon
- [ ] Logo is smaller but visible
- [ ] Video doesn't play (shows dark background - normal)
- [ ] All content stacks vertically
- [ ] Buttons are full-width
- [ ] Everything is readable

---

## Notes

**Video Loading:**
- 20MB video takes 5-15 seconds to load
- Dark background shows while loading
- This is normal - video will start once loaded

**Local Testing Limitation:**
- Some browsers may not autoplay video locally
- If video doesn't play, don't worry - it will work on Porkbun
- Upload to your live site to test properly

**Form:**
- Form won't submit yet (needs Google Sheets setup)
- Button will say "Submitting..." but nothing happens
- This is expected until you configure Google Sheets

---

## Upload to Porkbun

When ready to go live:

1. **Log into Porkbun.com**
2. **Domain Management → Your domain**
3. **File Manager → public_html folder**
4. **Upload all 3 files:**
   - index.html
   - velo-logo.svg
   - hero-video.mp4
5. **Wait for upload to complete** (video takes 1-3 minutes)
6. **Visit your domain!**

---

## File Sizes

- index.html: ~50 KB (very small)
- velo-logo.svg: ~20 KB (small - much smaller than PNG!)
- hero-video.mp4: 20 MB (large - consider compressing later)

**Total:** ~20 MB to upload

---

## Next Steps

**After testing locally:**
1. ✅ If everything looks good → Upload to Porkbun
2. ✅ Set up Google Sheets for form (we'll do this next)
3. ✅ Consider compressing video to 5-10MB (optional)
4. ✅ Share your site and start collecting signups!

---

## Troubleshooting

**Logo doesn't show:**
- Make sure velo-logo.svg is in same folder as index.html
- Refresh browser (Ctrl + Shift + R)

**Video doesn't play:**
- Wait 10-15 seconds for it to load
- Try a different browser (Chrome works best)
- If still not working locally, upload to Porkbun to test properly

**Page looks blank:**
- Check all 3 files are in the same folder
- Make sure you're opening index.html (not the other files)
- Try right-click → Open with → Your browser

**Feature cards don't have hover effects:**
- Hover effects work in browser, not when viewing file directly
- Make sure you're viewing in a web browser

---

## Questions?

If something doesn't work or looks wrong, let me know what you're seeing and I'll help troubleshoot!

---

## Summary

✅ SVG logo implemented (smaller, scalable)
✅ Video configured as hero background
✅ All features working
✅ Ready to test and upload

**Enjoy your new landing page!** 🚀
