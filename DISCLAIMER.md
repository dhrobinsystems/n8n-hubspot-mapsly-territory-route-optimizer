# ⚠️ Disclaimer & Liability Limitation

**Repository:** `n8n-hubspot-mapsly-territory-route-optimizer`
**Author:** DH Robin (dhRobin Systems)
**Last updated:** November 2026

Use at your own risk. The code, workflows, and scripts in this repository (`n8n-hubspot-mapsly-territory-route-optimizer`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes, without limitation, missed, late, duplicated or double-booked site visits, inaccurate geocodes, routes or travel-time estimates, unassigned visits that go unnoticed, overtime, vehicle or travel costs, customer dissatisfaction, API charges or rate-limit penalties, and any incident involving field staff while travelling to or performing a visit.

* **No Warranty:** All software, n8n JSON blueprints, JavaScript modules and Mapsly endpoint contracts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement. The optimiser is a heuristic. Its routes are not guaranteed to be optimal, feasible in real traffic, or compliant with your operational rules.

* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, a Mapsly test data source, a test Connecteam scheduler and a test Slack channel, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live HubSpot, Mapsly, Connecteam or Slack credentials. Keep `CONNECTEAM_PUBLISH_SHIFTS=false` until dispatchers have reviewed the draft schedules over a representative period. Treat every generated route and schedule as a draft that a person must review before technicians rely on it. The workflow doesn't replace driving-time, working-time, rest-break, safety or lone-worker rules that apply to your field staff.

* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA), labour and working-time regulations, and security policies of HubSpot, Mapsly, Connecteam, Slack and any connected services. That includes confirming a lawful basis for sharing customer site addresses with mapping and workforce-management providers, keeping technicians' personal and location data (such as home addresses) out of the roster unless that's lawful and necessary, restricting who can read dispatch channels and n8n executions, keeping credentials and secret endpoint URLs out of version control, and reviewing every automatically created shift.

* **No Affiliation:** This project is independent. It is not affiliated with, endorsed by, or sponsored by HubSpot, Inc., Mapsly LLC, Connecteam, Slack Technologies, LLC, Salesforce, Inc., or n8n GmbH. All product names and trademarks belong to their respective owners and are used only to describe compatibility.

* **Fictional Sample Data:** All business names, street addresses, record IDs, technician names, user IDs, territories and coordinates in the pinned sample data and documentation are fictional or synthetic and exist only for testing. Any resemblance to real people, places or organisations is coincidental. Placeholder values such as `YOUR_HUBSPOT_PRIVATE_APP_TOKEN`, `YOUR_MAPSLY_API_KEY`, `YOUR_CONNECTEAM_API_TOKEN`, `YOUR_SLACK_WEBHOOK_URL` and `YOUR_HUBSPOT_PORTAL_ID` must be replaced with your own values, which you keep in environment variables or n8n credentials.

* **Not Professional Advice:** Nothing in this repository is legal, employment, safety or compliance advice. Consult qualified professionals for decisions in those areas.

## Open-Source License Notice

This project is released under the MIT License. You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions in [LICENSE](./LICENSE). The MIT License's own warranty disclaimer and limitation of liability apply in addition to this document. If the two conflict, the terms more protective of the author apply to the extent permitted by law.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
