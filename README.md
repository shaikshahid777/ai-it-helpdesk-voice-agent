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
