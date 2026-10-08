# Marcin Chojnacki portfolio — book preview

Six chapters across 16 pages. One page at a time, with Previous/Next, keyboard arrows, horizontal swipe and a contents dialog. Normal pages fit the screen; content scrolls only when enlarged text or a short viewport makes it necessary. Header, page and navigation occupy separate layout rows, so controls do not overlay content. Uses dynamic viewport height and safe-area insets.

The supplied portrait appears on the opening and closing pages. G24H appears in the Grow24Hub chapter. The cropped Career Hub poster is omitted. Embedded images have no runtime dependencies. Copy remains factual, based on the approved project content and current CV.

The existing website menu/About links lead to `/portfolio/`. Referral code, eligibility gates, country warnings, invitation flow and contact destinations are preserved.

## Verification

Headless Chromium: all 16 pages at 320×568, 360×800, 390×844, 412×915, 768×1024 and 1440×1000. No vertical scrolling at normal text size, horizontal overflow, heading clipping or navigation overlap. Primary body text is 16px or larger.

Also checked 200% text, accessibility scrolling at 320×430, disabled first/last buttons, all six contents jumps, keyboard arrows, bidirectional swipe, reduced motion, and existing referral eligibility/country warning/invitation stop gates.

Phone and desktop screenshots were visually inspected. Physical Android/iOS, live mobile browser chrome and platform-specific safe-area behavior remain unverified. Signed-in contact destination behavior was not tested.

## Publication

Review draft only. Do not merge or publish without Marcin’s approval. Intended live link after publication:

https://grow24hub.com/portfolio/
