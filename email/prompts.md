# 📧 Email Prompts

---

## 1. Subject Line Generator

**The Prompt**
```
You are a senior email marketer. Generate 10 subject line variants for the following campaign:

Campaign goal: [e.g. drive registrations for a fintech conference]
Audience: [e.g. payments professionals and banking executives]
Key message: [e.g. early bird pricing ends Friday]
Tone: [e.g. urgent but professional, not salesy]

For each subject line, add a one-sentence note explaining the psychological trigger it uses (e.g. curiosity, urgency, social proof, FOMO).
```

**Usage Notes**
- Run this before writing the email body — the subject line should shape the narrative
- Ask for 10 even if you only want 3; the range surfaces angles you wouldn't have thought of
- Look for the variant that matches your list's typical open-rate behaviour (test if you have data)
- Works best when the "tone" instruction is specific — vague tone guidance produces generic output

---

## 2. Nurture Email Writer

**The Prompt**
```
Write a nurture email for the following context:

Product/event: [name and one-line description]
Audience segment: [e.g. leads who downloaded a whitepaper but haven't registered]
Stage in funnel: [e.g. mid-funnel, aware but unconvinced]
Key objection to address: [e.g. not sure if the content is relevant to their role]
Desired action: [e.g. click through to the agenda page]
Tone: [e.g. warm, peer-to-peer, not corporate]
Word count: 150–200 words

Do not use a generic opening like "We hope this email finds you well."
```

**Usage Notes**
- The "key objection" field is the most important — it forces Claude to write an email that actually moves someone rather than just announces
- Specifying word count prevents bloat; most nurture emails should be under 200 words
- If the output feels too polished, add: "Write in a conversational tone, as if from one professional to another"

---

## 3. Campaign Brief → Email Outline

**The Prompt**
```
I'm planning an email campaign. Based on the brief below, generate a 3-email sequence with a suggested send cadence, subject line for each email, and a one-paragraph description of the narrative each email should tell.

Campaign brief:
- Product/event: [name]
- Goal: [e.g. convert warm leads to paid registrations]
- Audience: [description]
- Timeline: [e.g. 3 weeks before event]
- Unique selling point: [what makes this different or valuable]
```

**Usage Notes**
- Use this at the start of a campaign, not at the end — it helps you see the full arc before writing individual emails
- The sequence logic Claude produces is usually sound; the subject lines often need refining
- Good for briefing copywriters or presenting a campaign plan to stakeholders

---

## 4. Personalisation by Audience Segment

**The Prompt**
```
I have the following email and need to adapt it for three different audience segments. Keep the core message and CTA the same, but adjust the opening paragraph and one supporting point to be more relevant to each segment.

Original email:
[paste email]

Segments to adapt for:
1. [e.g. startup founders]
2. [e.g. enterprise bank executives]
3. [e.g. payments technology vendors]
```

**Usage Notes**
- Best used after you have a strong base email — don't try to personalise a weak one
- Claude will sometimes over-adapt and change the CTA; check all three versions carefully
- The output is a good starting point for dynamic content blocks if your ESP supports them
