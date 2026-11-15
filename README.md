# Agee plugin for Claude

Agee is a case management platform for law firms. This plugin connects Claude to your firm's Agee account so you can work with your cases from a conversation.

## What it does

The plugin adds Agee's hosted connector at `https://mcp.agee.law`. Once you sign in, Claude can:

- Bring you up to speed on a matter: parties, counsel, judge, upcoming deadlines, recent filings and open tasks.
- Find and read documents, court filings and case email, by keyword or by meaning, within a case or across the firm.
- Check what is due: hearings, court deadlines, and deadlines taken from filings that an attorney has not yet reviewed.
- Record work when you ask: tasks, calendar events, draft time entries, and entries in the case wiki and notes.
- Save a memo or summary to the case file for attorney review.

Deleting, cancelling and removing are separate tools, so you can block them on their own in Claude's connector settings. The connector cannot file with a court or move money.

## What you need

An active user account at a law firm that uses Agee. A Claude Team or Enterprise plan is recommended for client work.

## Install

In Claude Code:

```
/plugin marketplace add Agee-LLC/agee-claude-plugin
/plugin install agee@agee-plugins
```

In Claude on the web or desktop: Settings, Customize, Plugins, Add, Add from a repository, then enter `Agee-LLC/agee-claude-plugin`.

## Sign-in and your data

Each person signs in with their own Agee account. Which firm's data you can reach is decided on Agee's servers from that sign-in, never from anything Claude sends. Every change made through the connector is recorded in your firm's audit trail.

## Use with care

AI output can be wrong. Before legal advice based on it reaches a client, a qualified attorney must review it. Case files can contain sensitive and medical information.

## Help

- Guide: https://agee.law/help/agee-mcp
- Support: support@agee.law
- Privacy: https://agee.law/privacy
- Terms: https://agee.law/terms

Copyright Agee, LLC. All rights reserved.
