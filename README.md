# LeCut Construction: landing page preview

A review copy of the paid-ads landing page NTD Digital built for LeCut Construction (lecut.co, CSLB #1080990). It is for client review only. The live page will be installed on lecut.co.

## Preview links

| Version | Link |
|---|---|
| Kitchen (default) | https://ntddigital-geo.github.io/LeCutCo/ |
| Bathroom | https://ntddigital-geo.github.io/LeCutCo/?svc=bath |
| ADU | https://ntddigital-geo.github.io/LeCutCo/?svc=adu |
| Garage conversion | https://ntddigital-geo.github.io/LeCutCo/?svc=garage |

Add `&h=2` to any link to see the "Burned by a Contractor Before?" line. The bar at the top of the page switches versions. Ad visitors on lecut.co won't see that bar.

## What works differently in the preview

- **The form is display-only.** It checks the fields and shows a "Preview only" note. Nothing is sent. On lecut.co it sends requests into LeCut's existing Contact form.
- **Photos:** the new project photos load from `lp-photos/` in this repo. On lecut.co they load from LeCut's media library once uploaded.
- **Search engines:** the page is marked `noindex, nofollow`.

## Turn on GitHub Pages

Settings > Pages > Build and deployment > Source: **Deploy from a branch**, Branch: **gh-pages**, folder **/ (root)** > Save. The site appears at https://ntddigital-geo.github.io/LeCutCo/ within a few minutes.

## Updating

`index.html` is generated from the install file `lecut-paid-landing-page.html` in NTD Digital's LeCut client folder, with the internal install notes removed. Rebuild it from there instead of editing it here.
