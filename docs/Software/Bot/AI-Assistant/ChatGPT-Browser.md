# ChatGPT-Browser

OpenAI's deprecated web browsing bot, superseded by [ChatGPT-User](ChatGPT-User.md).

## Description

`ChatGPT-Browser` was an early user-agent used by ChatGPT's web browsing plugin to fetch real-time web content on behalf
of users during conversations.

It has been deprecated and replaced by `ChatGPT-User`, which serves the same purpose with updated identification.
Operators should use the `ChatGPT-User` token in `robots.txt` for access control — `ChatGPT-Browser` rules are no longer
effective.

Company
: OpenAI OpCo, LLC

Website
: [https://openai.com](https://openai.com)

Documentation
: [https://platform.openai.com/docs/bots](https://platform.openai.com/docs/bots)

Status
: ⛔ Deprecated — replaced by `[ChatGPT-User](ChatGPT-User.md)

Verified
: ✅ rDNS

## User-Agent Examples

| User-Agent String                                                                     | Version |
|---------------------------------------------------------------------------------------|---------|
| `Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko); compatible; ChatGPT-Browser/1.0` | 1.0     |
