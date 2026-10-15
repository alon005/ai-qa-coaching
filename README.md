# AI QA & coaching system

**AI that listens to a call center's calls, scores how each one was handled, and coaches the team.**

*Showcase page. The code is private because it runs a live business; a walkthrough is available on request.*

---

## What it does

- **Analyses calls:** call recordings and transcripts go to Gemini, which judges how each call was handled: the opening, qualifying the customer, transparency on price, empathy, and whether the job was booked.
- **Coaches:** writes QA coaching messages for the agents, concrete and tied to their own calls.
- **Remembers:** keeps a running database of performance analyses for both call-center agents and technicians, so trends show over time, not just single calls.
- **Checks against the data:** the analyses are read alongside the CRM's own numbers (submitted jobs, answer rates, outcomes), not on their own.

It was the first of the two systems. The operations reporting layer (see [ops-reporting](https://github.com/alon005/ops-reporting)) came later, on top of it, to deliver what QA found to the people who act on it.

It is integrated into [Ava Connects](https://github.com/alon005/ava-connects).

**Stack:** Gemini · Cloudflare Workers · Postgres · Google Apps Script (first version)

— Alon Schneidman · [GitHub](https://github.com/alon005) · [LinkedIn](https://www.linkedin.com/in/alonschneidman)
