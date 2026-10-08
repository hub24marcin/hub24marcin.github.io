# Marcin Chojnacki portfolio

Review v2: Six responsive chapters at `/portfolio/`. Plain HTML, CSS and JavaScript; the approved portrait, Career Hub image and G24H brand image are embedded, so the page has no runtime dependencies.

Links from the existing hub menu and About section lead to the portfolio. Referral code, eligibility gates, country warnings and invitation flow are preserved. The current site’s LinkedIn, Linktree and Ko-fi destinations are reused. No personal phone or email is published.

Content is grounded in the existing hub, the current Grow24Hub project direction and Marcin’s CV updated on 7 October 2026. No invented statistics or testimonials.

## Verification

Headless Chromium checks passed at 320×568, 360×800, 390×844, 412×915, 768×1024 and 1440×1000:

- Exactly one visible page; no horizontal overflow or heading clipping.
- Normal body copy 16px or above; usable at 200% root text size.
- Previous/Next, contents menu, arrow keys and page counter.
- Horizontal swipe changes page; vertical gesture does not.
- Reduced-motion preference disables animation.
- Persistent mobile navigation stays visible while scrolling. Dynamic bottom spacing lets all content clear the dock at 100% and 200% text enlargement.
- Supplied portrait on page 1, Career Hub visual on page 3 and G24H on page 4.
- Exact current quality review title; previous product support role and three separate degree entries.
- Swipe guidance on the first page only; simplified return link and secondary Ko-fi support.
- Existing eligibility result, country disclosure/warning and after-referral stop gate.

The static page was visually inspected with phone and desktop screenshots. No physical Android or iOS device testing was available. External contact destinations are reused from the approved site; signed-in destination behavior was not tested.

## Publication

This is a review draft. Merge only after Marcin approves publication. After deployment, the intended shareable LinkedIn portfolio URL is:

https://grow24hub.com/portfolio/

An unpublished source branch is not a live website URL.
