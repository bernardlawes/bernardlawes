<!--
==============================================================================
TEMPLATE: README for each pinned repository
Copy this file into the repo as README.md, fill in every [BRACKET], and delete
any section that doesn't apply. Delete this comment block when done.

Suggested repos, one per domain:
  1. Detection / segmentation with ONNX or TensorRT export
  2. Classical CV or calibration tool
  3. Geospatial or raster processing pipeline
  4. Desktop or mobile app
  5. Agentic AI: imagery triage and report generation

Rules that keep these credible:
  - Lead with one image or GIF that shows the result, not the code.
  - Every number states its conditions (dataset, n, hardware, resolution).
  - If data or weights can't be shared, say so and offer a synthetic sample.
  - Store images in docs/ inside the repo, WebP or PNG, under ~1 MB each.
  - Credit imagery: Maxar (DigitalGlobe) or "Contains modified Copernicus
    Sentinel-2 data (YEAR)" as appropriate.
==============================================================================
-->

# [Project Name]

[One sentence: what it does, for whom, on what kind of data.]

<img src="docs/hero.webp" width="100%" alt="[Describe what the image shows: input on the left, output on the right]">

<sub>[Caption: what the viewer is looking at. Imagery credit.]</sub>

## Why it exists

[Two or three sentences. The problem, and what makes it hard: the sensing,
scale, or deployment constraint, not just "objects are small".]

## Results

| Metric | Value | Conditions |
|---|---|---|
| [e.g. mAP@0.5 / precision / count accuracy] | [0.00] | [dataset, n, resolution] |
| [e.g. Inference time] | [00 ms/frame] | [hardware, precision FP16/INT8, input size] |
| [e.g. Reprojection error / RMSE] | [0.00 px] | [setup] |

<!-- Optional second visual: a GIF of the app or pipeline running.
<img src="docs/demo.gif" width="100%" alt="[What happens in the demo]">
-->

## How it works

<!-- Optional: architecture or pipeline diagram (docs/architecture.svg). -->

1. **[Input / sensing]**: [what data comes in and how it's prepared]
2. **[Processing]**: [calibration, tiling, feature extraction, model]
3. **[Output]**: [what is produced and where it goes]

## Stack

[Languages, frameworks, and key libraries on one or two lines.]

## Run it

```bash
# [Install]
[command]

# [Run on the sample data]
[command]
```

[Hardware or OS requirements, e.g. "CUDA 12, tested on RTX 4070 and Jetson Orin".]

## Data

[Where the sample data comes from and its license. If the real data is client
or licensed imagery, say so and describe the synthetic or public substitute.]

## Limitations

- [Where it fails or hasn't been tested. One honest line here adds credibility.]

## Contact

Bernard Lawes · [bernardlawes.com](https://bernardlawes.com) · hello@bernardlawes.com
