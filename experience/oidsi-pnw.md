---
title: OIDSI-PNW (Vue + Vite)
layout: default
permalink: /experience/oidsi-pnw/
---

# OIDSI-PNW Website

**Role:** Full-stack Web Developer  
**Dates:** October 2022 – Present
**Stack:** Vue 3, Vite, Bootstrap 5, TypeScript, Playwright (e2e), GitHub Actions, AWS S3 + CloudFront

## Overview

The OIDSI-PNW site is a single-page application built with Vue and Vite. It was migrated from Firebase Hosting to **AWS S3 + CloudFront**, ensuring global caching and stable SPA routing. The project emphasizes accessibility, performance, and automated testing.

## Highlights

- Migrated deployment pipeline to **AWS S3 + CloudFront**, configured SPA routing fallback for deep links.
- Added **end-to-end testing with Playwright**; current suite passing on main.
- Customized Bootstrap theme using Sass `@use`, modernizing styles and removing deprecated imports.
- Fixed mobile navbar accessibility issues and improved ARIA usage for dropdowns.

## Technical Details

- **Frontend:** Vue 3 Composition API, Vue Router, Bootstrap 5 with custom Sass tokens.
- **Testing:** Playwright end-to-end test suite; CI runs on pull requests and main branch.
- **CI/CD:** GitHub Actions builds and deploys to AWS S3, with CloudFront invalidation for cache consistency.
- **Accessibility:** Keyboard navigation, focus ring adjustments, color contrast fixes, and mobile dropdown toggle improvements.

## Challenges & Solutions

- **Problem:** Direct navigation to routes (e.g. `/about`, `/gallery`) failed with 403/404 errors on static hosting.  
  **Solution:** Implemented SPA fallback (`index.html` copied to `404.html`) and CloudFront behavior rules.

## Screenshots
<figure>
  <img src="/images/oidsi-home.png" alt="OIDSI-PNW site home page" class="project-screenshot">
  <figcaption>OIDSI-PNW organization's home page</figcaption>
</figure>

<figure>
  <img src="/images/oidsi-contact.png" alt="OIDSI-PNW site contact form" class="project-screenshot">
  <figcaption>Contact OIDSI-PNW with this form</figcaption>
</figure>

<figure>
  <img src="/images/oidsi-tests-passing.png" alt="OIDSI-PNW site Playwright tests passing" class="project-screenshot">
  <figcaption>OIDSI-PNW end-to-end tests passing</figcaption>
</figure>

<figure>
  <img src="/images/oidsi-test-details.png" alt="OIDSI-PNW site contact form test details passing" class="project-screenshot">
  <figcaption>OIDSI-PNW site contact form test passing details</figcaption>
</figure>

## Links

- **Live:** [https://www.oidsi-pnw.com](https://www.oidsi-pnw.com)
- **Repo:** [https://github.com/quinise/oidis-pnw](https://github.com/quinise/oidis-pnw)
