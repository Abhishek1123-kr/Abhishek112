# Verification checklist

Date: 2026-10-07

## Source data
- Public GitHub profile checked on 07 Oct 2026.
- Verified profile facts used: B.Tech CSE student at Parul University; 13 repositories; 6 stars; 5 followers; 5 following.
- Public profile links used: GitHub, LinkedIn, LeetCode and portfolio.
- Project table is limited to repositories visibly verified on the public profile page.
- No contribution-city section is included.

## SVG safety
- Five requested SVGs are XML-valid.
- CSS + SMIL only; no JavaScript and no `foreignObject`.
- Portraits/fonts are embedded as data URIs.
- No external image/font references are present.
- SMIL animations begin at `0s` where animation is used.
- CSS entrance rule uses `animation-fill-mode: both`.
- Reduced-motion CSS is included.
- Relative README image paths all end in `?v=1`.
- Social links are outside the SVG image, as GitHub README images do not provide dependable clickable SVG links.

## Rendering checks
- Every SVG has structural no-motion renders.
- Every SVG has named 0s / 2s / 5s / 9s / 13s render snapshots for comparison.
- Every SVG has an img-element render set.
- Browser spot checks were performed on the animated hero, about, stack, ID dashboard and connect sections at 2 seconds.
- Mobile-width spot checks were performed for the rendered image workflow.

## Asset provenance
- `assets/id.png` is the original portrait reference supplied in the conversation and is embedded into every portrait-bearing profile SVG.
- A separate uploaded `right_pointing.png` was not present in the accessible conversation files. The second pointing portrait supplied/generated in this conversation was therefore saved as `assets/right_pointing.png` and used unchanged as the Connect character source.
- Font files are embedded WOFF2 data and their SIL Open Font License 1.1 notices are included in `LICENSE-FONTS.txt`.
