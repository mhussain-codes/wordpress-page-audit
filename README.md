# WordPress Page Audit

A lightweight browser tool that checks pasted, rendered HTML for useful on-page SEO and accessibility basics. The analysis runs locally in your browser; page source is not uploaded anywhere.

## What it checks

- Page title and meta description presence, with a rough length reminder
- H1 count and empty main headings
- Images that are missing an alt attribute
- Links without visible text or an image accessible name
- Declared document language and mobile viewport metadata

## Run it

Open [index.html](./index.html) in a modern browser, paste the rendered HTML from a page, then choose **Run audit**. Use **Load sample** to explore the results format. Download a JSON copy of the report when you are done.

## Scope and limitations

This tool parses HTML you provide. It does not fetch or crawl a live WordPress site, inspect server response headers, or replace a full SEO, accessibility, or security audit. Its title and description length reminders are heuristics, not pass/fail rules.

## Built with

HTML, CSS, and vanilla JavaScript. No dependencies, account, or build step required.
