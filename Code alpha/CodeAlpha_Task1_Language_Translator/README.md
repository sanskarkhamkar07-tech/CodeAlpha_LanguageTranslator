# Lingua AI — CodeAlpha Task 1

A responsive language translation tool created for the CodeAlpha Artificial Intelligence Internship, Task 1.

## Features
- Source and target language selectors (including auto-detect)
- Translation using the free MyMemory API
- Swap languages, clear/reset, character count
- Copy translated output
- Browser text-to-speech
- Responsive layout for desktop and mobile

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Enter text, choose languages, and click **Translate text**.
4. Internet access is required for translation.

You can also deploy the folder as a static site on Netlify (drag-and-drop the folder/site files in Netlify's deploy UI).

## API note
This project calls `https://api.mymemory.translated.net/get` from the browser. The free public API can have limits, availability changes, and browser/network restrictions. It is not intended for confidential text.

## GitHub submission
Create a repository named `CodeAlpha_LanguageTranslator`, upload `index.html` and `README.md`, then share the repository URL in your internship submission.
