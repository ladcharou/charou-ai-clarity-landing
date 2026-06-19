# Charou AI Clarity Landing Page

A static, conversion-focused landing page for Charou's practical AI education offer.

## Strategy Summary

- Page goal: convert visitors into leads for a 1:1 Practical AI Clarity Session.
- Target visitor: beginners, working professionals, creators, students, or small business owners who are curious about AI but overwhelmed by tools and hype.
- Core promise: turn AI confusion into a clear, practical action plan.
- Primary offer: Practical AI Clarity Session.
- Primary CTA: Book your AI clarity call.
- CTA link status: placeholder mailto link. Replace before launch.
- Proof status: honest placeholders only. No fake testimonials, client names, revenue, logos, guarantees, or scarcity were added.

## Files

- `index.html` — semantic static page markup
- `styles.css` — responsive Vercel-inspired premium AI/tech design
- `README.md` — project notes and deployment instructions
- `strategy.md` — extracted brand inputs, assumptions, page strategy, and version 2 recommendations

## Local Preview

From this folder:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## Replace Before Launch

1. Replace the CTA placeholder email:
   - Current: `replace-with-your-email@example.com`
   - Recommended: Calendly, Tally, Typeform, WhatsApp, or a real email address.

2. Replace Open Graph URL:
   - Current: `https://replace-with-your-domain.example`
   - Use the final Vercel/custom-domain URL.

3. Add real proof:
   - testimonials with permission
   - case studies
   - projects built
   - credentials
   - content links
   - measurable student/client outcomes

4. Add a real profile photo or brand visual if desired.

## Vercel Readiness

This is a static site. Vercel can deploy it with default settings:

- Framework preset: Other
- Build command: leave empty
- Output directory: leave empty or `.`

## Manual GitHub Push

If the connector cannot create a repo automatically:

```bash
git init
git add .
git commit -m "Add Charou AI clarity landing page"
git branch -M main
git remote add origin <repo-url>
git push -u origin main
```

## Manual Vercel Deploy

1. Go to https://vercel.com/new
2. Import the GitHub repo.
3. Choose Framework Preset: Other.
4. Leave build command empty.
5. Deploy.
