# Metric definitions

These definitions are the source of truth for every dashboard and report.

| Metric | Definition |
|---|---|
| **Activated account** | An account whose users launch their first checklist (`checklist_launched`) within **14 days** of signup (`signed_up`). |
| **Activation rate** | Activated accounts / accounts that signed up in the period, counting only signups at least 14 days old. |
| **MRR** | Monthly recurring revenue from active subscriptions. Annual plans count as 1/12 of the annual price. |
| **Day-90 revenue retention** | For accounts whose first payment was at least 90 days ago: MRR 90 days after first payment / MRR at first payment, summed over the cohort. |
| **Questions per account** | Internal questions about a customer account (asked to AskRight) per active account-month. |
| **Handling time** | Minutes a teammate spends answering a question, from the AskRight log. |
| **Acquisition source** | The HubSpot campaign that created the company, else its original source (organic, outbound, referral). |
