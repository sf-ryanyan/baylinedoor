# Bayline Door Co.

**A complete website template for a US local service business, built around a garage door contractor.**

🔗 **Live demo — [sf-ryanyan.github.io/baylinedoor](https://sf-ryanyan.github.io/baylinedoor/)**

---

## 📌 The Problem

Most local service businesses in the US — garage doors, plumbing, electrical, remodeling — **do not have a real website.** They run on word of mouth and referrals, and online they effectively do not exist.

But customer behavior has already moved. When a door jams at 11pm, the first thing anyone does is pick up a phone and search. **If you don't come up, you don't get the call.**

The two options on the market don't fit this kind of business:

| | Why it falls short |
|---|---|
| **DIY site builders** (Wix, Squarespace) | Generic templates with no understanding of the trade. The owner still has to become a marketer. |
| **Local design agencies** | $2,000–3,000 and up — too high a bar for a small contractor |

---

## 🎯 What This Template Solves

The goal was not "build a good-looking site." It was to solve three specific problems a contractor actually has.

### ① Catch the search traffic

Make the business findable by the person searching *garage door repair near me* at midnight.

### ② Divert the price-shopping calls

The calls that drain a contractor's day aren't the emergencies — those are good business. It's the **price-shopping calls**: measuring questions, product explanations, a quote, and often no sale at the end.

This site routes that group to a form instead. They submit sizes and photos, and the owner handles them in one batch when it suits him.

### ③ Stop the calls that shouldn't happen

A large share of inbound calls turn out to be a dead remote battery or a misaligned safety sensor. The site includes a self-help section that **deliberately teaches customers to fix those themselves** — it saves both sides time, and it builds more trust than any self-promotion would.

---

## 🧭 Site Structure

| Section | Purpose |
|---|---|
| **Hero** | Full-bleed photography, positioning line, two entry points |
| **Two paths** | *I need a new door* / *My door is broken* — each jumps straight to the form and pre-selects the matching fields |
| **New doors** | Scope of work, four door styles, three-step process |
| **Full-width band** | One industry fact — a breathing point between sections |
| **Repair** | What's repairable, and a plain statement of when it isn't worth repairing |
| **Fix it yourself** | Six things a homeowner can solve in ten minutes, plus three they must never attempt |
| **Quote form** | The only card on the page; fields change with the selected path |
| **How we work** | Four commitments: licensed, written estimate first, multiple manufacturers, written warranty |

---

## ⚙️ Design Decisions

This is where the template differs from a generic one.

**The form changes with the path.**
A new door and a repair need completely different information. New door: opening size, bay count, style, budget range. Repair: fault type, door size, opener make and model, urgency. **One generic form captures none of it.**

**No hard prices anywhere.**
Advertising "$280 spring replacement" and then charging $400 can constitute false advertising in the US. Every figure on the page is marked as preliminary, subject to a written estimate after inspection.

**Self-help as reverse marketing.**
Telling a customer what *doesn't* need paying for is more persuasive than any claim the business could make about itself — and it genuinely cuts wasted calls.

**The licence number appears three times.**
California requires licensed contractors to display their licence number in advertising, and a website is advertising. The template builds that in by default rather than leaving it to the user to remember.

**Emergencies route to the phone, not the form.**
Broken springs, doors off their track, snapped cables — the page explicitly tells those visitors to call instead of submitting a form. **Safety ranks above conversion.**

---

## 🎨 Design & Build

- **Type** — Archivo variable font with the width axis widened, large display sizes, generous tracking and leading
- **Palette** — warm graphite, warm off-white, low-saturation bronze. **No pure black**: it renders harshly on screen and reads cheap
- **One card on the whole page** (the quote form). Everything else is separated by hairlines and whitespace
- **A single HTML file.** No framework, no build step, no dependencies beyond Google Fonts
- **Fully responsive**, single column on mobile
- **~810 KB total**, including all seven images

---

## 🔧 Using It As a Template

A comment block at the top of `index.html` lists everything to replace before any real use:

```
business name · phone · email · licence number · service area · hours
```

**On the form:** it is wired for Netlify Forms. **GitHub Pages cannot process form submissions** — deploy to Netlify, or swap in a service such as Formspree.

```
baylinedoor/
├── index.html
└── images/          7 photographs
```

---

## 🙏 Acknowledgements

- **Archivo** by Omnibus-Type, via Google Fonts — SIL Open Font License
- Photography generated with AI

---

## ⚠️ Disclaimer

**Bayline Door Co. is a fictional company created for demonstration purposes. It is not a real business.**

- All contact details are placeholders. The phone number uses the **555-01xx** range, reserved for examples in North America, and reaches no one.
- The licence number `CSLB #1XXXXXX` is a placeholder. **California law requires licensed contractors to display a genuine licence number in advertising** — it must be replaced before any real use.
- All images are AI-generated and do not depict real projects or real products.
- Industry information on the page — repair guidance, safety notes, insulation advice — is general reference only and **does not constitute professional advice.** Work involving springs, cables and tracks is genuinely dangerous and should be carried out by a licensed technician.
- This project is not affiliated with, endorsed by, or connected to any real garage door company or manufacturer.

---

## 👤 About

Built by **Ryan Yan**, a data analyst.
