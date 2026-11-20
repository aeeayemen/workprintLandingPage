# Workprint — Atlassian App Distribution Portal

Public documentation, legal disclosures, and customer support portal for **Workprint** — an Atlassian Forge & Rovo AI capacity intelligence application for Jira, Confluence, and Bitbucket.

Developed by **Anas Adel Ismail** and **Abdulrahman Babeker** (Yemen).

This project hosts the publicly accessible pages required for Atlassian Cloud app distribution (**Start sharing your app** / **Edit distribution controls**):

1. **Customer Support Page:** [`contact.html`](./contact.html) / [`/contact`](./contact/)
2. **Privacy Policy & Personal Data Declaration:** [`privacy-policy.html`](./privacy-policy.html) / [`privacy.html`](./privacy.html) / [`/privacy`](./privacy/)
3. **Terms of Service:** [`terms.html`](./terms.html) / [`/terms`](./terms/)
4. **App Overview & Architecture:** [`index.html`](./index.html) & [`about.html`](./about.html)
5. **Knowledge Base & FAQ:** [`FAQ.html`](./FAQ.html)
6. **Squad Capacity Roster:** [`team.html`](./team.html)

---

## Technical Summary & Distribution Compliance

| Field | URL / Route | Notes |
|---|---|---|
| **Customer Support URL** | `https://workprint.atlassian.net/contact` or `contact.html` | Maintainer: Anas Adel Ismail (WhatsApp: `+967770300304`, Email: `anasadelismail2023@gmail.com`) |
| **Privacy Policy URL** | `https://workprint.atlassian.net/privacy` or `privacy-policy.html` | Forge scopes, tenant security, and Personal Data Declaration (Zero Outside Storage) |
| **Terms of Service URL** | `https://workprint.atlassian.net/terms` or `terms.html` | Cloud app licensing, acceptable use, and governing law (Yemen / Atlassian Marketplace) |

### Maintainer & Core Team
- **Anas Adel Ismail** — Founder & Lead Architect (Atlassian Forge & Rovo AI)
- **Abdulrahman Babeker** — Core Systems & Platform Engineer
- **Country:** Yemen
- **Email:** [`anasadelismail2023@gmail.com`](mailto:anasadelismail2023@gmail.com)
- **WhatsApp:** [`+967770300304`](https://wa.me/967770300304)
- **GitHub:** [`https://github.com/aeeayemen`](https://github.com/aeeayemen)
- **Atlassian Site:** [`https://workprint.atlassian.net/`](https://workprint.atlassian.net/)

### Personal Data Declaration (Zero Outside-Cloud Storage)
- **Runtime:** Atlassian Forge Node.js 22 serverless execution inside Atlassian Cloud.
- **Data Retention:** Zero personal data or user identifiers (such as Atlassian `accountId`) are copied, stored, or cached beyond 24 hours outside Atlassian Cloud.
- **Egress:** Strictly restricted to declared Bitbucket Cloud REST API v2 (`https://api.bitbucket.org`).
