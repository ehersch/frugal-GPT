# FrugalGPT Blog Post Scaffold

This repo now contains a small static blog-post scaffold built from the project paper and poster.

## Files

- `index.html`: the post itself
- `styles.css`: page styling
- `CS_224N_Poster.pdf`: source poster, linked and embedded in the page
- `Frugal_GPT_2__Efficient_Adaptation_via_LoRA__Quantization__and_Synthetic_Data (1).pdf`: source paper

## Run locally

You can either open `index.html` directly in a browser or serve the folder locally.

### Option 1: open directly

Double-click `index.html` in Finder.

### Option 2: run a local static server

From the repo root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

- The page is intentionally simple and static, so there are no package installs or build steps.
- The content is scaffolded from the current paper and poster and is ready for tighter editing, additional figures, or author-specific voice.
