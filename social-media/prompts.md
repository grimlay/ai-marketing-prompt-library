# 📱 Social Media Prompts

---

## 1. LinkedIn Post (Professional Announcement)

**The Prompt**
```
Write a LinkedIn post announcing the following:

What's being announced: [e.g. speaker lineup for a fintech conference]
Key detail to highlight: [e.g. 3 central bank governors confirmed]
Audience: [e.g. financial services professionals]
Tone: [e.g. credible, energising, not hype-y]
Length: 100–150 words
End with a soft CTA: [e.g. link to full agenda in comments]

Avoid: bullet points, excessive emojis, generic openings like "Excited to announce"
```

**Usage Notes**
- LinkedIn rewards posts that open with a strong first line — Claude sometimes buries the lead; move it up if needed
- "Avoid bullet points" is important — lists perform poorly on LinkedIn compared to flowing prose
- The no-emoji instruction is optional depending on your brand voice; remove it for consumer-facing brands

---

## 2. Instagram Caption (Event or Product)

**The Prompt**
```
Write an Instagram caption for the following post:

What the image shows: [e.g. venue reveal for a conference in Bangkok]
Mood/vibe: [e.g. aspirational, warm, Southeast Asian energy]
Brand voice: [e.g. professional but human]
Include: a question to encourage comments
Hashtags: suggest 8–10 relevant hashtags to append at the end
Length: 80–100 words before hashtags
```

**Usage Notes**
- Always describe the image specifically — generic image descriptions produce generic captions
- The question prompt boosts comment rates; Claude usually places it well near the end
- Review hashtags manually — Claude's suggestions are a starting point, not final

---

## 3. Twitter/X Thread Outline

**The Prompt**
```
Create a Twitter/X thread outline on the following topic:

Topic: [e.g. why embedded finance is changing SME banking]
Audience: [e.g. fintech professionals and startup founders]
Angle: [e.g. contrarian — the trend is overhyped in some areas]
Number of tweets: 6–8
Format: tweet number, one-sentence hook per tweet, and a note on what evidence or example to include

First tweet must work as a standalone hook even if someone doesn't read the thread.
```

**Usage Notes**
- Threads work best with a clear point of view — use the "angle" field to give Claude something to argue
- Ask for an outline first, not finished tweets — it's faster to refine structure before writing copy
- The standalone hook instruction is critical; many threads fail because the first tweet is too dependent on context

---

## 4. Caption Repurposing (One Piece → Three Platforms)

**The Prompt**
```
I have the following content and need captions adapted for three platforms. Keep the core message consistent but adjust length, tone, and format for each platform.

Original content summary: [paste summary or key message]

Adapt for:
1. LinkedIn (professional, 100–130 words, no hashtags)
2. Instagram (warmer tone, 70–90 words, suggest 6 hashtags)
3. X/Twitter (punchy, under 240 characters, standalone)
```

**Usage Notes**
- This is the most efficient prompt in this section — one input, three outputs
- LinkedIn and Instagram versions often need light editing to match brand voice; the X version usually needs more
- Add "do not repeat the same opening phrase across all three" to prevent lazy output
