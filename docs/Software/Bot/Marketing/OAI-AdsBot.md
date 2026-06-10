# OAI-AdsBot

OpenAI's ad landing page validation crawler for ChatGPT's advertising platform.

## Description

`OAI-AdsBot` is OpenAI's dedicated crawler for validating ad landing pages submitted through ChatGPT's advertising
platform. Unlike OpenAI's other crawlers, it operates on-demand — only visiting pages explicitly submitted as ad landing
pages, not crawling the broader web.

It serves two purposes: verifying that landing pages comply with OpenAI's ad policies, and extracting page content to
determine ad relevance for serving within ChatGPT. Collected data is not used to train generative AI foundation models.

Blocking `OAI-AdsBot` via `robots.txt` will prevent ad landing page validation, meaning ads pointing to that page will
likely not serve in ChatGPT.

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

| User-Agent String                                                                                            | Version |
|--------------------------------------------------------------------------------------------------------------|---------|
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko); compatible; OAI-AdsBot/1.0; +https://openai.com/adsbot` | 1.0     |