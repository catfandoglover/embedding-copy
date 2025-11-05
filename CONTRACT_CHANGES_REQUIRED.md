# Contract Changes Required - Based on Meeting Nov 5, 2025

## Summary of Changes from Meeting Discussion

Based on the meeting between Alex Jakubowski (Lightning) and Max (representing Dov Seidman), the following changes need to be made to the consulting agreement:

---

## CHANGE 1: Section 1 (INTRODUCTION)
**Issue:** Remove language allowing Lightning to unilaterally change agreement

**Current Text (to be removed):**
```
This Agreement can be updated from time to time in accordance with Section 15.1. Client is responsible for regularly reviewing the most recent version of this Agreement, which is published at: https://alexandria.wiki/terms-of-use-alexandria. When Lightning changes this Agreement, the Last Modified date above will be updated.
```

**Reason:** This language was intended for end-user license agreements, not the consulting agreement. Alex agreed to remove it as it doesn't belong in this context.

---

## CHANGE 2: Section 4 (SERVICES)
**Issue:** Add flexibility clause about Statement of Work structure

**Location:** Add new subsection after Section 4.5

**New Text to Add:**
```
4.6. Statement of Work Flexibility. The structure, format, and deliverables outlined in any Statement of Work represent one potential approach to achieving the project objectives. Lightning and Client acknowledge that the actual implementation may be adapted and reconstructed based on early project conversations, Client feedback, and evolving project requirements, provided both parties agree to such modifications in writing.
```

**Reason:** Max asked for language indicating the SOW structure is an example and open to interpretation and reconstruction based on early conversations.

---

## CHANGE 3: Section 4.3 (Platform License Grant)
**Issue:** Clarify continued access to deliverables after SOW ends

**Current Text:**
```
Platform License Grant. Subject to the terms of this Agreement and payment of applicable fees, Lightning grants to Client a limited, non-exclusive, non-transferable, revocable license to access and use the Lightning Platform solely for the purpose of receiving the Services and operating the Ask Howie prototype during the Term.
```

**Revised Text:**
```
4.3. Platform License Grant. Subject to the terms of this Agreement and payment of applicable fees, Lightning grants to Client a limited, non-exclusive, non-transferable license to access and use the Lightning Platform solely for the purpose of receiving the Services and operating the Ask Howie prototype.

    a. Deliverable Access. Upon completion and full payment for any Statement of Work, Client shall retain perpetual access to the specific deliverables and functionalities developed under that Statement of Work, even if no subsequent Statement of Work is executed or this Agreement terminates. Such continued access includes the right to use the delivered prototype or system in its delivered state without additional maintenance obligations from Lightning.

    b. Platform Continuity. Client's continued use of delivered systems may be subject to pass-through costs (such as third-party AI provider costs) at Lightning's actual cost, if applicable. Lightning shall not be obligated to provide maintenance, updates, or support for delivered systems beyond the term of the applicable Statement of Work unless separately agreed.

    c. Business Discontinuation. In the event Lightning ceases operations or discontinues the Lightning Platform, Lightning agrees to use commercially reasonable efforts to transfer or assign to Client the necessary rights and access to continue operating the delivered Ask Howie prototype and associated systems developed under this Agreement, or to provide Client with a reasonable transition period and technical documentation to enable Client to maintain the system independently or through a third party.
```

**Reason:** Max's concern that if they don't do a second SOW, they lose access to what was built in the first SOW. Alex agreed they should own the deliverable from a specific SOW and not be perpetually dependent on Lightning's platform. Also addresses the scenario where Lightning shuts down.

---

## CHANGE 4: Section 6.5 (Feedback)
**Issue:** Add restriction on quoting client feedback

**Current Text:**
```
5. Feedback. To the extent Client provides any feedback or suggestions to Lightning regarding the Services, such feedback shall be deemed non-confidential, and Lightning shall be free to use and exploit such feedback without restriction or obligation.
```

**Revised Text:**
```
5. Feedback. To the extent Client provides any feedback or suggestions to Lightning regarding the Services, processes, or platform functionality, such feedback shall be deemed non-confidential with respect to process improvements and general insights, and Lightning shall be free to use such insights to improve its general methodologies and future client services without restriction or obligation. However, Lightning shall not quote, publish, or otherwise use Client's written feedback as testimonials, endorsements, or attributed statements in any marketing, promotional, or public-facing materials without Client's prior written consent.
```

**Reason:** Max was concerned the language allowed Lightning to post client feedback on their website. Alex agreed to add language that written feedback won't be quoted without prior approval, while preserving Lightning's right to use process insights for improvement.

---

## CHANGE 5: Section 14.1 (Entire Agreement and Amendments)
**Issue:** Remove unilateral amendment language

**Current Text (paragraph to be removed):**
```
Lightning may change any part of this Agreement (including any terms or documents incorporated by reference in this Agreement) at any time by posting the revised terms on Lightning website. It is important for Client to review this Agreement before using the Services and from time to time. The updated Agreement will be effective as of the time of posting, and Client's continued use of the Services after any such changes are effective will constitute Client's consent to such changes.
```

**Revised Section 14.1:**
```
1. Entire Agreement and Amendments. This Agreement and the Statement of Work (including the addendums, amendments, or attachments) constitute the entire agreement of the Parties relating to the subject matter hereof and supersedes any and all prior written and oral agreements or understandings relating to such subject matter. No amendment or modification of this Agreement will be effective unless set forth in the Statement of Work, or as amendments, modifications or addendums to this Agreement and must be in writing and signed by each party's authorized representatives or, as appropriate, agreed through electronic means provided by Lightning.
```

**Reason:** Alex confirmed this language about unilateral changes doesn't belong in the consulting agreement - it was carry-over from end-user terms. Both this and the Introduction reference should be removed.

---

## CHANGE 6: Acceptance Criteria (Statement of Work - Exhibit A)
**Issue:** Make acceptance criteria more flexible and principle-based

**Current Text:**
```
Acceptance Criteria

Each milestone deliverable will be considered accepted upon Client's written approval or 10 business days after delivery if no written feedback is provided.
```

**Revised Text:**
```
Acceptance Criteria

Each milestone deliverable will be considered accepted upon Client's written approval. If Client requires additional time to review deliverables or is temporarily unavailable, Client shall provide written acknowledgment to Lightning indicating the expected timeframe for full review and feedback. Lightning will make good faith efforts to accommodate reasonable review periods.

Deliverables shall be deemed accepted if Client does not provide substantive written feedback within twenty (20) business days of delivery, provided that:
(a) Lightning has made good faith efforts to ensure Client received and had opportunity to review the deliverable;
(b) Client has not provided notice of being unavailable or needing additional review time; and
(c) The delay in feedback is not due to any deficiency in the deliverable or failure by Lightning to meet the specifications outlined in the Statement of Work.

This provision is intended to prevent indefinite delay while respecting both parties' good faith obligations. Simple acknowledgment of receipt (such as "received, will review" or "on vacation, will review upon return") shall constitute written feedback sufficient to pause the acceptance timeline.
```

**Reason:** Max felt the 10-day rule was too rigid ("what if we're on vacation for 10 days"). Alex agreed it's meant as an anti-ghosting provision and should focus on good faith effort and reasonable timeframes rather than strict calendar days. The new language extends to 20 business days but adds flexibility for acknowledgment and good faith.

---

## Notes for Implementation

1. These changes should be incorporated into the source document
2. The PDF should be regenerated with "Last Modified: [New Date]" at the top
3. Both parties should initial or re-sign if required by your document control procedures
4. The changes reflect the collaborative spirit discussed in the meeting where Alex repeatedly said "we would never do that obviously, but I can add language to clarify"

---

## Meeting Context

- Meeting Date: November 5, 2025
- Participants: Alex Jakubowski (Lightning), Max (representing Dov Seidman)
- Purpose: Review and discuss concerns with the consulting agreement before finalizing
- Outcome: Alex agreed to all requested changes and will provide track changes version for review
