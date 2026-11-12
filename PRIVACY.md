# Loki Privacy Policy

Last updated: 12 November 2026

Loki is a chat and moderation bot for Discord. This policy explains what the bot stores and why.
Contact: open an issue at <https://github.com/qooode/loki-legal/issues>

## What Loki stores

| Data | Why | Kept for |
|---|---|---|
| Messages in channels Loki can see: text, your Discord user ID and display name, channel and server ID, time | Context for replies and moderation; learning what the server talks about | 30 days, then deleted automatically |
| Short notes about members (interests, how they like to talk) written by the bot from chat | So replies fit the people in the conversation | Until you delete them (see below) |
| Server topics: themes the server talks about | To start and follow conversations | Fades out as topics go quiet |
| Moderation strikes: user ID, the flagged message, the reason, time | So repeat rule-breaking can be handled fairly | Until a server admin clears them |
| Server settings and moderation rules set by admins | To run the bot the way the server wants | Until changed |

Loki does not read direct messages, does not store attachments or voice, and does not collect
email addresses, IP addresses or payment data. The bot is instructed and filtered not to keep
notes about health, sexuality, religion, politics, finances, real names or addresses.

## Who receives data

To write replies, judge messages against the server rules and build notes, message text is sent
to an AI model through OpenRouter (openrouter.ai) and the model provider it routes to. They
process it under their own privacy terms. Every request is sent with OpenRouter's zero data
retention requirement, so it is only routed to providers that do not store prompts or replies. When a question needs current information, the bot
sends a short search query about the public subject (never member names or what members said
about themselves) to a web search model through OpenRouter. Data is not sold and is not used for advertising.

Moderation reports are posted to a private channel that the server's moderators choose.

## Your choices

- Run `/loki` and press **What you know about me** to see your notes.
- Run `/loki` and press **Forget me** to delete your notes and stored messages. Loki will not
  build notes about you again. Recent messages are still kept for up to 30 days for conversation
  context and moderation.
- To have strikes reviewed or cleared, ask a server admin.
- For any other request (access, correction, deletion), use the contact above.

## Where data lives

In a database on the server of whoever runs this copy of Loki. Removing the bot from a Discord
server stops all collection there.

## Changes

If this policy changes, the date above changes with it.
