# Project Memory

## 2026-07-20 - Word Duel Terms of Use added

- What was changed: Added a dedicated mobile-friendly Terms of Use page for Word Duel and linked it from the existing privacy policy.
- Why it was changed: Android and iOS production readiness requires a public legal URL, and player-submitted secret words require clear conduct and objectionable-content rules.
- Important files modified: `word-duel/index.html`, `word-duel/terms/index.html`, and `PROJECT_MEMORY.md`.
- Tests or validation performed: Reviewed the page structure, relative links, mobile viewport metadata, and public GitHub Pages path before publishing.
- Known issues or follow-up work: The game still needs an accessible in-app reporting flow and a reviewed moderation process before public online play.

## 2026-09-16 - Word Duel launch policies and deletion guidance completed

- What was changed: Updated the Word Duel privacy policy and Terms to match the lean 1.0 feature set, added public Community Guidelines and account-deletion instructions, documented optional Analytics and Diagnostics, and published explicit match, report, Analytics, and Diagnostics retention periods.
- Why it was changed: The Android and iOS clients now include policy-gated online play, reporting/blocking, account deletion, opt-in analytics, diagnostics, and ads, so public disclosures and support instructions must match the implemented data flow.
- Important files modified: `word-duel/index.html`, `word-duel/terms/index.html`, `word-duel/community/index.html`, `word-duel/delete-account/index.html`, and `PROJECT_MEMORY.md`.
- Tests or validation performed: All Word Duel HTML pages pass `html-validate`; relative policy/deletion links and mobile viewport metadata were checked, and the repositories contain no credentials or private identifiers in these pages.
- Known issues or follow-up work: Publish the commit through GitHub Pages, verify every public URL from Android and iOS, and complete the external deletion rehearsal and store privacy declarations before public release.

## 2026-09-16 - Word Duel age-aware advertising disclosure

- What was changed: Documented the app's 13-17 under-age advertising treatment, confirmed-adult treatment, ad-free unknown/under-13 path, age-band choice processing, and disabled publisher first-party advertising identifier.
- Why it was changed: The production client now distinguishes teen and adult ad requests, so the public policy must describe the behavior used on both Android and iOS.
- Important files modified: `word-duel/index.html` and `PROJECT_MEMORY.md`.
- Tests or validation performed: All Word Duel HTML pages passed `html-validate`; the privacy, terms, community, and deletion URLs each returned HTTP 200 before publication of this revision.
- Known issues or follow-up work: Reverify the disclosure against the final signed SDK privacy reports and completed Google Play/App Store privacy forms before public submission.
