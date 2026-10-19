# AI-Powered Meeting Minutes and Action Item Generator

## Meeting details

| Field | Details |
|---|---|
| Meeting | Website Launch Readiness Review |
| Date | 14 October 2026 |
| Time | 10:00–10:45 AM |
| Chair | Maya Patel, Project Manager |
| Attendees | Maya Patel (Project Manager), Leo Chen (Engineering Lead), Priya Nair (Marketing Lead), Omar Hassan (QA Lead), Nina Brooks (Support Lead) |
| Purpose | Review launch readiness, resolve open issues, and assign work before the planned launch. |

## A. Sample meeting transcript

1. **Maya:** Thanks, everyone. The purpose today is to review whether the new website is ready for its 26 October launch.
2. **Leo:** The core pages and checkout flow are implemented, and the latest build is on staging.
3. **Omar:** QA has tested the main desktop flows, but mobile checkout still has two open defects.
4. **Leo:** One defect is a layout shift on smaller screens; the other is that the address field sometimes clears after an error.
5. **Maya:** Can engineering fix both before the end of this week?
6. **Leo:** Yes. I will fix the layout shift by 16 October and the address-field issue by 19 October.
7. **Omar:** I will rerun mobile checkout regression tests on 20 October, after both fixes are available.
8. **Priya:** The launch campaign copy is ready, but the final product screenshots are not.
9. **Maya:** Who can provide those screenshots, and by when?
10. **Leo:** I can provide the approved desktop and mobile screenshots to Priya by 16 October.
11. **Priya:** That works. I will schedule the email and social campaign by 21 October, assuming the screenshots arrive on time.
12. **Nina:** Support needs a short FAQ covering order tracking, refunds, and account login before launch.
13. **Maya:** Nina, please draft that FAQ by 19 October.
14. **Nina:** I can do that and share it with the group for review.
15. **Omar:** We also need to decide whether to launch if a low-priority visual issue remains.
16. **Leo:** The only known visual issue is a slightly uneven spacing on the blog page; it does not affect checkout or accessibility.
17. **Maya:** Let’s agree that launch can proceed with low-priority visual issues only if QA confirms there are no critical or high-priority defects.
18. **Omar:** I support that condition and will include severity status in the final QA report.
19. **Priya:** We need a final go/no-go review after QA is complete.
20. **Maya:** Agreed. We will hold the go/no-go review on 22 October at 2:00 PM.
21. **Omar:** I will send the final QA report by noon on 22 October so it is ready for that review.
22. **Nina:** I will also bring the FAQ and support staffing plan to the review.
23. **Maya:** Nina, please finish the support staffing plan by 21 October.
24. **Nina:** Understood; I will include coverage for launch day and the first two days after launch.
25. **Leo:** Engineering can monitor the site on launch day, 26 October, and resolve any production issues.
26. **Maya:** Please post a short status update in the launch channel by 4:00 PM on launch day.
27. **Leo:** I will post that update by 4:00 PM on 26 October.
28. **Priya:** I will keep the campaign scheduled but will wait for the go/no-go decision before publishing launch-day posts.
29. **Maya:** That is correct. The launch remains planned for 26 October, subject to the 22 October go/no-go review and the QA condition we agreed.
30. **Maya:** Thanks, everyone. I will circulate these minutes today.

## B. Summarization and extraction prompt

> You are a careful meeting-minutes assistant. Use only the transcript provided; do not infer unstated facts, owners, dates, or decisions. First write a concise, neutral summary of the discussion. Then extract each explicit decision and each action item. For every action, include the responsible person and deadline exactly as stated; write “Not specified” if either is absent. Distinguish a firm decision from a proposal or a conditional plan. Preserve conditions that affect decisions. Finally, verify each summary point, decision, and action against the transcript and cite the relevant statement number(s). Return the minutes in clear tables. Do not treat the planned launch date as unconditional: retain any stated go/no-go condition.

## C. Meeting summary

The team reviewed readiness for the website launch planned for 26 October. The core pages and checkout flow are on staging, while two mobile checkout defects remain. Engineering committed to fixes by 16 and 19 October, with QA regression testing on 20 October. Marketing is waiting on final screenshots to schedule the campaign, and Support will prepare a customer FAQ and launch coverage plan. The team agreed that low-priority visual issues may remain only if QA confirms there are no critical or high-priority defects. A go/no-go review is scheduled for 22 October at 2:00 PM, after the final QA report is due. The launch is still planned for 26 October, conditional on that review and QA criterion.

## D. Key decisions

| # | Decision | Conditions / notes | Transcript reference |
|---|---|---|---|
| D1 | Launch may proceed with low-priority visual issues remaining. | QA must confirm there are no critical or high-priority defects. | 16–18 |
| D2 | Hold a final go/no-go review on 22 October at 2:00 PM. | Review follows the final QA report, due by noon that day. | 19–21 |
| D3 | Keep the website launch planned for 26 October. | Launch is subject to the 22 October go/no-go review and the QA condition in D1. | 1, 17–18, 29 |
| D4 | Publish launch-day campaign posts only after the go/no-go decision. | Campaign scheduling can proceed beforehand. | 28–29 |

## E. Action items

| ID | Action item | Responsible person | Deadline | Transcript reference |
|---|---|---|---|---|
| A1 | Fix the mobile layout shift defect. | Leo Chen | 16 October 2026 | 4–6 |
| A2 | Fix the mobile address field clearing defect. | Leo Chen | 19 October 2026 | 4–6 |
| A3 | Rerun mobile checkout regression tests after the fixes. | Omar Hassan | 20 October 2026 | 7 |
| A4 | Provide approved desktop and mobile product screenshots to Priya. | Leo Chen | 16 October 2026 | 8–10 |
| A5 | Schedule the email and social campaign, contingent on receiving screenshots. | Priya Nair | 21 October 2026 | 10–11 |
| A6 | Draft and share the FAQ covering order tracking, refunds, and account login. | Nina Brooks | 19 October 2026 | 12–14 |
| A7 | Include severity status in the final QA report. | Omar Hassan | 22 October 2026, by noon | 18–21 |
| A8 | Bring the FAQ and support staffing plan to the go/no-go review. | Nina Brooks | 22 October 2026, 2:00 PM review | 19–22 |
| A9 | Complete the support staffing plan, including launch day and the first two days after launch. | Nina Brooks | 21 October 2026 | 22–24 |
| A10 | Monitor the site and resolve production issues on launch day. | Leo Chen / Engineering | 26 October 2026 | 25 |
| A11 | Post a status update in the launch channel. | Leo Chen | 26 October 2026, by 4:00 PM | 26–27 |
| A12 | Circulate the meeting minutes. | Maya Patel | 14 October 2026 (today) | 30 |

## F. Accuracy verification

| Check | Result | Evidence |
|---|---|---|
| Transcript length | Pass: 30 numbered statements, exceeding the 25-statement requirement. | Transcript statements 1–30 |
| Summary reflects the main discussion | Pass: readiness, two defects, campaign assets, support preparation, QA gate, review time, and planned launch are represented. | 1–29 |
| Decisions are explicit and conditions retained | Pass: the launch gate, review time, conditional launch, and campaign publishing condition are captured without turning plans into unconditional approval. | 17–18, 20, 28–29 |
| Owners and dates match the transcript | Pass: each listed owner and deadline is tied to the corresponding commitment. | References in action table |
| Relative deadline handled transparently | “Today” for circulating minutes is resolved to 14 October 2026 using the meeting date given in the report. | 30 and meeting details |
| No unassigned due dates invented | Pass: the go/no-go review is recorded as the deadline for bringing materials because Nina explicitly said she would bring them to that review. | 19–22 |

### Items to monitor

- The 26 October launch is planned, not finally approved; the 22 October go/no-go review remains the approval point.
- Priya’s campaign scheduling depends on receiving screenshots by 16 October.
- Low-priority visual defects are acceptable only if QA confirms there are no critical or high-priority defects.
