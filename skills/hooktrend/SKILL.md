---
name: hooktrend
description: "Short-form trend research on TikTok and YouTube through the HookTrend MCP. Use whenever the user asks what is trending, going viral or breaking out in a niche or topic, which creators, sounds or hashtags are rising, wants to study a TikTok or YouTube account (a @handle or profile link), or wants ongoing research on a content brief. Not for Instagram."
---

# HookTrend

HookTrend finds the TikTok and YouTube videos getting many times their creator's usual views ("× usual"), in any niche or topic.

## Connect

The HookTrend MCP server must be connected: `https://hooktrend.com/api/mcp`.
If its tools (`whats_breaking_out`, `find_videos`, `niche_report`…) are not available, tell the user to add it (steps for every client: https://hooktrend.com/mcp) and stop.

## Work from the live instructions

HookTrend's instructions change as it improves, so this skill does not copy them. Follow the MCP server's own instructions, and read the live guide when you need detail: https://hooktrend.com/agents/guide.md

Three rules that never change:
1. Compare videos by × usual, never by raw views, and never across TikTok and YouTube.
2. Before anything that costs credits, quote the cost and wait for the user's yes; only then call with `user_approved: true`.
3. Use only the numbers and links the tools return.

Skill version: 2026-11-14
