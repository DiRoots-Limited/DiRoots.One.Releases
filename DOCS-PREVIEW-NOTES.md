# Documentation notes for DiRoots.One.Releases

Found while testing documentation PR previews on a replica of this repository (`DiRoots-Mauro/DiRoots.Sandbox.DiRootsOne.Releases`) and on the production site. None of these items is caused by the preview workflows; they are listed so they can be fixed separately.

## Home page logo uses a root-relative Windows path

`index.md` line 11 references the logo as `/assets\images\DiRootsOne-Revit-Plugin-Logo.png`.
- The leading `/` points at the root of the domain. It works today only because the site is served at the root of `docs.dirootsone.diroots.com`. Previews load this logo from the live site, so a PR that changes it will not show the change, and the link breaks if the site is ever served under a path (it is already broken in the test replica and in the AutoCAD manual, which uses the same line).
- Suggested fix: `![DiRootsOne Logo]({{ '/assets/images/DiRootsOne-Revit-Plugin-Logo.png' | relative_url }})` (forward slashes, `relative_url` adds the site path when needed).

## Site size

The `gh-pages` branch holds about 392 MiB of files, almost all images and GIFs. GitHub Pages recommends repositories and published sites below 1 GB.
- Previews are not affected: they reuse the live images, so a preview of this site measured 6.2 MiB instead of 397 MiB.
- Suggested fix: compress the largest GIFs or convert them to MP4/WebM. Largest files: `assets/images/HideInViews/HV-Category-Hide.gif` (75.0 MiB), `assets/images/HideInViews/HV-Category-Unhide.gif` (56.7 MiB), `assets/images/SheetLink/SH-Mc-bx.gif` (5.1 MiB), `assets/images/SheetLink/SH-Sc-ImportProject.gif` (4.8 MiB), `assets/images/SheetLink/SH-El-ImportProject.gif` (3.9 MiB).
