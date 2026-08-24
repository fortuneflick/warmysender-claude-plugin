# WarmySender for Claude Code & Cowork

Run your outreach on autopilot from Claude. This plugin connects Claude Code and Cowork to [WarmySender](https://warmysender.com) — cold email, email warmup, LinkedIn, Instagram, lead database and real-time email verification — through WarmySender's hosted MCP server (66 tools).

## What you can do

- Build, launch, pause and resume cold email campaigns; enroll prospects singly or in bulk
- Create and manage LinkedIn campaigns, posts and Recruiter jobs; run Instagram DM campaigns
- Verify email addresses and turn results into clean prospect lists
- Read warmup stats and mailbox health — including whether mail is actually arriving
- Search and save leads from a built-in B2B database
- Ask "why did this campaign send nothing today?" and get a plain-language answer

## Bundled skills

- **campaign-doctor** — diagnose a quiet campaign from real skip reasons
- **cold-email-launch** — idea → approved copy → enrolled prospects → safe launch
- **list-hygiene** — verify lists allowance-first and build clean prospect lists

## Setup

1. Install the plugin.
2. The `warmysender` MCP server connects to `https://warmysender.com/mcp` — sign in via OAuth when prompted (Google, Apple or email code).
3. Requires a WarmySender account on a paid plan. Email features need a connected mailbox; LinkedIn/Instagram need the respective add-on. Accounts are connected in the WarmySender app — deliberately not through the agent.

## Safety model

The agent never sends a message, DM or invite directly and can never raise a limit. Every write hands off to WarmySender's scheduler, which paces all actions within safe caps and gradual ramps — identically for human and agent callers.

## Privacy Policy

WarmySender's privacy policy: https://warmysender.com/privacy

The plugin itself stores nothing; all data access goes through the authenticated MCP connection to your own WarmySender workspace.

## Support

hello@warmysender.com · Docs: https://warmysender.com/mcp
