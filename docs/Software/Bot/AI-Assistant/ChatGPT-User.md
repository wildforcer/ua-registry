# ChatGPT-User

OpenAI's conversational AI browser bot, sent when ChatGPT browses the web on behalf of a user.

## Description

`ChatGPT-User` is a user-agent sent by OpenAI's ChatGPT when it performs web browsing on behalf of a user during a
conversation. It is distinct from OpenAI's indexing crawler (`GPTBot`) — this bot is triggered by real-time user
requests, not background crawling.

Operators can allow or block this bot via `robots.txt` using the `ChatGPT-User` token, or by restricting access to
OpenAI's published IP ranges.

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

| User-Agent String                                                                                           | Version |
|-------------------------------------------------------------------------------------------------------------|---------|
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko; compatible; ChatGPT-User/1.0; +https://openai.com/bot)` | 1.0     |
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko); compatible; ChatGPT-User/1.0; +https://openai.com/bot` | 1.0     |
| `Mozilla/5.0 (compatible; ChatGPT-User/1.0; +https://openai.com/chatgpt)`                                   | 1.0     | 

