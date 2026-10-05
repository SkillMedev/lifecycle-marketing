# Lifecycle & Email Marketing

**For lifecycle marketers: turn signups into retained users and keep email in the inbox.** — built in-house by [Skill&nbsp;Me](https://skillme.dev/?utm_source=github&utm_medium=readme&utm_campaign=pack-lifecycle-marketing).

Reach for this when you own a lifecycle or email program and need it to actually move retention, not just ship more sends. It takes you from a stage-by-stage journey map and behavioral segments through onboarding drips, multi-channel push, and dormant-user win-backs, with deliverability practices guarding your sender reputation so the work lands in the inbox. The payoff: a coherent program where every message has a clear job and a measurable signal, instead of disconnected blasts that burn your list.

## Install

- **Claude, ChatGPT, Codex, Cursor (connector):** [install the whole pack from skillme.dev](https://skillme.dev/pack/lifecycle-marketing?utm_source=github&utm_medium=readme&utm_campaign=pack-lifecycle-marketing) — one connection, then ask for any skill by name.
- **As files for Codex, Cursor, or Claude Code:** `npx @skillme/cli add lifecycle-journey-map email-drip-builder win-back-campaign segmentation-strategy push-notification-copy email-deliverability email-newsletter-pro churn-reduction --target all`
- **With the skills CLI:** `npx skills add SkillMedev/lifecycle-marketing`
- **Manually:** copy any `skills/<slug>/SKILL.md` into `.agents/skills/`, `.cursor/skills/`, or `.claude/skills/`.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Skills in this pack

- **[Lifecycle Journey Map](skills/lifecycle-journey-map/SKILL.md)** — Builds a customer lifecycle journey map with behavioral entry/exit criteria per stage, one goal and one signal per stage, message briefs, and dead-zone flags.
- **[Email Drip Builder](skills/email-drip-builder/SKILL.md)** — Designs automated onboarding and activation drip sequences with behavior-gated sends, exit
- **[Win-Back Campaign](skills/win-back-campaign/SKILL.md)** — Designs segmented win-back email sequences for dormant users - dormancy tiers, a three-beat sequence with a single proportional incentive, and a suppression rule - and measures success by re-activation, not opens.
- **[Segmentation Strategy](skills/segmentation-strategy/SKILL.md)** — Builds a behavioral segmentation system for lifecycle messaging - RFM-based segments, event-driven membership triggers, one next action per segment, size audits, and send-time suppression rules.
- **[Push Notification Copy](skills/push-notification-copy/SKILL.md)** — Writes push and in-app notification copy that survives lock-screen truncation, ties every send to a user-specific trigger, deep-links to the exact destination, and respects frequency caps.
- **[Email Deliverability](skills/email-deliverability/SKILL.md)** — Audits and protects sender reputation and inbox placement for permissioned marketing and lifecycle email - SPF, DKIM, and DMARC authentication, domain warmup, bounce and complaint thresholds, and engagement sunsetting - and delivers a scored deliverability audit checklist with a remediation order.
- **[Email Newsletter Pro](skills/email-newsletter-pro/SKILL.md)** — Write recurring email newsletters - subject lines that earn the open, preview text that extends them, a body structure readers finish, and cadence rules that keep the list healthy.
- **[Churn Reduction](skills/churn-reduction/SKILL.md)** — Diagnoses SaaS churn root causes through cohort analysis and a seven-category taxonomy, then builds segmented intervention playbooks ranked by frequency, revenue at stake, and addressability - including save-offer economics.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev/browse?utm_source=github&utm_medium=readme&utm_campaign=pack-lifecycle-marketing).
