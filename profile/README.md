<p align="center">
  <a href="https://spix.sh">
    <img src="https://img.shields.io/badge/spix.sh-Visit%20Website-blue?style=for-the-badge" alt="Website" />
  </a>
</p>

<h3 align="center">Communications infrastructure for AI agents</h3>

<p align="center">
  Phone calls, SMS, and email — so your agents can reach humans in the real world.
</p>

---

### What is Spix?

Spix gives AI agents real communication capabilities. Your agent gets a dedicated phone number and email address, then uses them to make calls, send texts, and send emails — just like a human would.

**Phone Calls** — Outbound voice calls with real-time speech, automatic transcription, answering machine detection, and sub-300ms latency.

**SMS** — Send and receive text messages from a dedicated number with compliance handling built in.

**Email** — Send and receive from a real address with thread history and attachment support.

### How it works

```bash
# Install
curl -fsSL https://spix.sh/install | sh

# Make a phone call
spix call make +1234567890 \
  --persona "You are a friendly appointment reminder" \
  --briefing "Remind about dentist appointment tomorrow at 2pm"

# Send an SMS
spix sms send +1234567890 "Your order has shipped!"

# Send an email
spix email send user@example.com --subject "Invoice" --body "Attached is your invoice."
```

### Integrate anywhere

| Method | Description |
|--------|-------------|
| **CLI** | Single binary, no dependencies. Linux and macOS. |
| **REST API** | Standard HTTP endpoints with Bearer token auth. |
| **MCP** | Model Context Protocol tools for direct agent integration. |
| **Dashboard** | Web UI at [app.spix.sh](https://app.spix.sh) for monitoring and management. |

### Links

- [Website](https://spix.sh)
- [Dashboard](https://app.spix.sh)
- [API Documentation](https://api.spix.sh/docs)
