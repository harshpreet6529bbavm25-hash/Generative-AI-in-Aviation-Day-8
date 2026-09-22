# Generative-AI-in-Aviation-Day-8
Day 8 lab exploring AI summary fidelity, claim-by-claim verification, numerical accuracy, omission and invention detection, management-report scaffolding, [VERIFY] placeholders, source limitations, and responsible AI-assisted aviation reporting.
# GenAI Business Portfolio — Day 8

## Workplace Writing II: Summary Fidelity and Report Scaffolding

This repository contains Day 8 of the Generative AI in Aviation lab portfolio.

## Lab Focus

- AI-generated summary writing
- Summary fidelity
- Claim-by-claim verification
- Numerical accuracy
- Omission detection
- Invention detection
- Source limitations
- Management-report scaffolding
- [VERIFY] placeholders
- Separating facts from interpretation
- Separating recommendations from source facts
- Baggage-complaint summary
- Peer review
- Human verification

---

# Repository Structure

genai-business-portfolio/
│
└── day-08-summary-fidelity/
    │
    └── summary-fidelity-and-report-scaffolding.md

---

# 1. Lab Objective

The objective of this lab is to use Generative AI to create concise aviation summaries while preserving the meaning, numerical information, limitations and important facts of the original source.

The AI-generated summary must not:

- Invent statistics
- Add recommendations
- Create financial information
- Create passenger-satisfaction scores
- Add airport comparisons
- Invent staffing problems
- Claim successful outcomes that were not measured
- Convert assumptions into facts

---

# 2. Initial Summary Prompt

Summarise the supplied airport passenger-service report in no more than 100 words.

Retain all important figures, clearly distinguish complaints from positive feedback and do not add recommendations, comparisons, financial information or conclusions that are not stated in the source.

---

# 3. AI Summary

During August, an airport customer-service team reviewed 120 passenger comments. Forty-five concerned long security-screening queues, 30 concerned unclear directional signs, 20 concerned baggage delays, and 15 concerned limited seating near departure gates. Ten comments praised staff helpfulness. Airport management introduced two temporary information desks near the security area for a two-week trial. The report did not measure overall passenger satisfaction, compare the airport with other airports, or calculate financial impact. The effect of the information-desk trial had not been measured when the report was prepared.

---

# 4. Why the Summary Is Faithful

| Check | Result |
|---|---|
| Total comments | 120 — retained |
| Security-queue complaints | 45 — retained |
| Directional-sign complaints | 30 — retained |
| Baggage-delay complaints | 20 — retained |
| Seating complaints | 15 — retained |
| Positive staff comments | 10 — retained |
| Information desks | 2 — retained |
| Trial duration | 2 weeks — retained |
| Overall satisfaction | Correctly stated as not measured |
| Airport comparison | Correctly stated as not conducted |
| Financial impact | Correctly stated as not calculated |
| Trial outcome | Correctly stated as not measured |
| Recommendations | None added |
| Unsupported conclusions | None added |

---

# 5. Claim-by-Claim Fidelity Check

| Claim | Present in Source? | Support | Correction |
|---|---|---|---|
| 120 passenger comments were reviewed | Yes | Fully supported | None |
| 45 comments concerned security queues | Yes | Fully supported | None |
| 30 comments concerned directional signs | Yes | Fully supported | None |
| 20 comments concerned baggage delays | Yes | Fully supported | None |
| 15 comments concerned limited seating | Yes | Fully supported | None |
| 10 comments praised staff helpfulness | Yes | Fully supported | None |
| Two temporary information desks were introduced | Yes | Fully supported | None |
| Desks were introduced for a two-week trial | Yes | Fully supported | None |
| Overall satisfaction was not measured | Yes | Fully supported | None |
| Airport comparison was not conducted | Yes | Fully supported | None |
| Financial impact was not calculated | Yes | Fully supported | None |
| Trial effect had not been measured | Yes | Fully supported | None |

## Overall Finding

The AI summary is fully faithful to the supplied source.

There are no unsupported claims, invented statistics or factual distortions.

---

# 6. Numerical Accuracy Check

| Information | Original Source | AI Summary | Match |
|---|---:|---:|---|
| Total passenger comments | 120 | 120 | Yes |
| Security-queue complaints | 45 | 45 | Yes |
| Directional-sign complaints | 30 | 30 | Yes |
| Baggage-delay complaints | 20 | 20 | Yes |
| Seating complaints | 15 | 15 | Yes |
| Positive staff comments | 10 | 10 | Yes |
| Temporary information desks | 2 | 2 | Yes |
| Trial duration | 2 weeks | 2 weeks | Yes |

## Numerical Accuracy Finding

All 8 numerical items match the original source.

No figures were:

- Altered
- Omitted
- Invented

---

# 7. Omission Check

## Important Information Retained

The summary retained:

- Total number of comments
- All four complaint categories
- Exact complaint figures
- Positive staff feedback
- Temporary information desks
- Trial duration
- Unmeasured trial outcome
- Lack of passenger-satisfaction measurement

## Omission Finding

No important information identified in the lab was omitted.

---

# 8. Invention Check

The summary did NOT invent:

- Overall passenger-satisfaction percentage
- Comparison with another airport
- Financial loss
- Successful information-desk outcome
- Recommendation to hire more staff
- Claim that security was understaffed
- Claim that passenger satisfaction declined

## Important Principle

Long security queues do not automatically prove that security was understaffed.

Similarly, introducing information desks does not prove that the intervention was successful.

The source states that the effect of the trial had not yet been measured.

---

# 9. Management Report Scaffold

# Airport Passenger-Service Feedback Report — August

## 1. Executive Summary

During August, the airport customer-service team reviewed 120 passenger comments.

The main complaint areas were:

- Long security-screening queues — 45 comments
- Unclear directional signs — 30 comments
- Baggage delays — 20 comments
- Limited seating near departure gates — 15 comments

Ten comments praised staff helpfulness.

Airport management introduced two temporary information desks near the security area for a two-week trial.

The effect of the trial had not been measured when the report was prepared.

---

## 2. Purpose of the Report

The purpose of this report is to summarise passenger-service feedback reviewed during August and document the customer-service action introduced by airport management.

---

## 3. Source and Scope

The report is based on 120 passenger comments reviewed by the airport customer-service team during August.

---

## 4. Key Findings

| Complaint / Feedback Category | Number of Comments |
|---|---:|
| Long security-screening queues | 45 |
| Unclear directional signs | 30 |
| Baggage delays | 20 |
| Limited seating near departure gates | 15 |
| Positive comments about staff helpfulness | 10 |
| **Total** | **120** |

---

## 5. Positive Feedback

Ten comments praised staff helpfulness.

---

## 6. Actions Already Taken

Airport management introduced two temporary information desks near the security area for a two-week trial.

---

## 7. Limitations

The source report:

- Did not measure overall passenger satisfaction.
- Did not compare the airport with other airports.
- Did not calculate financial impact.
- Had not measured the effect of the temporary information-desk trial when the report was prepared.

---

# 8. Recommendations

[VERIFY — Recommendations require additional operational evidence and management review.]

No recommendation should be presented as an established fact because the supplied source does not provide enough evidence to determine what action should be taken.

---

# 9. Information Requiring Verification

- Trial outcome: `[VERIFY AFTER TRIAL EVALUATION]`
- Passenger-satisfaction score: `[VERIFY — NOT MEASURED IN SOURCE]`
- Financial impact: `[VERIFY WITH FINANCE DEPARTMENT]`
- Staffing levels: `[VERIFY WITH OPERATIONS — NOT PROVIDED IN SOURCE]`
- Management approval for future recommendation: `[VERIFY APPROVAL STATUS]`

---

# 10. Conclusion

The August passenger comments identified four complaint categories and included positive feedback about staff helpfulness.

Airport management responded by introducing two temporary information desks near security for a two-week trial.

However, the source does not establish:

- Trial effectiveness
- Overall passenger satisfaction
- Comparative airport performance
- Financial impact

`[VERIFY AFTER TRIAL EVALUATION]`

---

# 11. [VERIFY] Placeholder Table

| Report Section | Information Required | Available in Source? | Verification Placeholder |
|---|---|---|---|
| Executive Summary | 120 comments, complaint categories, 10 positive comments and 2 information desks | Yes | No placeholder required |
| Key Findings | Complaint figures and categories | Yes | No placeholder required |
| Actions Taken | Two information desks and two-week trial | Yes | No placeholder required |
| Recommendations | Evidence-based future actions | No | `[VERIFY WITH OPERATIONS / MANAGEMENT]` |
| Financial Impact | Actual financial effect | No | `[VERIFY WITH FINANCE DEPARTMENT]` |
| Trial Outcome | Effectiveness of information desks | No | `[VERIFY AFTER TRIAL EVALUATION]` |
| Conclusion | Final outcome of trial | No | `[VERIFY AFTER TRIAL EVALUATION]` |

---

# 12. Separate Facts From Interpretation

| Item | Classification | Explanation |
|---|---|---|
| The report reviewed 120 comments | Verified source fact | Explicitly stated in the source |
| Executive Summary | Report structure | Section of the report |
| Passenger satisfaction has declined | Unsupported interpretation | Satisfaction was not measured |
| Install more directional signs | Recommendation | Source reports unclear signs but does not recommend this action |
| Two temporary information desks were introduced | Verified source fact | Explicitly stated |
| The trial was successful | Unsupported conclusion | Trial effect had not been measured |
| Financial Impact | Report structure | Can be a report section even without a financial figure |
| `[VERIFY AFTER TRIAL EVALUATION]` | Information requiring verification | Evidence is not currently available |

---

# 13. Important Fidelity Rule

Do not write:

> "The information desks successfully reduced passenger complaints."

This would be an unsupported conclusion.

The source only establishes that:

- Two information desks were introduced.
- They were introduced for a two-week trial.
- Their effect had not yet been measured.

---

# 14. Baggage-Complaint Summary

The second source reviewed 80 baggage-related complaints.

The five categories were:

- 32 delayed baggage
- 18 damaged baggage
- 14 tracking-information difficulties
- 10 communication complaints
- 6 baggage-delivery-arrangement complaints

The source specifically did not report:

- Permanent baggage loss
- Compensation amounts
- Delivery timelines
- Customer-satisfaction scores

---

# 15. Realistic AI Baggage Summary

During one month, an airline reviewed 80 baggage-related complaints. Thirty-two concerned delayed baggage, 18 concerned damaged baggage, 14 concerned difficulty obtaining tracking information, 10 concerned communication from service staff and six concerned baggage-delivery arrangements. The document did not state that any baggage was permanently lost and did not report compensation amounts, delivery timelines or customer-satisfaction scores. The airline planned to review its baggage-tracking communication, but no new system had been approved.

---

# 16. Baggage Numerical Check

| Information | Source | AI Summary | Match |
|---|---:|---:|---|
| Total complaints | 80 | 80 | Yes |
| Delayed baggage | 32 | 32 | Yes |
| Damaged baggage | 18 | 18 | Yes |
| Tracking information | 14 | 14 | Yes |
| Staff communication | 10 | 10 | Yes |
| Delivery arrangements | 6 | 6 | Yes |

---

# 17. Baggage Fidelity Rules

The following distinctions must be maintained:

- Delayed baggage ≠ permanently lost baggage
- Do not invent compensation amounts.
- Do not invent delivery timelines.
- Do not invent customer-satisfaction scores.
- Do not claim that a new tracking system was approved.
- Do not present a planned review as an implemented solution.

---

# 18. My Own Summary Prompt

Summarise the supplied aviation document for a BBA Aviation Management student and management audience.

Keep the response between 100 and 120 words.

Retain all important figures, operational facts, actions taken, positive feedback and source limitations.

Clearly distinguish complaints, positive feedback and management actions.

Do not invent:

- Passenger-satisfaction scores
- Financial impacts
- Staffing levels
- Performance results
- Recommendations
- Approvals
- Outcomes

If information required for a management conclusion is not available, clearly mark it as `[VERIFY]`.

Present the response in a concise management-report format while preserving the meaning of the original source.

---

# 19. Peer Review

| Review Question | Result | Evidence / Suggested Correction |
|---|---|---|
| Does the summary preserve source meaning? | Yes | All major source claims are preserved. |
| Are all important figures correct? | Yes | 120, 45, 30, 20, 15, 10, 2 and two weeks match the source. |
| Has critical information been omitted? | No | Major limitations and unmeasured trial outcome are included. |
| Has unsupported information been added? | No | No financial, satisfaction, staffing or outcome claims were invented. |
| Are source limitations included? | Yes | Satisfaction, comparison, financial impact and trial limitations are stated. |
| Are `[VERIFY]` placeholders used correctly? | Yes | Used where additional evidence is required. |
| Is the summary concise and readable? | Yes | Suitable for a management audience. |
| Is the summary suitable for the intended audience? | Yes | Provides factual information without overstating conclusions. |

---

# 20. Reflection

## 1. What is summary fidelity?

Summary fidelity means preserving the meaning and important information of the original source without adding unsupported claims, changing figures or creating conclusions that the source does not establish.

## 2. Why is claim-by-claim verification important?

It allows each statement in an AI-generated summary to be checked directly against the original source.

## 3. Why must numerical information be checked?

AI-generated summaries can potentially change, omit or invent figures. Numerical comparison confirms that the summary matches the source.

## 4. What is an omission?

An omission occurs when important information from the original source is missing from the AI summary.

## 5. What is an invention?

An invention occurs when the AI adds information, statistics, conclusions or claims that are not supported by the source.

## 6. Why should source limitations be preserved?

Source limitations prevent the summary from overstating what the evidence proves.

For example, the source did not measure:

- Overall passenger satisfaction
- Financial impact
- Airport comparison
- Information-desk trial effectiveness

## 7. Why is `[VERIFY]` useful?

`[VERIFY]` identifies information that requires additional evidence or confirmation before the report is finalised.

## 8. Why should recommendations be separated from facts?

A recommendation requires evidence and management judgement. It should not be presented as if it were an established fact from the source.

## 9. Why does delayed baggage not mean permanently lost baggage?

The source specifically reports delayed baggage but does not establish permanent loss.

## 10. Why should AI-generated management reports receive human review?

Human review is necessary to verify:

- Facts
- Figures
- Source meaning
- Limitations
- Recommendations
- Operational information
- Management conclusions

---

# 21. AI Usage Declaration

ChatGPT and/or Google Gemini were used to create and refine initial summaries.

The outputs were independently reviewed against the supplied source for:

- Source fidelity
- Numerical accuracy
- Omissions
- Inventions
- Unsupported conclusions
- Source limitations

---

# 22. GitHub Upload Checklist

Before uploading, confirm:

- [x] Summary is based on the supplied source
- [x] Important figures are retained
- [x] Complaint categories are preserved
- [x] Positive feedback is distinguished
- [x] Source limitations are included
- [x] No unsupported recommendations are presented as facts
- [x] No financial information is invented
- [x] No passenger-satisfaction score is invented
- [x] No staffing claim is invented
- [x] No successful trial outcome is claimed
- [x] `[VERIFY]` placeholders are used where required
- [x] Numerical accuracy has been checked
- [x] Claims have been checked against the source
- [x] Peer review has been completed

---

# 23. Submission Details

Repository:

genai-business-portfolio

Folder:

day-08-summary-fidelity

File:

summary-fidelity-and-report-scaffolding.md

Suggested commit message:

Add Day 8 Lab 8 - Summary Fidelity and Report Scaffolding

---

# 24. Final Takeaway

Reliable AI-assisted aviation reporting requires source fidelity.

The AI should:

1. Preserve important facts.
2. Preserve numerical information.
3. Distinguish complaints from positive feedback.
4. Preserve source limitations.
5. Avoid unsupported conclusions.
6. Avoid invented recommendations.
7. Avoid invented statistics.
8. Separate facts from interpretation.
9. Use `[VERIFY]` when evidence is missing.
10. Receive human review before the report is finalised.

The key principle is:

**Do not make the source say more than it actually says.**
