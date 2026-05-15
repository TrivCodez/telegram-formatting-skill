---
name: telegram-formatting
description: Use this skill whenever sending, composing, or formatting any message destined for Telegram. Triggers on any task that involves writing to a Telegram group, channel, or bot — including news digests, announcements, summaries, or any other message type. Ensures all output uses Unicode styled text instead of Markdown, since Telegram does not render Markdown and asterisks/underscores will appear as raw symbols.
---

# Telegram Formatting Skill

Telegram does not render Markdown. Any use of `**`, `*`, `_`, `#`, or similar symbols will appear as raw characters in the chat and break the message visually. This skill ensures all Telegram messages are formatted correctly.

## Default Telegram Group

Unless the user specifies otherwise, send to one of the following:

- 𝗖𝗵𝗮𝗻𝗻𝗲𝗹 𝗜𝗗: -1003905712918
- 𝗚𝗿𝗼𝘂𝗽 𝗜𝗗: -5138545691

If not specified, default to the channel (-1003905712918).

---

## Hard Rules

1. **NEVER** use Markdown syntax in Telegram messages: no `**bold**`, no `*italic*`, no `_underscore_`, no `# headers`, no `` `code` ``, no `~strikethrough~`
2. **ALWAYS** use Unicode styled text for visual emphasis (see table below)
3. **ALWAYS** use `•` for bullet points — never `-` or `*`
4. Keep blank lines between sections for clean spacing
5. Before sending, mentally scan the full message for any `*`, `_`, `#` characters — if found, replace them

---

## Unicode Font Reference

| Style | Example | Use for |
|-------|---------|---------|
| 𝗦𝗮𝗻𝘀-𝗦𝗲𝗿𝗶𝗳 𝗕𝗼𝗹𝗱 | 𝗛𝗲𝗹𝗹𝗼 | Headings, emphasis |
| 𝘚𝘢𝘯𝘴-𝘚𝘦𝘳𝘪𝘧 𝘐𝘵𝘢𝘭𝘪𝘤 | 𝘏𝘦𝘭𝘭𝘰 | Subtext, captions |
| 𝙼𝚘𝚗𝚘𝚜𝚙𝚊𝚌𝚎 | 𝙷𝚎𝚕𝚕𝚘 | Code, IDs, handles |

### Bold Alphabet (copy-paste ready)

Uppercase:
𝗔 𝗕 𝗖 𝗗 𝗘 𝗙 𝗚 𝗛 𝗜 𝗝 𝗞 𝗟 𝗠 𝗡 𝗢 𝗣 𝗤 𝗥 𝗦 𝗧 𝗨 𝗩 𝗪 𝗫 𝗬 𝗭

Lowercase:
𝗮 𝗯 𝗰 𝗱 𝗲 𝗳 𝗴 𝗵 𝗶 𝗷 𝗸 𝗹 𝗺 𝗻 𝗼 𝗽 𝗾 𝗿 𝘀 𝘁 𝘂 𝘃 𝘄 𝘅 𝘆 𝘇

---

## Message Structure Template

```
[Emoji] 𝗧𝗶𝘁𝗹𝗲 𝗛𝗲𝗿𝗲

Opening line or context.

𝗦𝗲𝗰𝘁𝗶𝗼𝗻 𝗛𝗲𝗮𝗱𝗲𝗿
• Point one
• Point two
• Point three

𝗔𝗻𝗼𝘁𝗵𝗲𝗿 𝗦𝗲𝗰𝘁𝗶𝗼𝗻
• More points here

— Footer or source attribution
```

---

## Examples

✅ Correct:
```
𝗕𝗿𝗲𝗮𝗸𝗶𝗻𝗴 𝗡𝗲𝘄𝘀 🇦🇺

Today's top stories from Australia:

𝗣𝗼𝗹𝗶𝘁𝗶𝗰𝘀
• One Nation polling higher than Labor
• Backlash against Angus Taylor's budget reply

𝗦𝗽𝗼𝗿𝘁
• Sam Kerr leaving Chelsea FC
```

❌ Wrong:
```
**Breaking News** 🇦🇺

Today's top stories:

**Politics**
- One Nation polling higher than Labor
- Backlash against budget reply
```
