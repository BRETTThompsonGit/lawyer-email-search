# Email Search Product Research

Research date: November 14, 2026

Several existing products cover substantial parts of the proposed expert-witness application. The recommended first comparisons are Intella for local investigation capabilities, MailDex for inexpensive local archive search, and Nextpoint for cloud pricing suited to large data volumes. No product has been selected or tested against a representative case.

The comparison below records vendor-documented features and published USD prices. Prices are a dated snapshot; quote-only products have no verified public numeric rate in this research.

## Local Applications

| Product | Platform and relevant capabilities | Published price and qualifications |
| --- | --- | --- |
| [Intella](https://www.vound-software.com/10-100-250) | Windows. PST/OST processing, advanced search, email threading, tagging, combined identities, and communication graphs. Desktop editions have different evidence-size limits; Professional has no edition-imposed size limit. | Quote required. The vendor FAQ lists annual maintenance/support at 20% of the purchase price. [Pricing FAQ](https://www.vound-software.com/faq), [feature and platform manual](https://www.vound-software.com/docs/intella/3.1/Intella%20User%20Manual.html). |
| [MailDex](https://www.encryptomatic.com/maildex/) | Windows. Searches multiple PST/OST archives, indexes messages and attachments into projects, visualizes metadata patterns, and exports results. Processing stays on the computer. Its full threading and case-role workflow require evaluation. | $139 permanent license, including one year of updates/support; support renewals are separate. A 15-day trial is available. [Pricing and feature comparison](https://www.encryptomatic.com/msgviewer/compare.html). |
| [dtSearch Desktop](https://www.dtsearch.com/PLF_Features_2.html) | Windows. Boolean, phrase, proximity, fuzzy, metadata, and custom synonym searches across emails and attachments. Useful as a search-capability benchmark. | $249 single-user license, including at least one year of updates/support. A separate $1,225/year investigative license permits successive installations on different machines under its terms. [Store and license options](https://www.dtsearch.com/dtStore.html). |
| [Aid4Mail Investigator](https://www.aid4mail.com/editions/aid4mail-investigator) | Windows. Email processing, filtering, conversion, recovery, Boolean/proximity searching, and attachment search. Relevant to preparing large datasets; AI features are configured separately from conventional filtering. | $999/year, billed annually. Converter is $299/year but lacks advanced investigation features. [Pricing](https://www.aid4mail.com/pricing), [AI configuration](https://www.aid4mail.com/docs/ai-guide). |
| [DocFetcher](https://docfetcher.sourceforge.io/) | Mac, Windows, and Linux. PST and document search using Boolean, phrase, proximity, wildcard, and fuzzy queries, with text-only previews and highlighted matches. Its documented scope is general desktop search. | Free and open source. |

## Cloud Applications

| Product | Relevant capabilities and limits | Published price and qualifications |
| --- | --- | --- |
| [Nextpoint](https://www.nextpoint.com/platform/ediscovery) | PST processing, advanced search, review, tagging, custom coding, and case timelines. Verify full conversation threading across mailboxes separately from email/attachment-family grouping. | Quote required. Standard plans advertise monthly per-user pricing, unlimited data/cases, and no separate hosting, OCR, deduplication, or production charges. Exact seat minimums, commitments, and onboarding costs require a quote. [Plans](https://www.nextpoint.com/ediscovery-pricing). |
| [Everlaw](https://www.everlaw.com/pricing/) | Rich email threading, communication visualization, review tools, timelines, and fact management. A useful comparison for the broader future product. | Quote required, based on hosted data volume, with unlimited users. Pay-as-you-go or annual volume commitments; billing uses each database's monthly peak size, including hosted productions. [Billing FAQ](https://support.everlaw.com/hc/en-us/articles/205660765-Billing-and-Pricing-FAQ). |
| [GoldFynch](https://goldfynch.com/) | Browser-based upload, search, tagging, review, and export. Its published support article says it lacks built-in email threading and describes a same-subject workaround. [Threading limitation](https://support.goldfynch.com/support/solutions/articles/21000003813-finding-duplicate-emails-with-same-subject-to-exclude-from-review-alternative-to-email-threading). | Standard per-case plans include $27/month for 3 GB, $76/month for 10 GB, and $652/month for 100 GB. These are case-storage tiers, not promises that a PST of the same size fits after extraction. [Published tiers](https://goldfynch.com/docs/case_creation/docs_how_to_change_case_size/), [pricing details](https://goldfynch.com/pricing.html). |

GoldFynch has separate [processing plans](https://goldfynch.com/processing-plans.html) for larger cases, with a one-time processing fee and recurring case fee; they require a GoldFynch Organization. Compare a complete quote for the intended data volume and retention period. Its pricing-page FAQ contains a $5.50/GB statement at 100 GB that conflicts with the current plan table and interactive slider; the verified 100 GB tier above is $652/month.

## Other Products Screened

- [Logikcull](https://www.logikcull.com/pricing): current numeric pricing requires a quote; monthly pay-as-you-go pricing is based on stored GB, with annual subscription options.
- [Lexbe](https://lexbe.com/ediscovery-platform/pricing/): quote-based pricing with pay-as-you-go and monthly options. Its [search and threading features](https://lexbe.com/ediscovery-platform/features/) merit further comparison.
- [DISCO](https://csdisco.com/pricing): quote-based discovery platform; published packages include AI capabilities.
- [Relativity](https://www.relativity.com/platform/pricing/): quote-based discovery platform with processing and review capabilities.

Historic third-party rate cards were not used as current prices.

## Fit With the No-AI Requirement

Traditional search, threading, and identity-based exploration can support the proposed workflow without generative interpretation. Intella's manual documents its threading process and identity/communication views; dtSearch documents conventional query methods and custom synonym expansion.

Some products also bundle AI. Nextpoint distinguishes ordinary search in Essential from AI Intelligent Search in Advanced. Aid4Mail documents separate AI task configuration. Everlaw provides [project controls for disabling its generative AI features](https://support.everlaw.com/hc/en-us/articles/58212758083867-Manage-Everlaw-AI-at-the-Project-Level). GoldFynch advertises machine-learning-assisted searches. These facts do not establish that every background operation in those products is free of machine learning; the stricter no-AI MVP boundary must be checked when evaluating a substitute.

## Implications for the Project

Existing products establish substantial competition for archive ingestion, advanced search, threading, and communication exploration. A possible opportunity is a simpler workflow specifically for expert witnesses: human-defined topics, case-role mapping, and clearer reading of source conversations. That remains a hypothesis to validate, not an established market gap.

The recommended next comparison is a representative case in MailDex and Intella, plus a Nextpoint demo and quote. Use the same archive and expert questions to assess completeness, search usefulness, thread accuracy, reading clarity, relationship handling, and total cost. Establish whether ordinary import, search, and review can operate within the intended no-AI boundary.

The [stakeholder email draft](2026-11-14-product-evaluation-email.md) asks whether existing products meet the need and whether continuing a custom build is worthwhile. No build-versus-buy decision has been recorded.
