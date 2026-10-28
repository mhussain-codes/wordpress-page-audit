# WordPress Page Audit

A free, privacy-first helper for checking the HTML behind a WordPress page. Preview the page title and description, spot common SEO and accessibility issues, and get practical next steps—all in your browser.

## What it checks

- Page title and meta description, with human-review reminders
- An illustrative search-result preview
- A page-level noindex directive and canonical URL
- Open Graph and Twitter/X card metadata
- Missing or repeated H1 headings and skipped heading levels
- Images without an alt attribute
- Links without a text or image name, and new-tab links missing rel="noopener"
- Declared page language and mobile viewport metadata
- Presence of JSON-LD structured data (without validating it)
- A rough visible-text word count

The report includes a simple heuristic score, severity labels, suggested next steps, and a downloadable JSON summary.

## Run it

1. Open [index.html](./index.html) in a modern browser.
2. In WordPress, open the page source and copy its HTML.
3. Paste the HTML into the tool and select **Check my page**. Or select **Try sample** to explore the report.
4. Review the suggested fixes in your WordPress theme or SEO plugin.
5. Select **Download JSON report** if you want to save the results.

## Privacy

The pasted HTML is parsed locally in the browser. The tool does not fetch a URL, upload page source, use an account, or send analytics.

## Scope and limitations

This is a quick check of the HTML you provide. It does not crawl a website, inspect HTTP headers or robots.txt, test live links, measure rankings, or replace a full SEO, accessibility, or security audit. The score and title-length reminders are heuristics, not ranking signals or pass/fail rules. Google may generate a different title or snippet depending on the search.

For details, see Google's guidance on [title links](https://developers.google.com/search/docs/appearance/title-link) and [search snippets](https://developers.google.com/search/docs/appearance/snippet).

## Built with

HTML, CSS, and vanilla JavaScript. No dependencies, build step, or backend required.
