# Responsive behavior, design parameters, states and actions

Page: AI Opportunity Audit (/services/ai-opportunity-audit/)

## 1. Views and grid

| | Desktop | Mobile |
|---|---|---|
| Frame | Page/Desktop-1440, 1440 px | Page/Mobile-390, 390 x 1637 px |
| Layout grid | 8 columns, stretch | 4 columns, stretch |
| Side margins | 150 | 20 |
| Gutter | 20 | 16 |
| Content width | 1140 | 350 |

Mobile: columns collapse into one, long titles wrap and are never cropped.

## 2. Colors (Figma variables)

| Variable | HEX | Use |
|---|---|---|
| Text | #EEF4EF | headings, paragraphs |
| Text secondary | #B9C7BE | tagline, footer, default link and header button text |
| Accent / 100 | #3DDC5A | primary button, lines, "What you receive:" label |
| Accent / 15 | #00E044 at 15% | translucent accent surface |
| Accent hover | #6CF08A | hover, link hover |
| Text on accent | #001400 | text on the primary button |
| Background | #050A07 | page background |

Contrast: #001400 on #3DDC5A is about 10.5:1. Text #EEF4EF on #050A07 is about 17.9:1, Text secondary on #050A07 about 11.4:1.

## 3. Typography (Montserrat, fallback Arial, Helvetica, sans-serif)

Format: size / line height, px.

| Style | Desktop | Mobile |
|---|---|---|
| H1 | 56 / 64 | 40 / 48 |
| Tagline | 16 / 24 | 16 / 24 |
| WhatYouReceive  | 16 / 24 | 16 / 24 |
| Header-Brand | 24 / 32 | 14 / 18 |
| Button-Primary | 16 / 24 | 16 / 24 |
| Button-Header | 16 / 24 | 14 / 20 |
| Footer-TextAndLinks | 16 / 24 | 16 / 24 |
| Footer-Brand | 16 / 24 | 16 / 24 |

## 4. Components

| Component | Parameters |
|---|---|
| Buttons (primary and header, desktop) | height 56, padding 24 x 16, gap 10, corner radius 32, auto layout, width hug contents |
| Primary button (mobile) | text 16 / 24, [впиши ширину и высоту] |
| Header button (mobile) | text 14 / 20, [впиши высоту и padding] |
| Link | default, hover and focus states, see section 6 |

## 5. Spacing between blocks (auto layout)

| Gap | Desktop | Mobile |
|---|---|---|
| Hero to body | 16 | auto |
| Body to CTA | 56 | 16 |
| CTA to footer | auto | 32 |

Scene behavior:
- Desktop: panoramic windows, city, sky, sun, plant. Dark gradient under the text, bottom blends into the page background.
- Mobile: scene cropped to fit window, city and plant. Gradient at the bottom blends into the page background. Text and CTA do not lie on the photo.
- Wordmark "iBusiness System" is a separate text layer behind the content. It never overlaps the H1, CTA or the plant.
- Touch targets are at least 44 px high.

## 6. States (shown on desktop; mobile has no hover)

| Element | Default | Hover | Focus |
|---|---|---|---|
| Primary button | fill #3DDC5A, text dark | fill #6CF08A | white outline around the button |
| Header button "Start a Project" | dark fill, thin border, text #B9C7BE | darker fill, text #3DDC5A | [впиши, если сделан] |
| Link | text #B9C7BE | text #6CF08A | green outline frame around the link |

## 7. Actions

| Element | Action |
|---|---|
| Start a Project | Goes to #start, same as on the home page |
| Additional Services | Returns to the "Additional Services" block on the home page. The anchor is not invented here, the target block is named for the developer |
| Discuss Your Business Idea | Opens https://wa.me/66984407304?text=Hello%21%20I%20would%20like%20to%20discuss%20AI%20Opportunity%20Audit%20for%20my%20business. WhatsApp opens with the prepared text, the message is not sent automatically |
| Email AI Business Systems | mailto:b2b.volodymyr.thai@gmail.com |
| Denmark +45 50 27 64 39 | tel:+4550276439 |
| WhatsApp +66 98 440 7304 | https://wa.me/66984407304 |