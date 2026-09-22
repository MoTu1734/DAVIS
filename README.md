# DAVIS project homepage

This static project page adapts the [GALATEA `gh-pages` template](https://github.com/boyuan-an/GALATEA/tree/gh-pages) for DAVIS: *A Depth-Only End-to-End Active-Vision Framework for Humanoid Soccer Skills*.

## Local preview

```powershell
python .\serve.py --host 127.0.0.1 --port 8000
```

Open <http://127.0.0.1:8000/index.html>.

The page uses the active figures and content from `ICRA/1_原文转格式/DAVIS_ICRA2027_Self`. The named page publishes the current manuscript as `resources/DAVIS.pdf`. Large raw demonstration archives remain in the source workspace and are intentionally not copied into this static site.

## Named release: 2026-09-22

- Source: `ICRA/1_原文转格式/DAVIS_ICRA2027_Self/root.tex` and its active inputs.
- Paper: the source `root.pdf`, built on 2026-09-22 at 17:55 (Asia/Shanghai), copied without re-encoding; 16 pages including the full appendix.
- Paper SHA-256: `907315210fcb20fbb37e8ace12592b8309cc7075138ee1a71512c6a0aa7a23ee`.
- The supplement follows the separate Table VI (reaching/obstacle) and Table VII (turning) captions and distinguishes the reference protocols.
- The main method summary uses “HIM history feature”; the appendix retains its explicit 3-D estimate. The source framework caption calls the history feature 64-D, so these descriptions must not be treated as interchangeable dimensions.
- The public citation includes all named authors and identifies the document as a manuscript; update publication metadata when a confirmed venue or archive record is available.
