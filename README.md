<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=ai%20it%20helpdesk%20voice%20agent;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=ai-it-helpdesk-voice-agent&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/ai-it-helpdesk-voice-agent?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/ai-it-helpdesk-voice-agent?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent) · [🐞 Report Issue](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent/issues/new) · [⭐ Star](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/ai-it-helpdesk-voice-agent/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

# AI IT Helpdesk Voice Agent — Max

Apex Enterprises IT Helpdesk Voice Agent built with **Vapi** for the voice interface and **n8n** for backend tool orchestration.

## Demo

🎥 **Loom Demo:** https://www.loom.com/share/1fe94e9c3cb94fd98bc0a4aa1555c285

## Overview

Max is an AI voice assistant for employee IT support. The workflow covers:

- Employee identity verification
- IT troubleshooting knowledge base
- Ticket creation for unresolved issues
- Ticket status lookup
- Tier-2 escalation
- Confirmation notification
- Professional call closure

## Tools

The voice assistant is connected to these n8n-backed tools:

1. `verify_employee`
2. `create_it_ticket`
3. `check_ticket_status`
4. `escalate_case`
5. `send_confirmation`

## Architecture

```text
Employee Caller
      ↓
Vapi Voice Agent — Max
      ↓
n8n Webhook Tools
      ↓
Verification → Troubleshooting → Ticketing → Escalation → Confirmation
```

## Demo Scenarios

### Flow 1 — Resolved without ticket

Password-reset guidance is provided through self-service troubleshooting. When the employee confirms the issue is resolved, no ticket is created.

### Flow 2 — Unresolved VPN issue

The employee is verified, VPN troubleshooting is attempted, the issue remains unresolved, an IT ticket is created, ticket status is checked, the case is escalated to Tier-2, and confirmation is provided.

## Platform Note

The assessment specification names xAI Voice Agent Playground and Twilio. The working simulated voice demonstration uses Vapi because the xAI voice runtime required account credits. The n8n backend remains the tool/orchestration layer. This substitution is disclosed for transparency.

## Submission Evidence

- Vapi assistant configuration
- n8n workflow/tool configuration
- Loom demonstration
- Supporting implementation report

## Repository

**Repository:** `shaikshahid777/ai-it-helpdesk-voice-agent`
