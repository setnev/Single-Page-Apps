# 📄 Resume Analyzer

> Paste your resume, optionally add a job description, and get AI-powered feedback — all in your browser.

## What It Does

Resume Analyzer sends your resume text (and an optional target job description) to the AI provider you configure, then shows a structured review: an overall score and impression, strengths, weaknesses, missing keywords and skills versus the job description, ATS-friendliness notes, and concrete bullet-point rewrite suggestions. You can load a `.txt` or `.md` file or just paste text, and copy the full result with one click.

## How To Use

1. Open Settings and add your AI provider API key (Claude by default, or any OpenAI-compatible endpoint).
2. Paste your resume into the resume box (or load a `.txt` / `.md` file).
3. Optionally paste the job description you're targeting for tailored keyword and fit feedback.
4. Click **Analyze** and read the structured review; use **Copy result** to grab the text.

## Notes

- Runs entirely in the browser — no server of ours, no install, no account.
- Everything lives in a single self-contained index.html.
- Bring your own AI key: it is stored only in your browser, and your text is sent only to the provider you configure. A browser-stored key is visible to anyone with access to this device.

## Tags

`ai` `resume` `career` `pluggable-llm` `offline`
