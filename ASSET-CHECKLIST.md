# Content Acquisition Checklist — Jaya Abadi Las Landing Page

The UI/layout is done. Everything below is real-world content that must be
collected from the business owner before this page can go live. Until each
item arrives, the page uses the placeholder noted in the "Current placeholder"
column — replace in `Landing Page.html` when the real asset is ready.

---

## 1. Required Assets
*The page cannot go live (or will mislead customers) without these.*

| Asset | Why it matters | Used in | Current placeholder | Priority |
|---|---|---|---|---|
| **Real WhatsApp business number** | Every CTA on the page points here. A wrong/placeholder number means **zero leads** convert. | Navbar, Hero, CTA banner, Footer, Floating WA button (`6281234567890` / `0812-3456-7890`, 6 locations) | Fake number `6281234567890` | 🔴 Critical |
| **Business address (street-level)** | Customers want to know if you're local before they message. Needed for Google Maps embed/link and schema markup later. | Footer contact block | Generic "Depok, Jawa Barat" | 🔴 Critical |
| **Operating hours (confirmed)** | "Buka 7 Hari, 08:00–17:00" is currently an assumption — if wrong, it sets a false expectation and damages trust on first contact. | Trust section, Footer | Assumed "Setiap hari 08:00–17:00" | 🔴 Critical |
| **Logo / brand mark** | Current logo is a generic flame icon in a box — not a real identity. A real logo (even simple wordmark) makes the business look established. | Navbar, Footer | Lucide `flame` icon | 🟡 High |
| **Legal/registered business name** (if different from "Jaya Abadi Las") | Affects footer copyright line and any future invoicing/legal text. | Footer copyright | "Jaya Abadi Las" (assumed) | 🟢 Medium |

---

## 2. Trust Assets
*These make the "Mengapa Memilih Jaya Abadi Las" section and overall credibility honest and verifiable.*

| Asset | Why it matters | Used in | Current placeholder | Priority |
|---|---|---|---|---|
| **Google Business Profile URL** | The "Lihat di Google Maps" link currently points to a generic search query, not the actual listing. If the listing doesn't exist or doesn't match, this looks deceptive. | Trust card #1 (rating) | Generic search: `google.com/maps/search/?q=Jaya+Abadi+Las+Depok` | 🔴 Critical |
| **Verified Google rating + review count** | "4.8 / 5" and "48 Ulasan" are placeholder numbers from the brief — if the real numbers differ, this is a false claim that can hurt trust (and violates "no unproven claims" instruction). | Trust cards #1–2 | Hardcoded "4.8" / "48" | 🔴 Critical |
| **2–3 short customer testimonial quotes** (with first name + area, e.g. "Pak Budi, Cinere") | A number ("48 reviews") without a single visible quote feels abstract. One real sentence from a real customer is far more convincing than a stat. | New section between Trust and Services (not yet built) | None — section doesn't exist yet | 🟡 High |
| **Years in business / founding year** | Currently not stated anywhere. "Tim Berpengalaman" is vague; a concrete number ("Berdiri sejak 20XX") is far more credible. | About section, Trust card | None | 🟡 High |
| **Photo of the actual workshop/team** | The About section currently reuses a staircase photo as a stand-in for "company branding visual." A real workshop or team photo builds far more trust than a project photo. | About section (left image) | `images/tangga-spiral-5.jpg` | 🟡 High |
| **Any certifications, supplier brand partnerships, or notable clients** (only if real) | Per the brief: do not invent "Nomor 1 / Terbaik / Garansi" — but if there's something real (e.g. "Mitra resmi [brand] baja ringan"), it's a strong trust signal. | About / Trust section | None | 🟢 Medium |

---

## 3. Portfolio Assets
*The "Bukti Hasil Pekerjaan Kami" section is the proof layer — right now it's skewed to one product.*

| Asset | Why it matters | Used in | Current placeholder | Priority |
|---|---|---|---|---|
| **Pagar Besi photos** (3–5, finished installs, good lighting) | This is one of the 3 primary services but has **zero** real photos anywhere on the page. | Portfolio masonry, ideally also primary service card | None | 🔴 Critical |
| **Kanopi photos** (3–5) | Same — primary service with no visual proof. | Portfolio masonry | None | 🔴 Critical |
| **Teralis photos** (3–5) | Same — primary service with no visual proof. | Portfolio masonry | None | 🔴 Critical |
| **Folding Gate / Rolling Door photos** (1–2 each) | Secondary services currently represented only by generic icons. | Services secondary grid, Portfolio | Lucide icons only | 🟡 High |
| **Konstruksi Baja / Menara Air / Kusen Aluminium photos** (1–2 each) | Same as above — currently icon-only. | Services secondary grid, Portfolio | Lucide icons only | 🟢 Medium |
| **Additional Tangga Spiral photos in better resolution** | Current 5 photos are low-resolution screenshots (some are stock/catalog images, not the company's own work — verify authenticity). | Hero, About, Portfolio (5 instances) | `images/tangga-spiral-1.jpg` to `-5.jpg` | 🟡 High |
| **Before/after pairs (optional but powerful)** | Strong conversion driver for fabrication/renovation work — shows transformation. | Portfolio (future enhancement) | None | 🟢 Medium |
| **Process/work-in-progress photos** (welding, fabrication in workshop) | Supports the "Proses Kerja Kami" timeline with real imagery instead of icons only. | Process section (future enhancement) | Numbered circles only | 🟢 Low |

---

## 4. Conversion Assets
*Anything that affects whether a visitor actually clicks "Chat WhatsApp."*

| Asset | Why it matters | Used in | Current placeholder | Priority |
|---|---|---|---|---|
| **Pre-filled WhatsApp message copy review** | Messages are currently in Indonesian and reasonable, but the owner should confirm tone/wording matches how they actually want to be approached (formal vs. casual). | All `wa.me` links (6 messages) | Generic Indonesian templates | 🟡 High |
| **Response time expectation** (e.g. "Balas dalam 30 menit") | Sets expectations and reduces bounce — visitors are more likely to message if they know they'll get a fast reply. | Near CTA banner / floating button | Not stated | 🟢 Medium |
| **Service area confirmation** | "Sawangan, Cinere, Beji, Pancoran Mas, Bojongsari, Tapos, Seluruh Depok" was provided in the brief — confirm these are accurate and complete (any areas outside Depok, e.g. parts of Jakarta Selatan/Tangerang, served too?). | Footer "Area Layanan" | List from brief (assumed accurate) | 🟢 Medium |
| **Pricing range or starting price indicators** (optional, only if owner is comfortable) | "Harga Transparan" is claimed in the About checklist but no pricing signal exists anywhere. Even a rough "mulai dari Rp X/meter" for Pagar Besi reduces friction for price-sensitive visitors. | Services section (future) | None — claim only | 🟢 Medium |
| **Alternative contact (phone call) confirmation** | Phone number `0812-3456-7890` is shown but currently a placeholder — must be a number that's actually answered for calls, not just WhatsApp. | Navbar, Footer | Placeholder number | 🔴 Critical |
| **Favicon / browser tab icon** | Small detail but affects perceived professionalism in browser tabs and bookmarks. | `<head>` (not yet added) | None | 🟢 Low |
| **Open Graph image** (for WhatsApp/social link previews) | When someone shares the page link in WhatsApp/Instagram, a proper preview image with logo/photo dramatically increases click-through. | `<head>` meta tags (not yet added) | None | 🟡 High |

---

## Placeholder Content Strategy (until real assets arrive)

Goal: keep the page honest and functional without looking broken or making
unverifiable claims, while real assets are collected.

1. **Numbers (phone, WhatsApp, address, hours, rating, review count)**
   - Keep clearly-fake placeholder values (`0812-3456-7890`, `6281234567890`,
     "4.8 / 5", "48 Ulasan") **only in a non-public/staging copy**.
   - Do **not** publish the live site until at minimum the WhatsApp number,
     phone number, and address are real — these are the entire purpose of
     the page.
   - If the real Google rating/review count isn't available yet, **remove
     the stat entirely** rather than publish an invented number — replace
     the card with a neutral one (e.g. "Konsultasi Gratis" / "Respon
     Cepat") until the real figure is confirmed.

2. **Portfolio photos (Pagar Besi, Kanopi, Teralis — currently zero)**
   - Short-term: ask the owner for **even phone-camera photos** of 3–5 past
     jobs per category — quality can be improved later, but *some* real
     photo beats zero.
   - If truly nothing exists yet for a category, **remove that category
     from the masonry** rather than leaving an empty/grey block — an
     incomplete-but-honest gallery (e.g. 5 real Tangga Spiral photos) is
     more trustworthy than a padded one with placeholders.
   - The current "Lihat Proyek Lainnya" WhatsApp CTA card in the portfolio
     grid is the interim solution — it converts the *absence* of photos
     into a conversation starter. Keep this card until at least 2 of the 3
     primary categories have real photos.

3. **Testimonials**
   - Do not write fabricated quotes. If the owner has WhatsApp/SMS threads
     with positive feedback, ask permission to paraphrase 2–3 short quotes
     with first name + neighborhood.
   - Until then, omit the testimonial section entirely rather than building
     it with placeholder names.

4. **About section photo**
   - Interim: keep the current staircase photo (it's at least a real
     finished installation) but relabel the caption neutrally — avoid
     implying it represents "the workshop" if it's actually a client site.
   - Swap for an actual workshop/team photo as soon as available — this is
     a high-impact, low-effort win (one good photo).

5. **Icons-only secondary services** (Folding Gate, Rolling Door, Menara
   Air, Konstruksi Baja, Kusen Aluminium, Railing Tangga)
   - Acceptable as a long-term pattern per the original design brief
     ("monochrome icons" was an approved option) — not blocking for launch.
   - Upgrade opportunistically: as soon as 1 photo exists for any of these,
     consider promoting that service into the portfolio masonry.

6. **Favicon / Open Graph image**
   - Quick interim fix: generate a simple monogram favicon from "JAL" using
     the existing gold (`#c9a35f`) on dark (`#0c0c0e`) palette — takes
     minutes and removes the "generic browser icon" tell.
   - OG image can reuse the hero photo + logo overlay until a dedicated
     graphic is designed.

---

## Suggested Acquisition Order (fastest path to a launchable page)

1. Real WhatsApp number + phone number + address + hours *(blocks launch)*
2. 3–5 phone photos each of Pagar Besi, Kanopi, Teralis jobs
3. Confirm/replace Google rating + review count (or remove the stat)
4. One workshop/team photo for About section
5. Favicon + OG image
6. Testimonials (if available with permission)
7. Everything else (secondary service photos, pricing signals, etc.)
