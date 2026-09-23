# DAVIS project homepage

This static project page adapts the [GALATEA `gh-pages` template](https://github.com/boyuan-an/GALATEA/tree/gh-pages) for DAVIS: *A Depth-Only End-to-End Active-Vision Framework for Humanoid Soccer Skills*.

## Local preview

```powershell
python .\serve.py --host 127.0.0.1 --port 8000
```

Open <http://127.0.0.1:8000/index.html>.

The page uses the active figures and content from `ICRA/1_原文转格式/DAVIS_ICRA2027_Self`. The named page publishes the current manuscript as `resources/DAVIS.pdf`. Large raw demonstration archives remain in the source workspace and are intentionally not copied into this static site.

## Named release: 2026-09-23

- Source: `ICRA/1_原文转格式/DAVIS_ICRA2027_Self/root.tex` and its active inputs.
- Paper: the source `root.pdf`, built on 2026-09-23 at 17:15 (Asia/Shanghai), copied without re-encoding; 16 pages including the full appendix.
- Paper SHA-256: `e64137e72e6151844be86f7694efe6c30c1c3380dbd5b7c7fe7ca9476fd6c9b3`.
- The named page body is organized into Abstract, Overview, Method, Tasks, Results, and Deployment chapters with a responsive section navigator; the technical supplement remains organized as Appendix A–F.
- The supplement follows the separate Table VI (reaching/obstacle) and Table VII (turning) captions and distinguishes the reference protocols.
- The main method summary uses the dimension-neutral term “HIM history feature” because the active appendix and the main framework caption currently disagree on its dimensionality; the 32-D depth latent is stated separately.
- The public citation includes all named authors and identifies the document as a manuscript; update publication metadata when a confirmed venue or archive record is available.
