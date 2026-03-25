# Frictions

## The Support Relay Bottleneck

**The Friction:** In many fast-growing companies, internal support channels become bottlenecked with manual relay requests. For example: "Reach out to customer ID 12345 and tell them we need more banking info." Currently, a human has to read this unstructured message, find the customer in a database, switch to a CRM/email tool, and manually send the message.

**Your Canvas:** How would you eliminate this friction? Design and build a prototype using mock data that solves this bottleneck. You decide the form factor and architecture: Is it a Slack bot with a human-in-the-loop approval UI? An event-driven background service? A brand-new internal dashboard? Show us how you would bridge the missing interface and data to make this workflow effortless.

## The Stale Data Spreadsheet

**The Friction:** Financial operations teams often manually compile daily reports (like funding metrics or margin calls) by pulling numbers from various systems, pasting them into a spreadsheet, and posting a summary screenshot to a chat channel. Because humans are acting as the integration layer, the process is slow, prone to fat-finger errors, and the data is instantly stale.

**Your Canvas:** How do we turn this team into "data producers" rather than manual "button pushers"? Build a system that removes the human from this reporting loop. You decide how the AI ingests mock financial data, ensures mathematical accuracy (preventing hallucinations), and how the final verified insights are presented to stakeholders.

## The Context-Blind Code Reviewer

**The Friction:** Engineering teams increasingly use AI tools to review code. However, when an AI reviews a Pull Request in isolation, it only sees the code diff. It lacks the broader architectural context, leading to generic feedback that ignores system-wide design decisions.

**Your Canvas:** How do you give an AI a "whole architecture view"? Build a prototype that allows an AI to review mock code changes while aware of a broader system context. You decide the approach: A custom interactive web UI? An MCP (Model Context Protocol) integration? A GitHub Action? Prove how you would supply the missing context and data to the LLM so it makes intelligent, system-aware architectural reviews.

## The Alert Fatigue & Incident Triage Friction

**The Friction:** Engineering teams get bombarded with monitoring alerts (Sentry, Datadog, AWS CloudWatch). Many are noise, but when a real incident happens, developers scramble to manually cross-reference the alert with recent Pull Requests, logs, and deployment histories to find the root cause.

**Your Canvas:** How do we stop engineers from acting as manual log-correlators? Build a smart triage system. You decide how it works: does it intercept mock webhook alerts, query a mock GitHub API for recent changes, and post a summarized "probable root cause" into an incident channel? Bridge the gap between raw alert noise and actionable engineering insights.

## The User Feedback Blackhole

**The Friction:** Sales and Customer Success teams constantly hear feature requests and bug reports. They usually dump this unstructured text into a massive #product-feedback Slack channel or a messy spreadsheet. Product Managers then have to spend hours manually reading, categorizing, and tallying these to figure out what users actually want.

**Your Canvas:** How do we turn unstructured chatter into structured product data? Build a system that captures mock user feedback, categorizes it by sentiment, feature area, and urgency, and presents it. You decide the interface: A real-time product dashboard? An automated Jira-ticket creator? Show us how you'd make the Product Manager's job effortless.

## The "Tribal Knowledge" Bottleneck

**The Friction:** As companies scale, documentation gets fragmented across Notion, Google Docs, Slack history, and Jira. When new hires join, they can't find anything, so they end up pinging senior engineers with the exact same 50 questions week after week. The data exists, but the interface to retrieve it is broken.

**Your Canvas:** How do you make company knowledge instantly accessible without adding more tools? Build a prototype that solves this silo. Do you build an AI agent that listens to an #ask-engineering channel and auto-replies based on mock company docs? A unified search interface? You decide how to connect the missing data to the user.

## The Manual KYC / Compliance Trap

**The Friction:** Compliance and Ops teams often have to manually open user-submitted documents (like Proof of Address or ID verification), read the text, and cross-reference it against what the user typed into the database to ensure they match before approving an account.

**Your Canvas:** How do we remove the human from this repetitive verification loop? Build a pipeline that ingests mock user documents (text or images), extracts the structured entity data, compares it to a mock user record, and either auto-approves the match or flags discrepancies for human review.
