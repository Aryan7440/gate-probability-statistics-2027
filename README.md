# Probability, understood

A concept-first, interactive Probability and Statistics study guide for **GATE CS**, aligned with the official **GATE 2027 CS syllabus** checked on 21 October 2026.

**[Open the study guide](https://aryan7440.github.io/gate-probability-statistics-2027/)**

## Open the guide

Open `index.html` in a browser. The file includes its lessons, original practice questions, Chapter 7 question images, styles, and scripts. It works offline; links to official sources and external discussions need internet.

The guide includes theory before worked examples and practice, separate closed hints and answers, interactive distributions and concept explorers, a mind map, and browser-local notes/progress. “Copy doubt context” prepares a reference to paste into the learning chat. No account or backend is used.

The scope page distinguishes directly named CS material from supporting foundations and extensions, including the requested CLT. This is a guide to the CS probability-and-statistics portion, not a complete course for GATE DA or GATE ST.

## GitHub Pages handoff

This repository is prepared to publish its root `index.html` from `main`. To publish a copy:

1. Put `index.html`, this README, and `.nojekyll` in the intended GitHub repository's publishing folder. No `assets` folder is required: the final HTML embeds all question images.
2. In that repository's **Settings → Pages**, select the publishing branch and folder, or use the repository's existing Pages workflow.
3. Open the resulting GitHub Pages URL when GitHub has finished publishing. See [GitHub's publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

The guide uses hash navigation and relative-free embedded assets, so a repository subpath is supported. There is no build command and no package installation.

## Sources and question provenance

- Official syllabus index: https://gate2027.iitm.ac.in/exam_papers_and_syllabus
- Official CS PDF: https://gate2027.iitm.ac.in/static/doc/GATE2027_Syllabus/CS_GATE2027_Syllabus.pdf
- User-provided `filter1_volume1.pdf`, **Chapter 7 only**, pages 189–227. All 125 chapter question prompts are preserved as images to retain mathematical notation and figures. CS, IT, DA and source question identifiers remain visible, with links to their GateOverflow discussions. Source answer keys are hidden separately from guide-authored hints.

Original teaching examples/practice include worked reasoning. Bank answer keys are labelled as source keys; they are not presented as independently verified solutions. Missing/invalid bank-key entries receive clearly labelled explanations where verified. Some source questions are defective; warnings are placed inside the relevant answer panel so they do not spoil attempts.

Source questions are adapted from the user-supplied **GATEOverflow for GATE CSE** compilation. Credit to the GATE examination organizers and the GateOverflow community; individual discussion links are preserved. The guide's source notes retain attribution. Before publicly publishing the source-bank images, check the original collection's applicable reuse terms. This README does not grant rights in third-party questions.

## Notes and privacy

Notes, lesson checkmarks, attempted-question checkmarks and theme preferences use browser local storage. They are not sent to GitHub or to the chat. Local-file storage behavior may vary by browser, and notes made in a local file will not automatically migrate to the later Pages origin. Copy notes you want to retain before switching origins or clearing browser data.

## Editing

The delivered `index.html` is self-contained. Authoring sources and QA files are in `.work/`; these are excluded from the proposed publish list. `assets/bank/` contains intermediate question crops already embedded into the HTML. To rebuild from the authoring sources, run `node .work/assemble.mjs` from this folder. Node is needed only for rebuilding, not for reading or hosting.
