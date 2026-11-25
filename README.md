# Verified AI certification facts

Exam facts for AI and agentic-AI certifications, each read from the vendor's own page and
dated. Where a vendor does not publish a figure, this says **not published** rather than
repeating a number that circulates online.

| Exam | Vendor | Level | Price | Questions | Minutes | Passing score | Valid for | Source (checked) |
|---|---|---|---|---|---|---|---|---|
| **NCP-AAI** NVIDIA-Certified Professional: Agentic AI | NVIDIA | Professional | $200 | 60–70 | 120 | not published | Two years from issuance | [vendor page](https://www.nvidia.com/en-us/learn/certification/agentic-ai-professional/) (2026-11-24), retakes: [certification FAQ](https://www.nvidia.com/en-us/learn/certification/) (2026-11-24) |
| **AI-103** Microsoft Certified: Azure AI Apps and Agents Developer Associate | Microsoft | Associate | $165 typical for Associate and Expert exams, priced by region ([exam FAQ](https://learn.microsoft.com/en-us/credentials/certifications/frequently-asked-questions), 2026-11-24) | not published | 120 | 700 on a 1000-point scale (not a percentage) | One year | [vendor page](https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-103/) (2026-10-02) |
| **CY0-001** CompTIA SecAI+ | CompTIA | Intermediate | not published | Maximum of 60 | 60 | 600 on a 100–900 scale (not a percentage) | not published | [vendor page](https://www.comptia.org/en/certifications/secai/) (2026-11-12) |
| **AI-901** Microsoft Certified: Azure AI Fundamentals | Microsoft | Fundamentals | not published | not published | not published | 700 on a 1000-point scale (not a percentage) | Does not expire | [vendor page](https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-901/) (2026-10-04) |
| **GH-600** GitHub Certified: Agentic AI Developer | GitHub | Intermediate | not published | not published | 120 | 700 on a 1000-point scale (not a percentage) | Two years (GitHub-wide policy) | [vendor page](https://learn.microsoft.com/en-us/credentials/certifications/agentic-ai-developer/), validity: [GitHub policy page](https://learn.microsoft.com/en-us/credentials/certifications/github-copilot/) (2026-11-12), Microsoft Learn access: [exam experience page](https://learn.microsoft.com/en-us/credentials/support/exam-duration-exam-experience) (2026-11-24) |
| **SY0-801** CompTIA Security+ (V8) | CompTIA | Intermediate | not published | Maximum of 90 | 90 | 750 on a 100–900 scale (not a percentage) | not published | [vendor page](https://www.comptia.org/en-us/certifications/security/v8/) (2026-11-24), recommended version and V7 retirement: [Security+ page](https://www.comptia.org/en-us/certifications/security/) (2026-11-24), recommended experience and V8 launch date: [V8 page](https://www.comptia.org/en-us/certifications/security/v8/) (2026-11-25), SY0-701 code and retirement: [V7 page](https://www.comptia.org/en-us/certifications/security/v7/) (2026-11-25) |

## Why this exists

Prep sites repeat each other, and wrong figures spread: NCP-AAI's pass mark is quoted as
"720/1000" and "70%" (NVIDIA publishes neither), AI-103's duration as 100 minutes (it is
120; 100 was AI-102). Every row here links the vendor pages it came from.

## How it stays current

The figures are generated from the data behind
[examifyr.com/ai-certifications](https://www.examifyr.com/ai-certifications). A weekly job
re-reads the vendor sources and flags any change to a fact-bearing sentence; the vendor
page is checked again before this table changes.

Corrections are welcome: open an issue with the vendor URL that shows the right figure.

- `facts.json`: the same data, machine-readable. `policy_source` is set when a figure (so far
  only GH-600's validity) comes from a vendor-wide policy page rather than the exam's own page.
  `other_sources` lists any further vendor page a row draws on, and `price_note` says what a
  price is when it is not the exam page's own figure.
- Maintained by [Examifyr](https://www.examifyr.com), free readiness tests for these exams.

## Status (as of 2026-11-25)

- 6 exams. Published 2026-10-17.
- Every figure re-checked against the live examifyr.com data the day it was published;
  the SecAI+ and Security+ V8 rows were re-read from CompTIA's pages on 2026-10-17.
- 2026-10-26: GH-600's exam page no longer states validity, so the two-year figure is now
  attributed to GitHub's certification policy, still published on the GH-300 page.
- 2026-11-24: AI-103's $165 is now attributed to Microsoft's exam FAQ as the typical
  associate price (the exam page prints no figure), and NCP-AAI renewal no longer states a
  retake price. Security+ V8 now shows CompTIA's recommended experience and that CompTIA
  calls it the recommended version. GH-600's note about Microsoft Learn access is now
  attributed to Microsoft's exam-experience page.
- 2026-11-25: Security+ rows now say which page backs what: recommended experience and the
  V8 launch date are on CompTIA's V8 page, and the SY0-701 code is on its V7 page.
  AI-103's price wording now matches Microsoft's exam FAQ as examifyr cites it: Associate
  and Expert exams typically cost US$165.

License: CC BY 4.0. Cite the vendor page, not this repo, for anything official.
