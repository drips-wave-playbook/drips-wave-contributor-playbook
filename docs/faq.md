# Frequently Asked Questions

Common questions from Drips Wave contributors, answered.

## General

### What is Drips Wave?

A recurring bounty cycle where developers resolve scoped issues in open-source projects and earn rewards. Each Wave runs for a set period (typically one week), contributors apply for issues, and rewards are distributed based on points earned.

### Is it free to participate?

Yes. There are no fees to join a Wave or apply for issues. However, you must complete KYC verification before earning rewards.

### Do I need a wallet to participate?

You need a **Stellar wallet with USDC support** to receive rewards. You can browse and apply without a wallet, but you won't be able to withdraw earnings.

### What is a Wave Program vs. a Wave?

- **Wave Program** — a long-running initiative around an ecosystem (e.g., Stellar Wave Program)
- **Wave** — a specific sprint within a Program (e.g., Stellar Wave 5)

## Finding and Claiming Issues

### How do I find issues?

Two ways:
1. **Drips Wave app** — Explore page, select a Wave, browse Issues
2. **GitHub** — search for the Wave label (e.g., `label:"Stellar Wave"`)

### Can I apply for multiple issues at once?

Yes, but there are limits:
- **15 pending applications** maximum
- **4 assigned issues per organization** per Wave

### Do I need to be assigned before starting work?

**Yes.** Never start coding or writing before a maintainer assigns you. PRs submitted without assignment may be closed without review.

### What if no one applies to my issue?

This FAQ is for contributors, but if you're waiting for others to apply: maintainers typically review applications within 24–48 hours. If an issue gets no applicants, it may roll to the next Wave.

## Points and Rewards

### How are points calculated?

| Complexity | Points |
|------------|--------|
| Trivial | 100 |
| Medium | 150 |
| High | 200 |

### How do points convert to dollars?

Points are **shares** of the Wave reward pool:

`Your Payout = (Your Points / Total Wave Points) × Reward Budget`

You cannot predict the exact amount in advance.

### When do I get paid?

After the Wave ends and the **7-day Compliment window** closes. Payouts are in **USDC on Stellar**.

### What is a Compliment?

A bonus awarded by maintainers for exceptional work. It adds points to your total and signals high-quality contribution.

### Do I need KYC?

**Yes.** Starting in Wave 5, KYC is required **before applying** for any issue. Complete it in Settings → Identity and Payments.

## PRs and Merging

### Why didn't I get points after my PR was merged?

Points are awarded when the **issue** is closed as completed. If your PR was merged but the issue is still open:
1. Check that you linked the issue with `Closes #<number>`.
2. Politely remind the maintainer to close the issue.
3. If unresponsive, open a Discord ticket.

### What if I can't finish on time?

**Notify the maintainer immediately.** They may reassign the issue or roll it to the next Wave. Going silent hurts your reputation.

### My PR was rejected — can I appeal?

Talk to the maintainer first via GitHub comments. If unresolved, contact Drips Wave support. Maintainers have final say on code quality, but support can mediate disputes.

## Account and Setup

### Why do I need to verify my phone number?

Drips may require phone verification as a security measure to prevent fraud. It's used only for verification.

### Can I change my wallet address after earning rewards?

Rewards are sent to the wallet address on file when you withdraw. Set up your wallet correctly from the start.

### How do I withdraw rewards?

1. Go to **Wave → Reward Grants** in the Drips app.
2. Request a **test transaction ($1)** first to verify your wallet setup.
3. After the test succeeds, request the **full withdrawal**.

Full withdrawals process within 1–3 business days.

## Troubleshooting

### My test transaction failed or didn't arrive

Check:
- Wallet address is correct
- USDC trustline is active
- Wallet has enough XLM for the minimum balance
- If using an exchange, the correct memo was included

### The issue is closed but I didn't get points

1. Verify the issue was "Closed as **Completed**."
2. Wait 24–48 hours.
3. Open a Discord ticket: **"I didn't receive Points for an Issue."**

### I can't apply — application limit reached

You have **15 pending applications** or **4 assignments** in that org. Withdraw unused applications or resolve an assigned issue to free slots.

### The maintainer is unresponsive

- Wait 48 hours during an active Wave.
- Comment politely on the PR.
- If still unresponsive, open a Discord ticket. Drips support can intervene.
