# Color Care — Painting, Sacramento

Single-page sample site for a licensed C-33 painting contractor in Sacramento,
California. Built as a free sample for a warm SMS lead.

## Business details

| | |
|---|---|
| Business | Color Care (Google listing: "Color Care Painting") |
| Owner | **Not public** — ask him |
| Phone | (916) 826-7879 |
| Location shown | Sacramento, CA |
| Google listing | https://maps.google.com/?cid=1226099562632377174 |
| HomeAdvisor | https://www.homeadvisor.com/rated.ColorCare.163131557.html |
| Website | None — the listing says "Add website" |

## Licence — verified

Checked against the CSLB database on **2026-10-08**, licence **#1133206**:

- **COLOR CARE** — Sole Ownership
- Issued **02/18/2025**, expires **02/28/2027**
- **This licence is current and active.**
- Classification **C-33 — Painting and Decorating**
- Contractor's bond with **Nationwide Mutual Insurance Company**,
  bond #7901231859, **$25,000**, effective 01/06/2025
- **Workers' compensation** with Employers Compensation Insurance Company,
  policy #EIG635891100, effective 03/23/2026 to **03/23/2027**

Everything in the licensing section traces to that record. Unlike the Noah's Air
build, this licence is clean, so the full trust section is here and it is a
genuine selling point.

Nice corroboration: **his own yard sign carries "LIC #1133206"** — the same
number CSLB returns. He is already advertising it, so the site leans into it.

## His real branding — used, not invented

His Google listing has two photos and both are his own. They gave the whole
design its palette:

| File | What it is |
|---|---|
| `shirt.jpg` | **His** — lime work shirt, "COLOR CARE / FREE ESTIMATES / 916-826-7879" |
| `yard-sign.jpg` | **His** — yard sign with the same logo, phone and LIC #1133206 |

His logo is three red roof peaks over "COLOR CARE" with navy underscores and a
navy chevron. That is **recreated as inline SVG** in the header, and the site
palette is taken straight from it:

- Red `#CE2127` (roofline), navy `#16255C` (underscores/chevron),
  lime `#C2DC1E` (work shirt).

No invented brand colours, and no hand-drawn approximation of someone else's
logo beyond his own shapes.

## Images

`img/` — two of his, four stock (Unsplash): `trim.jpg` (a real painting photo,
used as the hero), `livingroom.jpg`, `bedroom.jpg`, `kitchen.jpg`.

Stock use is disclosed under the gallery and in the footer. Eight stock
candidates were discarded along the way for showing the wrong subject (a
carpenter, a bricklayer, a power drill, houseboats in Kashmir).

Real before/after job photos are the biggest single upgrade available to this
page — he was asked for them.

## What was deliberately not built

- **No reviews section.** His Google listing has **zero** reviews. HomeAdvisor
  shows a 5.0 rating, but with no visible review count or text to attribute, so
  there is nothing honest to quote. Inventing testimonials is not an option.
  Getting real Google reviews is the recommendation instead.
- **No owner name.** Not published anywhere; the site never names a person.
- **No home address.** 18 Marilyn Circle is almost certainly his home. The site
  says "Sacramento, CA" and "north Sacramento" only.
- **Hours left vague** ("Monday to Friday"). The brief said 8am–6pm from
  HomeAdvisor, but his Google listing says **"Opens 9 AM"**. The two disagree,
  so no specific opening time is claimed. Needs confirming.
- **"6 years experience"** is stated — from HomeAdvisor, and consistent with a
  licence issued in 2025 to someone who worked before going out on his own.
  Worth confirming with him; it is the one claim here not from CSLB.
- **Interior only.** His listed services are all interior work, so the site does
  not claim exterior painting. Ask — if he does exteriors, that is a whole
  section missing.

## Design

Distinct from the other painting sites in this collection (Cover All, Rojas,
Santana, Top Class, Mendez, VR, Rodriguez):

- His own red/navy/lime brand palette rather than a chosen one.
- Archivo (display) + Public Sans (body).
- Lime "estimates are free" band lifted from his work shirt.
- Eight sections: hero, stats strip, services, process, work gallery, service
  areas, licensing, contact.
- Full dark mode (system preference plus explicit `data-theme`), sticky header,
  `scroll-margin-top` anchors, reduced-motion respected, inline CSS, no build step.

## Open questions for the client

1. **First name** — so the site can have an owner story.
2. **Job photos**, especially before/after.
3. **Interior only, or exteriors too?**
4. **Hours** — HomeAdvisor says 8am–6pm, Google says opens 9am.
5. **Service area** — confirm, and whether he covers Elk Grove / Roseville.
6. **Merge the duplicate Google listing.** There are two with the same phone
   number — "Color Care Painting" (cid=1226099562632377174) and an empty
   "Color Care" (cid=3630077357404389819). Duplicates split his search presence.
7. **Ask past customers for Google reviews.** Zero reviews is the single biggest
   gap; the licence and the website cannot substitute for social proof.

Note: "Colorcare - House Painting Services" (colorcarepainting.com) is a
**different business in Deltona, Florida**, and another "Color Care" uses
(916) 562-7080. Neither is him.
