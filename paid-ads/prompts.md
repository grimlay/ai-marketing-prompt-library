# 💰 Paid Ads Prompts

---

## 1. Ad Copy Variants (Google / Search)

**The Prompt**
```
Write Google Search ad copy for the following campaign:

Product/offer: [e.g. early bird tickets for a fintech conference in Bangkok]
Primary keyword: [e.g. fintech conference Asia 2026]
USP: [e.g. 300+ speakers, 10,000+ attendees, Asia's largest fintech event]
Audience intent: [e.g. someone actively searching for industry events to attend this year]

Produce 3 responsive search ad sets. Each set should include:
- 5 headlines (max 30 characters each)
- 2 descriptions (max 90 characters each)

Label which headlines are keyword-focused, benefit-focused, or urgency-focused.
```

**Usage Notes**
- The character limits are strict — Claude sometimes goes over by 1–3 characters; always check before uploading
- Labelling headline types helps you ensure Google has variety to test; don't submit 5 urgency headlines
- Add "do not use exclamation marks in more than one headline per set" to keep copy from feeling spammy

---

## 2. LinkedIn Ad Copy (B2B)

**The Prompt**
```
Write LinkedIn Sponsored Content ad copy for the following:

Offer: [e.g. download a whitepaper on embedded finance in Southeast Asia]
Target audience: [e.g. banking executives and fintech decision-makers]
Pain point: [e.g. struggling to evaluate which embedded finance partnerships to prioritise]
CTA: [e.g. Download the report]
Tone: [e.g. authoritative but not academic]

Produce:
- Introductory text: 100–150 words
- Headline: max 70 characters
- Description (shown below image): max 100 characters
```

**Usage Notes**
- LinkedIn ad copy needs to earn attention fast — if the first sentence doesn't hook, revise it before anything else
- The introductory text often over-explains; trim aggressively in review
- Test two versions with different pain points, not just different wording — pain point variation outperforms copy variation in B2B

---

## 3. Audience Messaging Framework

**The Prompt**
```
I'm running paid campaigns targeting three different audience segments for [product/event]. Help me build a messaging framework that maps a distinct value proposition and ad angle to each segment.

Product/event: [description]
Segment 1: [e.g. startup founders in fintech]
Segment 2: [e.g. enterprise bank marketing leads]
Segment 3: [e.g. payments technology vendors]

For each segment, provide:
- Core pain point to address
- Relevant value proposition
- Suggested ad angle (one sentence)
- One example headline
```

**Usage Notes**
- Use this before writing any ad copy — it prevents you from running the same message at different audiences
- The framework is also useful for briefing a media agency or paid specialist
- If segments feel too similar in the output, make your audience descriptions more specific and re-run

---

## 4. Ad Performance Debrief Prompt

**The Prompt**
```
I'm reviewing the performance of a paid campaign. Based on the data below, help me identify what's working, what isn't, and suggest 3 specific optimisations to test next.

Campaign goal: [e.g. registrations for an event]
Platform: [e.g. LinkedIn]
Duration: [e.g. 4 weeks]

Performance data:
- Impressions: [X]
- Clicks: [X]
- CTR: [X%]
- Conversions: [X]
- CVR: [X%]
- Top performing ad: [description]
- Lowest performing ad: [description]

What patterns do you see and what would you test next?
```

**Usage Notes**
- The more specific the data, the better the analysis — include actual numbers, not just "low CTR"
- Claude's optimisation suggestions tend to be directionally correct but generic; use them as a starting checklist, not a final answer
- Follow up with: "Which of these three tests would you prioritise first and why?" to force a recommendation
