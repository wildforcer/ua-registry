# OAI-SearchBot

OpenAI's dedicated search indexing crawler for powering ChatGPT Search citations.

## Description

`OAI-SearchBot` is OpenAI's web crawler designed exclusively for search indexing — not AI model training. It crawls
publicly accessible pages to build the index that powers real-time search results and citations within ChatGPT Search
(formerly SearchGPT).

It is distinct from `GPTBot` (training data) and `ChatGPT-User` (user-triggered retrieval). All three can be controlled
independently via `robots.txt`. Allowing
`OAI-SearchBot` while blocking `GPTBot` lets your content appear in ChatGPT Search results without contributing to AI
training data.

## Vendor

Company
: OpenAI OpCo, LLC

Website
: [https://openai.com](https://openai.com)

Documentation
: [https://platform.openai.com/docs/bots](https://platform.openai.com/docs/bots)

Status
: ✅ Active

Verified
: ✅ rDNS

## User-Agent Examples

| User-Agent String                                                                                                                                                                                 | Version |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko); compatible; OAI-SearchBot/1.0; +https://openai.com/searchbot`                                                                                | 1.0     |
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko; compatible; OAI-SearchBot/1.0; +https://openai.com/searchbot)`                                                                                | 1.0     |
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0; compatible; OAI-SearchBot/1.0; +https://openai.com/searchbot`                                                               | 1.0     |
| `Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36; compatible; OAI-SearchBot/1.0; +https://openai.com/searchbot`             | 1.0     |
| `Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36; compatible; OAI-SearchBot/1.0; robots.txt; +https://openai.com/searchbot` | 1.0     |
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko); compatible; OAI-SearchBot/1.3; +https://openai.com/searchbot`                                                                                | 1.3     |
| `Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36; compatible; OAI-SearchBot/1.3; +https://openai.com/searchbot`             | 1.3     |
| `Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36; compatible; OAI-SearchBot/1.3; robots.txt; +https://openai.com/searchbot` | 1.3     |
