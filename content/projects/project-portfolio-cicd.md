---
title: "Portfolio Website Pipeline"
date: 2026-05-19
draft: false
tags: ["Hugo", "Web", "CI/CD"]
layout: "cicd"
description: "A GitHub Actions pipeline for this portfolio site, enforcing linting, spell-check, and deployment validation on every change."
---

A portfolio site should be held to the same standards as any production application. This project automates quality gates for the site so content is validated before it reaches GitHub Pages.

- Automated Markdown linting, spell checking, and HTML/link validation
- Protected branches for authoring and deployment
- Zero-touch deployment from the release branch

This pipeline keeps the site polished, reliable, and ready for every commit.
