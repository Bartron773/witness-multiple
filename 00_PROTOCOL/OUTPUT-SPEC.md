# WITNESS / MULTIPLE
## Independent Witness Output Specification

Return one complete, self-contained HTML5 document as **raw source code**.

The required deliverable is the actual HTML source beginning with `<!DOCTYPE html>` and ending with `</html>`.

Do **not** return only:

- a hosted artifact or sandbox preview;
- a downloadable webpage wrapper;
- an exported platform page containing the surrounding Meta, Gemini, Claude, Grok, or ChatGPT application shell;
- React/Next.js application output;
- a share link to an artifact;
- screenshots or flattened images of the artifact;
- plain prose without the HTML source.

If the platform also creates a visual artifact or preview, that is fine, but the witness must additionally provide the **raw standalone HTML source code itself** so it can be saved directly as a `.html` file in the repository.

### Required technical format

- HTML5
- Begin with `<!DOCTYPE html>`.
- Include the complete `<html>`, `<head>`, and `<body>` structure.
- Include all CSS inside the same HTML document, preferably in `<style>`.
- Include JavaScript only if genuinely useful to the artifact, and keep it inside the same HTML document.
- Do not require React, Next.js, npm, a build process, or external application frameworks.
- Do not rely on platform-specific asset paths such as `/_next/`, internal sandbox URLs, authenticated application resources, or temporary preview URLs.
- The file must open directly in a modern browser when saved locally or served from GitHub Pages.
- The artifact must remain understandable if printed or converted to PDF.
- Important text must remain actual selectable text, not flattened into images.
- Avoid external dependencies when practical.
- If external fonts are used, provide sensible fallback fonts.
- No analytics, tracking, cookies, or network requests are required.

### Required content

Clearly include:

1. WITNESS / MULTIPLE
2. Commission number and title/question
3. Model/witness name
4. "Independent Witness Account"
5. The full argument or investigation
6. The final unresolved question required by the commission prompt

### Visual authorship

The visual interpretation belongs to the witness.

The artifact may be:
- editorial
- spatial
- archival
- typographic
- diagrammatic
- restrained
- experimental

Do not imitate another witness's artifact.

Do not attempt to make the five outputs visually uniform.

### Epistemic rule

Do not claim to remember material merely because it was read in the repository.

When useful, distinguish:

- source material read;
- interpretation;
- inference;
- direct experience within the current interaction.

### Return format

Return the **raw HTML source code** as the deliverable.

When the interface permits, place the entire source in one code block so it can be copied or saved without surrounding commentary.

If the platform can create files directly, create a plain UTF-8 `.html` file containing only that standalone source and provide that file.

Suggested filename:

`WITNESS_MULTIPLE_Commission_06_[WitnessName]_Independent.html`
