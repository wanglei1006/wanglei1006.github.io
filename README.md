# Lei Wang — Academic Homepage

A responsive, buildless academic homepage for https://wanglei1006.github.io/.

## Publish on GitHub Pages

1. Create a public repository named `wanglei1006.github.io` under `wanglei1006`.
2. Upload `index.html`, `publications.json`, and `.nojekyll` to the repository root.
3. Open **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
5. Wait for GitHub Pages deployment; visit https://wanglei1006.github.io/.

## Content and maintenance

The homepage includes all 38 supplied papers: 27 journal articles and 11 conference papers. Publication metadata and author-role labels come from the supplied Word list. Current impact factors and quartiles are not asserted. No academic title, affiliation, CV, portrait, code repository, or paper PDF is invented. DOI links are included where supplied; remaining titles link to a Google Scholar title search. The 2026 publication records are retained as supplied and have not been independently verified.

`index.html` renders every paper without JavaScript. JavaScript adds search and year/type filtering. Update both the embedded HTML publication list and `publications.json` when editing publications. Run `extract.py` and `build.py` locally with the source Word file available to regenerate both. The Word source, extraction scripts, and raw extraction are local maintenance files and do not need to be published.
