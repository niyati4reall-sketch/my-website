# TalkYourMind – Mental Wellness Campaign Website

A single-page site for the student-led HOSA mental health campaign focused on teen depression and anxiety.

## What’s included

- **Hero** with campaign name and a “Play on YouTube” link
- **What is TalkYourMind?** – HOSA campaign, focus on teen depression & anxiety, education, stigma reduction, open conversations
- **Purpose & Goal** – problem (prevalence, impact, stigma) and goal (educate, support, connect)
- **Resources** – buttons linking to “What is depression?” and “What is anxiety?” (currently WHO fact sheets)
- **Footer** – Instagram, YouTube, and Gmail links

## How to add your links

Edit `index.html` and replace:

1. **YouTube video**  
   Find: `https://www.youtube.com/watch?v=YOUR_VIDEO_ID`  
   Replace `YOUR_VIDEO_ID` with your video’s ID (e.g. `dQw4w9WgXcQ`).

2. **Instagram**  
   Find: `https://www.instagram.com/YOUR_INSTAGRAM`  
   Replace with your profile URL (e.g. `https://www.instagram.com/talkyourmind`).

3. **YouTube channel**  
   Find: `https://www.youtube.com/@YOUR_CHANNEL`  
   Replace with your channel URL.

4. **Gmail**  
   Find: `mailto:your.talkyourmind@gmail.com`  
   Replace with your campaign email.

5. **Resource buttons** (optional)  
   The “What is depression?” and “What is anxiety?” buttons point to WHO fact sheets. You can change those `href` values to your own resource URLs.

## Run locally

Open `index.html` in a browser, or use a simple server:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve
```

Then visit `http://localhost:8000` (or the port shown).
