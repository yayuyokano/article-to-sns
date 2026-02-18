---
layout: default
title: Privacy Policy - Article to SNS
---

# Privacy Policy - Article to SNS

**Last updated: February 18, 2026**

## Overview

Article to SNS is a Chrome extension that helps bloggers generate tweet drafts and OGP images from their articles using AI.

## Data Collection

### What we collect
- **Article content**: The text of the blog article on the currently active tab is temporarily extracted when you click the "Generate" button. This works on any website with article content.
- **API Key**: Your AI provider API key (Anthropic, OpenAI, or Google Gemini) is stored locally in Chrome's storage to authenticate with the selected AI service.

### What we do NOT collect
- We do **not** collect personal information (name, email, etc.)
- We do **not** track browsing history
- We do **not** use cookies or analytics
- We do **not** store any data on external servers

## Data Usage

- **Article content** is sent to your selected AI provider's API solely to generate tweet drafts. It is not stored or retained after generation.
- **Your API Key** is stored only in your browser's local storage (`chrome.storage.local`) and is never transmitted to any server other than the AI provider you selected.

## Third-Party Services

This extension supports the following AI providers. Your article content is sent to the selected provider's servers for processing:

- [Anthropic API](https://www.anthropic.com/privacy) (Claude)
- [OpenAI API](https://openai.com/policies/privacy-policy) (GPT)
- [Google Gemini API](https://ai.google.dev/terms) (Gemini)

Please refer to each provider's privacy policy for details on how they handle data.

## Data Retention

- No data is permanently stored on any server.
- Article content is processed in memory and discarded after tweet generation.
- Your API key remains in Chrome's local storage until you remove it or uninstall the extension.

## Data Security

- All communication with AI provider APIs is encrypted via HTTPS.
- Your API key is stored using Chrome's built-in secure storage mechanism.

## Your Rights

You can:
- Remove your API key at any time through the extension's settings
- Switch between AI providers at any time
- Uninstall the extension to delete all locally stored data
- Choose not to use the extension on any page

## Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected in the "Last updated" date above.

## Contact

If you have questions about this privacy policy, please create an issue on our [GitHub repository](https://github.com/yayuyokano/article-to-sns).
