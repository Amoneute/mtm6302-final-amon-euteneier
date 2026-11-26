# Client Communication Log

Project: StudentWallet — Student Budget Tracker
Developer: Amon Euteneier
Client: Katok

## Contact 1: Introduction and confirmation

- **Date and time:** November 26, 2026, 7:40 a.m.
- **Method:** Brightspace email
- **Question/message:** Introduced myself, confirmed my understanding of the brief, and asked the questions below.
- **Response:** None as of November 26, 2026 at [time].

### Questions asked

1. **Monthly totals:** Should the dashboard total all transactions, or only the current calendar month?
2. **History order:** Should the history show newest transactions first?
3. **No budget set:** If no budget has been saved, should the dashboard show "No budget set" instead of a negative remaining budget when expenses exist?
4. **Income category:** If a transaction is changed to Income, can its category be set to Other automatically?

## Deadlines

- **24-hour clarification window ends:** November 27, 2026, 7:40 a.m.
- **48-hour instructor notification deadline:** November 28, 2026, 7:40 a.m., if there has been no response at all.

## Decisions and assumptions

The five required features (F1–F5) remain unchanged. Optional features will only be considered after all required functionality is complete and tested.

| ID | Decision | Reason | Status |
|----|----------|--------|--------|
| D1 | Include all transactions in all dashboard totals | Matches the client's worked example; month filtering is optional | Pending client confirmation |
| D2 | Show newest transactions first | Latest activity is easiest to find | Pending client confirmation |
| D3 | Income uses the category Other | Stated in the brief | Confirmed by brief |
| D4 | Save data in Local Storage under `studentWalletData` | Brief requires same-browser persistence and no sync | Developer decision |
| D5 | A budget of $0 means "not set" | Avoids a misleading "over budget" message | Pending client confirmation |

If there is no response by November 27, 2026 at 7:40 a.m., I will proceed with D1, D2 and D5 as documented and update this log.

## Instructor notification

If there is no response at all by November 28, 2026 at 7:40 a.m., I will contact the instructor with this log and the outstanding questions.

## Follow-up log

- [Date/time]: [Follow-up sent, or response received and decision made]