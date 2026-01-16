# YouTube-Style Data Analysis

## Task Overview
The goal of this task is to analyze YouTube-style performance data to understand **how viewers behave and why certain videos perform better than others**.  
The focus is on **thinking clearly with data**, not on fancy models, and on turning insights into **real creator actions**.

---

## 1. What data I used

I created a **simulated YouTube-style dataset** with **50 videos**.  
Each row represents one video from either the main creator’s channel or competitor channels.

The dataset includes:
- Views
- Click-Through Rate (CTR)
- Average Watch Time
- Audience Retention at key points (30 seconds, 1 minute, mid-video)
- Video titles
- Thumbnail descriptions (text-based)
- Upload day and upload time
- Content type (tutorial, explainer, vlog, etc.)
- Competitor indicator

The data is **fake but realistic**, since real YouTube Studio data is not publicly available.

---

## 2. What I analyzed

Using this dataset, I analyzed:
- How **titles and thumbnails** affect clicks
- How **early retention** impacts watch time and views
- Which **content types** perform better
- Whether **upload timing** affects performance
- Whether high CTR actually leads to meaningful watching (CTR vs retention)

I used summary statistics and simple visualizations such as bar charts, scatter plots, and heatmaps to identify patterns.

---

## 3. What I discovered

### What seems to be working
- Clear titles and easy-to-understand thumbnails increase CTR.
- Videos with strong retention in the first 30 seconds have higher watch time.
- Tutorial and explainer content performs better than casual vlogs.
- Uploading in the evening or on weekends helps early performance.

### What seems to be failing
- Clickbait titles that don’t match the content cause viewers to leave quickly.
- Slow or unclear introductions reduce retention.
- Videos uploaded very late at night perform poorly.
- Vlog-style content shows inconsistent engagement.

### Why this is happening
- Viewers click videos based on expectations; if those expectations are not met quickly, they stop watching.
- Attention spans are short, so the beginning of the video is critical.
- Educational content works because it provides clear value.
- Viewer mood and availability affect how deeply they engage.

---

## 4. Decisions based on the analysis

### What the creator should START doing
- Clearly explain the value of the video in the first 30 seconds.
- Focus more on tutorial and explainer formats.
- Upload videos during evenings or weekends.

### What the creator should STOP doing
- Stop using clickbait titles that the video does not deliver on.
- Stop slow or unnecessary introductions.
- Stop consistently uploading very late at night.

### What the creator should TEST next
- Test different hook styles in the first 10 seconds.
- Test emotional vs clean thumbnail styles for the same topic.
- Test slightly shorter video lengths (8–10 minutes).

---

## 5. One thing I am NOT confident about

Because this dataset is simulated, the exact CTR and retention values may differ from real YouTube data.  
While the patterns are realistic, real Creator Studio data would be needed to validate precise numerical thresholds.

---

## Final Note
This analysis focuses on **connecting data with human behavior** and turning insights into **clear, testable actions** that creators can actually use.
