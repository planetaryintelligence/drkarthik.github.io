# Website update — September 2026

## Current version

- Home contains the supplied biography and three linked appearance previews: the energy-transition YouTube talk, AI + Environment Summit 2025, and CERAWeek Responsible AI.
- Named researchers Yoshua Bengio, Gregory Dudek and David Meger link to their academic profiles. Relevant institutions and research references are linked within the bio.
- The supplied biography is retained, including its approximate turnover, investment and citation figures; these are the author's supplied figures rather than a live data feed.
- Research figures are on the research pages. karthikLab features KDD Figure 1 (Flow framework), IJCAI Figure 3 (HiGFlow architecture) and WSDM Figure 2 (HoGA architecture).
- The IJCAI crop is a different figure with no watermark crossing it. The previously rejected watermarked figure is absent. Source credit remains explicit.
- There are 53 deduplicated Scholar entries, plus the earlier preprint retained on the lab page, and 14 credited paper figures.

## Preview and upload

Extract the ZIP and open `preview/index.html`. The local preview has a compact stylesheet; GitHub Pages retains the Just the Docs theme. Speaker portraits and video thumbnails are external images and need an internet connection. Their sources and links are in `_data/media.json`. The CERAWeek card uses the speaker's portrait, not an event photograph.

Upload the contents of the enclosed `drkarthik.github.io-main` folder to the repository root on a review branch. Include `_data`, `_includes` and `assets`. Do not upload the ZIP itself. Keep the live Pages publishing branch unchanged until ready to merge.

The `preview` folder is excluded from the Jekyll build. The original CNAME is preserved. No live GitHub changes or deployment have been made.

## Validation

All eight generated preview pages passed local link, asset and image-alt checks. The KDD, IJCAI and WSDM figure crops were visually inspected. The exact Jekyll build and browser rendering could not be run because Ruby/Jekyll and a browser executable are unavailable. External media downloads are restricted in this environment, so the final portrait and thumbnail rendering could not be visually verified here; they remain direct, linked images from the event site and YouTube.

Optional exact-theme local build, with Ruby installed: `bundle install`, then `bundle exec jekyll serve`.
