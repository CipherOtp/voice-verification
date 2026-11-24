# voice-verification

Automated outbound call flows for one-time-code and identity verification.

## Stack

- Python / Flask
- TwiML and TeXML call control
- Twilio and Telnyx for PSTN
- SQLite for state

## Flow

1. Number validation
2. Outbound call with machine detection
3. DTMF gather for the code
4. Webhook result back to a Telegram operator panel

Handles US numbers only. Built for low-volume, high-touch verification work.
