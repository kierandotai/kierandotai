# Kieran Sweeney

I build [Cred](https://cred.ninja/?utm_source=github&utm_medium=profile), open-source credential delegation for AI agents.

[kieran@kierans.net](mailto:kieran@kierans.net) · [LinkedIn](https://linkedin.com/in/kierandotai)

## Cred

In plain terms: an agent gets a limited pass, not the master key. Access is narrow, expires, gets logged, and can be revoked.

When an agent needs a user's Google Calendar, Slack or GitHub, Cred checks the agent's identity and the user's consent, then returns a short-lived token or a brokered handle. Refresh tokens stay in the encrypted vault.

**Start here**

- [Watch a simulated run](https://cred.ninja/sandbox?utm_source=github&utm_medium=profile) in your browser. It uses mock data and needs no install.
- Run Cred for real with `npx @credninja/create-app my-cred-server`, or follow the [quickstart](https://github.com/cred-ninja/sdk#quickstart).
- Read the [source](https://github.com/cred-ninja/sdk): TypeScript and Python packages under Apache-2.0.
- Read the [Internet-Draft](https://datatracker.ietf.org/doc/draft-sweeney-wimse-credential-delegation/) I wrote for the protocol. It is an individual draft, not an adopted standard.

**What is in the SDK**

- OAuth 2.0, with PKCE where the provider supports it, and adapters for Google, GitHub, Slack, Notion, Salesforce, Linear and HubSpot
- An AES-256-GCM token vault and Ed25519-signed delegation receipts
- A policy guard for rate limits, scope filters, time windows and URL allowlists
- Integrations for MCP, Vercel AI SDK, LangChain, CrewAI, OpenAI Agents SDK, AutoGen and Semantic Kernel

## About

- **Now:** Technical Founder of Cred, an open-source project. I designed and shipped it solo, from the SDK and framework integrations to the docs and protocol draft. Active in the IETF WIMSE and OAuth working groups.
- **Before:** Top Closer 2025 as an Account Executive at Total Quality Logistics. Core Steward at ETHDenver, a 20,000-person developer conference. Also ran 0xDrip, a consumer eyewear brand.
- **Based in:** DC metro.

[Substack](https://substack.com/@kierans) · [kieran.ai](https://kieran.ai)
