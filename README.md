# UX Fair Dealing

<img src="badge.png" width="200" alt="UX Fair Dealing badge">

If it feels like app developers are manipulating you, they probably are.

## What Is UX Fair Dealing?

UX Fair Dealing (UXFD) is an open, community-driven standard for ethical user interface design of B2C apps, including a trust badge that you can display on your web or mobile product. It is a simplified list of best practices, avoiding "[dark patterns](https://www.deceptive.design/)," grounded in leading global regulations (EU [DSA](https://digital-strategy.ec.europa.eu/en/policies/digital-services-act)/[DFA](https://www.europarl.europa.eu/legislative-train/theme-protecting-our-democracy-upholding-our-values/file-digital-fairness-act)).

While the topic of manipulative UX design goes far beyond the list below, it provides a set of items whose violation are generally provable via app screenshots. It's a start.

* **Purpose:** Encourage fair B2C user experience patterns with a clear, self-auditable checklist.
* **How:** Ensure compliance, submit a PR adding your app to the [apps.md](apps.md) list, and display the badge.
* **Accountability:** Anyone can publicly document existing dark patterns via GitHub Issues.

Join developers, advocates, and users in making trust and fair treatment the baseline for digital products.

## The Standard: Core Principles & Checklist

Adoption means you meet *all* the following requirements:

1. Show value before asking for money
*Don't require a credit card before letting users experience the product.*
2. Be honest and upfront with pricing
*Don’t hide fees, reveal pricing at the end of onboarding, or steer declines into secret discounts.*
3. Default to user privacy and choice
*No auto-ticked boxes for marketing, sharing, or auto-renew. Users should opt in, not have to opt out.*
4. Don’t fake urgency, scarcity, or social proof
*Countdowns, “only X left,” or “just booked!” must be real, not manufactured.*
5. Give fair warning before new charges
*Provide reasonable notice before a trial converts to a subscription.*
6. Give users clear, neutral choices — no manipulation
*No confirm-shaming, guilt-tripping, or double negatives.*
7. Make it easy to leave or opt out
*Canceling or opting out should be no harder than signing up.*

\* See [dsadfa-eu-source](#sources) for regulatory foundation.

## How to Adopt UXFD (& Use the Badge)

1. **Complete the checklist above.** Confirm that your live product *fully* complies. File a PR on this repo adding your app (alphabetically) to 
2. **Add the badge** (\[see `/badge/` for image assets\]) to your site/app footer or info page.
  * The badge *must* link directly to this README or a specific tagged version.
3. **Declare adoption** in your app's About/Privacy page. Example: "\[App\] adheres to UX Fair Dealing Standard v1.0, adopted on \[DATE\], reviewed at: \[REPO_LINK_OR_URL\].
4. **Be accountable**: By adopting, you agree users may report potential violations for public review.

## The Hall of Shame: Public Accountability

The Deceptive Design [Hall of Shame](https://www.deceptive.design/hall-of-shame) hasn't received any updates since mid-2025. This repo simplifies that cathartic process.

* **Anyone may submit a Hall of Shame report as a GitHub issue** (choose **Hall of Shame Report** under *Issues → New issue*).
  * Use the **Hall of Shame** issue template: include app/service name, violated checklist item, screenshot(s), and repro steps.
* **Eligibility:**
  * *Adopter shaming* — Focus: Products declaring UXFD adoption and found in violation (highest priority for investigation and transparency)
  * *General shaming* — Products not claiming UXFD but causing egregious harm may also be listed, labeled as “Non-adopter.”
* **Right of Response:**
  * Anyone listed may submit a public reply or remediation note as a PR.
* **No central arbitration or removal:**
  * Submissions are merged if the required facts and screenshots are present—the public record is the evidence.
* **Note:** Abuse (inaccurate or malicious shaming) is handled through the standard GitHub moderation/reporting process.

## Sources & Legal Basis

* EU Digital Fairness Act ([DFA](https://www.europarl.europa.eu/legislative-train/theme-protecting-our-democracy-upholding-our-values/file-digital-fairness-act)) (draft, 2026)
* EU Digital Services Act ([DSA](https://digital-strategy.ec.europa.eu/en/policies/digital-services-act)) (in force 2024)
* Brignull’s Deceptive Design Patterns [taxonomy](https://www.deceptive.design/types)
* Mathur et al. (2019) academic taxonomy
* Civil society input (EDRi, etc.)

*This README is the living, one-source-of-truth standard. For questions or improvements, open an issue or PR.*