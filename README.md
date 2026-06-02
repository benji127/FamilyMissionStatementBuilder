# 7 Habits AI Playbook Collection

A set of interactive, AI-powered learning tools built around Stephen Covey's *The 7 Habits of Highly Effective People* and *The 7 Habits of Highly Effective Families*. Each playbook is a single self-contained HTML file — no dependencies, no build step, no backend required.

---

## Live Tools

| File | Description |
|---|---|
| `7habits-playbook.html` | Personal Victory vs Public Victory — all 7 habits with AI chat per habit |
| `circle-playbook.html` | Circle of Influence vs Circle of Concern — comparison + situation analyser |
| `family-mission-playbook.html` | 4-step family mission statement builder for a 3-member family |

---

## What Each Tool Does

### 7 Habits Playbook
- Browse all 7 habits filtered by Personal Victory, Public Victory, or Renewal
- Click any habit to open a modal with quick-tap prompts and a free-text AI chat
- AI explains, gives real-world examples, and offers reflection prompts on demand

### Circle of Influence & Circle of Concern
- Animated visual showing the two circles
- Side-by-side comparison of language, energy, and mindset for each circle
- Two independent AI panels — one per circle
- **Situation Analyser** — describe a real stressor, AI identifies what you can and can't control, and gives you a first action step

### Family Mission Statement Builder
A guided 4-step flow:

1. **Learn** — Covey's framework and principles explained, with AI Q&A
2. **Examples** — Six sample statements modelled on the book's three-element structure, with AI analysis
3. **Build** — Enter three family members, select core values, describe your ideal home and contribution. AI generates a personalised statement with a framework breakdown
4. **Finalize** — Poster-style display of your completed statement, plus AI chat to refine it or build rituals around it

---

## How to Use

### Run locally
Just open any `.html` file in a browser. No installation needed.

```bash
open family-mission-playbook.html
```

### Deploy to the web (free options)

**Netlify Drop** — fastest
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop the HTML file
3. Get a live URL instantly

**GitHub Pages**
1. Push this repo to GitHub
2. Go to Settings → Pages → set source to `main` branch
3. Your tools are live at `https://yourusername.github.io/repo-name/`

**Tiiny.host**
1. Go to [tiiny.host](https://tiiny.host)
2. Upload the HTML file
3. Share the generated link

---

## Sharing on Social Media

**Instagram**
- Add your hosted URL to your bio or use a link-in-bio tool (Linktree, etc.)
- Use the Stories **link sticker** to drive direct traffic
- Create a carousel walking through the tool's steps with a CTA

**Facebook**
- Paste the hosted URL directly into a post — link previews automatically
- Share in personal development, parenting, or productivity groups
- Use as a resource in a Facebook Event or workshop

**WhatsApp / Telegram**
- Drop the link into family groups or community chats — high click-through with link previews

**Embed on a website**
```html
<iframe 
  src="YOUR_HOSTED_URL" 
  width="100%" 
  height="800px" 
  frameborder="0">
</iframe>
```

---

## Tech Stack

- Vanilla HTML, CSS, JavaScript — no frameworks
- [Anthropic Claude API](https://www.anthropic.com) — powers all in-tool AI responses
- Google Fonts — Cormorant Garamond, Lora, Karla, Jost, Playfair Display, DM Sans

> **Note:** The AI features require a valid Anthropic API key configured in the environment. If you are self-hosting or forking this project, update the fetch call in each file to pass your own key via a secure backend proxy rather than exposing it client-side.

---

## Inspired By

- *The 7 Habits of Highly Effective People* — Stephen R. Covey
- *The 7 Habits of Highly Effective Families* — Stephen R. Covey

---

## License

MIT — free to use, share, and adapt with attribution.
