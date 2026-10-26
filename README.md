# RSIx — The Assurance Lab

An interactive companion to Blake A. Myers’s *No Assurance for Free: Evaluation, Trust, and the Limits of Self-Improving AI*.

Eight browser-based experiments explore accurate checkers, changing evaluations, delegation drift, checking versus trusting, correlated monitors, proxy selection and evaluation awareness, changing alignment targets, and bounded assurance cases.

## Run locally

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. No build, dependencies, accounts, or API keys are required.

## Source and interpretation

Based on the supplied manuscript `no-assurance-for-free(7).docx`. The full manuscript is not distributed. Each experiment identifies the relevant chapters and explains its assumptions. Numerical models are explicitly illustrative, not empirical estimates or general impossibility proofs. The worksheet follows Table 14.1; its example adapts Table 14.2.

## Privacy and accessibility

No analytics, third-party scripts, remote fonts, or backend. Optional worksheet storage remains in the visitor’s browser; Markdown export is local. Keyboard-operable native inputs, visible focus indicators, reduced-motion support, responsive layouts, and explanatory text accompany visualizations.

## Publishing

GitHub Pages serves `main` from `/` at https://prototypeversions.github.io/RSIx/.

## Editing

- `index.html`: narrative, site structure, source notes
- `style.css`: responsive visual design
- `app.js`: experiment logic and worksheet

Please preserve the distinction between a model’s stipulated assumptions, what its calculation demonstrates, and broader philosophical claims.
