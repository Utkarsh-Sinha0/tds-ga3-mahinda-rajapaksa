# Mahinda Rajapaksa — 3D portrait

[Interactive public site](https://utkarsh-sinha0.github.io/tds-ga3-mahinda-rajapaksa/)

[Direct GLB file](https://utkarsh-sinha0.github.io/tds-ga3-mahinda-rajapaksa/mahinda_rajapaksa.glb)

This repository hosts the approved, sharpened portrait model for TDS 2026 September GA3 Question 6. GitHub Pages serves the static site and model without a temporary local tunnel. The site and direct file should be retained for offline evaluation.

## Model

- glTF 2.0 binary, self-contained.
- **1,960,712 bytes**, below 2,000,000 bytes.
- 58,926 triangles; original geometry preserved.
- Smooth normals and a 2048 × 1024 lossless PNG texture.
- SHA-256: `ca8fd2f604acd4fbd8982ae248eb09e05b5af775ec6f9678fc9f11b1b37753cd`.
- Khronos glTF validation: 0 errors, 0 warnings. See [validation.json](validation.json).

## Provenance

Source model: [Headsketch.xyz](https://www.headsketch.xyz/uploads/2022/mahindarajapaksha.glb), supplied by the student. The original GLB did not embed a license statement; no new license for the source artwork is claimed.

Adaptations: duplicate vertices merged, smooth normals rebuilt, matte material refined, and original texture sharpened. A controlled amount of AI-assisted fine detail was baked with the original colours and a fade across UV seams. Generated detail is inferred rather than measured. Geometry and UV buffers are unchanged from the smoothed base model.

Reference person: [Mahinda Rajapaksa, Wikidata Q57338](https://www.wikidata.org/wiki/Q57338). The assignment's photograph is [Mahinda Rajapaksa 1.jpg](https://commons.wikimedia.org/wiki/File:Mahinda_Rajapaksa_1.jpg), by Khamenei.ir, CC BY 4.0.

## Viewer

The pinned Google model-viewer 4.4.0 bundle is hosted in this repository, with its upstream license. It is not fetched from a CDN when viewing the site. Model download and inspection do not require sign-in.

The automatic exam check concerns reachability, CORS, GLB validity and size. Offline likeness grading is separate.
