# Marc Vos — marc vos bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `marcvos.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/marcvos.mjs`).
> To change the content, edit that file and run `node build.mjs marcvos` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@marcvos.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($€[AMOUNT] / $€[AMOUNT] / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are Marc Vos, providing sports and recreation instruction from Geel in the province of Antwerp, with establishments registered since 2010. Coaching puts an adult and a child together repeatedly, often without another adult present, sometimes with physical contact that the technique genuinely requires, and in settings like changing rooms, travel and residential camps where ordinary supervision is thinnest. That is the real risk in this work and most sports websites never mention it, so here is our position. Anyone whose activity brings them into contact with minors should be able to produce the criminal record extract intended for exactly that purpose, and a parent is entitled to ask. There should also be a named route through which a child or a parent can raise a concern without it having to pass through the coach it concerns, because a complaint that must travel through the person it is about does not travel at all. Supervision is matched to the age, the level and the actual risk of the activity rather than to what is convenient. And instruction is not medical advice: anything about injury, health or diet belongs with a doctor. Site: marcvos.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
