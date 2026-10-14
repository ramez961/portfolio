# Ramez — Web design portfolio

A responsive, buildless web design portfolio for [ramez961](https://github.com/ramez961). The positioning brings marketing, identity, photography, and motion together as supporting skills for complete website experiences. The page showcases curated repository-based websites, five website case studies, and a repository archive. It refreshes the public repository list from GitHub on each visit, with pagination, search, filters, and an offline fallback. The original Khalik Fahem version is excluded from the showcase; `Khalik-Fahem-2` is displayed as **Khalik Fahem**. No credentials are exposed.

## Preview

Open `index.html` directly, or serve the repository root with any static web server. No package installation or build is needed.

## GitHub Pages

The repository root `index.html` is the deployable page. In repository Settings → Pages, select **Deploy from a branch**, **main**, and **/(root)**. The repository administrator must enable this setting. The resulting URL is normally `https://ramez961.github.io/portfolio/`.

## Edit

Edit the page’s copy, colors, selected-project links, and `descriptions` map in `index.html`. The hero shows a fanned stack of website captures that spreads on hover, followed by a scrolling marquee of brands from the 2026 portfolio (static when the visitor prefers reduced motion).

Selected work opens with five website studies, each with its own tinted panel: Ronins (featured, full width), Khalik Fahem, The Realest Estate, and FORM Athletic Club (a concept site with its own case study page), and Brennar (an outdoor storefront concept with a browser-local catalog dashboard). Trading Niche Webinar and Maison du Cèdre / MDC follow as “More website builds”. MDC links to its repository; its preview was rendered from the repository source because no live homepage was configured.

Graphic design samples sit in a justified mosaic: each row sizes its images by aspect ratio (`--r`), so nothing is letterboxed. Visible: Saudi Arabian Grand Prix, Yas Marina Circuit, Saudi Motorsports Company, Framez, Hamburgini, and MM Fitness Pro; four photography samples remain expandable. Gallery images open in a native dialog with keyboard dismissal and focus restoration. Newly added public repositories appear automatically in the archive, apart from the explicitly excluded original Khalik Fahem.

Seven animation clips are optimized H.264 MP4 files with poster images, shown as a tile grid with Punk Wurst featured. Clips do not preload. On devices with a mouse, hovering previews a clip muted; selecting a tile plays it with sound, and starting one pauses the others.

A lime “In numbers” band shows organic follower growth (@saudiarabiangp, @saudimotorsport, @houseofdiamond.shop) and a top reel’s views, taken from the statistics page of the 2026 portfolio PDF. The figures count up on scroll.

Keep `assets/` beside `index.html` when publishing. Images are optimized WebP exports of selected finished work. Source artwork, internal documents, and unrelated reference files are not included. GitHub and Google Fonts are external resources; local font fallbacks and the included repository collection remain usable if those services fail.

The biography, six career entries, brand experience, skills, education, language proficiency, email address, and phone number were supplied in Ramez Abou Azar’s 2026 portfolio and résumé. The documents are used as content sources; the visual design is independently developed. Career dates reflect the supplied résumé. The supplied résumé is available as a PDF download; the complete source portfolio PDF is not published.

Case study descriptions identify the focus, documented contribution, visible design direction, and deliverables. They do not claim independently measured business outcomes.

Page order: selected work and case studies, services, about, motion, graphic design, experience, repository archive, and contact. The sticky header links to each main section, highlights the one in view, and keeps a “Let’s talk” button within reach. Sections fade in on scroll unless the visitor prefers reduced motion.

The contact section provides working email and telephone links. GitHub is linked from the repository archive and the footer. Open Graph tags assume the GitHub Pages URL above; update them if the site moves to a custom domain.

Brennar is presented as a storefront concept with demo checkout, generated product imagery, custom categories, and a browser-local management studio. Its actual optimized website capture is included. The documented image-asset reduction is 25.3 MB to about 584 KB (97.7%); no live deployment or measured business outcome is claimed. Brennar is also included in the repository archive’s offline fallback.
