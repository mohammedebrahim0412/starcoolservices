# Star Cool Service — SEO launch checklist

The website is already optimised (titles, descriptions, structured data, FAQ data,
fast images, mobile layout). These steps finish the job once the site has a domain.

## 1. Website address — done

Live at **https://starcoolservices.vercel.app/**. Canonical tag, share images, structured data, `sitemap.xml`
and `robots.txt` all use this address. If you later buy your own domain (e.g.
`starcoolservice.in`), replace `https://starcoolservices.vercel.app` in `index.html`, `robots.txt` and
`sitemap.xml`, and add the domain in Vercel → Project → Settings → Domains.

## 2. Google Business Profile — the biggest factor for "AC service near me"

For local searches, Google mostly ranks the **map listing**, not the website.

- [ ] Create/claim the profile at <https://business.google.com> and complete verification.
- [ ] Business name exactly: **Star Cool Service** (no extra keywords — Google penalises that).
- [ ] Primary category: **Air conditioning repair service**. Add secondary categories:
  *Appliance repair service*, *Refrigerator repair service*, *Washing machine repair service*,
  *Air conditioning contractor*.
- [ ] If you don't have a shop customers visit, choose **service-area business**, hide the
  address, and list the Chennai areas you actually cover.
- [ ] Phone: **+91 98413 74019** — same as the website. Website link: your domain.
- [ ] Opening hours, services list (AC installation, AC repair, gas checking, fridge repair…),
  and a short description mentioning 20+ years and Chennai.
- [ ] Upload real photos: technicians at work, vans/tools, before/after. Add new ones monthly.
- [ ] **Ask every happy customer for a Google review** (send the review link on WhatsApp after
  each job). Reply to every review. Steady, genuine reviews are the strongest ranking signal.

## 3. Search engines

- [ ] **Google Search Console** (<https://search.google.com/search-console>): add the domain,
  submit `sitemap.xml`, then use *URL inspection → Request indexing*.
- [ ] **Bing Webmaster Tools** (<https://www.bing.com/webmasters>): import from Search Console.
- [ ] Test the structured data: <https://search.google.com/test/rich-results>
- [ ] Test speed: <https://pagespeed.web.dev> (aim for green on mobile).

## 4. Listings and consistency (citations)

- [ ] List the business on **JustDial, Sulekha, IndiaMART, Bing Places, Apple Business Connect**
  and Facebook/Instagram.
- [ ] Use **exactly the same name, phone and area everywhere** ("NAP consistency").
- [ ] Link each listing back to your website.

## 5. Keep it growing

- [ ] When you have real service areas, fill `SERVICE_AREAS` in index.html (they appear on
  the page) and add them to `areaServed` in the structured-data block.
- [ ] Add new genuine reviews to the page (both the HTML cards and the `REVIEWS` list).
- [ ] Later: separate pages such as "AC repair in Chennai" or area pages, each with unique
  content, help you rank for more searches.

> No one can guarantee the #1 position, and anyone who promises it is not being honest.
> The steps above are what Google itself recommends, and together they give Star Cool
> Service the best chance of ranking at the top for Chennai appliance-service searches.
