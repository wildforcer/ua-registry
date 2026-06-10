# GPTBot

OpenAI's background web crawler for collecting training data for AI foundation models.

## Description

`GPTBot` is OpenAI's automated web crawler that crawls publicly accessible web pages to collect content used in training
and improving AI models such as ChatGPT. Unlike
`ChatGPT-User`, which is triggered by real-time user requests, GPTBot operates as a background crawler with no direct
user interaction.

Content collected by GPTBot may be used to train generative AI foundation models. Operators can allow or block it
independently via `robots.txt` using the `GPTBot` token without affecting `ChatGPT-User` or `OAI-SearchBot` access.

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

| User-Agent String                                                                                        | Version |
|----------------------------------------------------------------------------------------------------------|---------|
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko; compatible; GPTBot/1.0; +https://openai.com/gptbot)` | 1.0     |
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko); compatible; GPTBot/1.1; +https://openai.com/gptbot` | 1.1     |
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko; compatible; GPTBot/1.2; +https://openai.com/gptbot)` | 1.2     |


