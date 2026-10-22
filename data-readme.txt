# Arizona Cardinals Fan Survey 2026: public dataset

**Independent survey by fans, for fans. Not affiliated with the Arizona Cardinals or the NFL.**

- File: `data.csv` on cardinalssurvey.com (same file as `public-dataset.csv`; UTF-8 with BOM, so Excel shows emoji and curly quotes correctly).
- Responses: all **3,057** submitted to the Google Form promoted at cardinalssurvey.com, Oct 19, 2026 through the close on **Thursday, Oct 22, 2026, 9 AM Arizona time**. No response was excluded; possible duplicates are flagged in the report, not removed.
- Columns: the form's original columns in their original order (only the timestamp header is relabeled), plus one appended column, `Last season-ticket year (normalized)` (4-digit year; blank = could not be resolved).
- Timestamps are the full form timestamps (date and time, Arizona time, MST, as in the form export); the first column is labeled `Timestamp (Arizona time, MST)`.

## What this is, and is not
A grassroots online survey, not a scientific poll. Respondents chose to take part (self-selected), no identity verification was required, and results may not be generalized to all Cardinals fans. Use "respondents" or "responses" when describing the data.

## How free text was handled
Free-text answers (the comment question, the "Other" write-ins for "Why did you cancel" and "What could Bidwill say and do", and the "What year did you last have season tickets?" answers) use **exactly the same masking as the companion PDF "Fan Comments: Complete Appendix"**. No answer is removed or replaced as a whole.

- Profanity is masked with asterisks (for example f***). Words respondents already self-censored, such as "f-off", appear as written.
- Slurs are shown as [slur removed]; the rest of the answer appears as written.
- Names of private individuals, email addresses and phone numbers are masked as [name], [email] or [phone]. Public figures and team personnel named by respondents are left as written.
- Identifying details were generalized, limited to seat locations and season-ticket and tenure years: seat locations appear as [section]; exact season-ticket start years are shown as a bracketed period (for example, since [the late 1980s]); stated numbers of years as a season-ticket holder or fan are rounded down to the nearest 5 with a plus sign (for example, 37 years becomes [35+] years). Years respondents became fans (for example, "fan since 1988") were intentionally left as written. Only the detail itself is replaced; every other word is the respondent's.
- Square brackets mark an editor's generalization of an identifying detail.
- Spelling, grammar, capitalization, line breaks and emoji are otherwise unchanged.

Answers carrying at least one mask: 86 comments, 6 other free-text answers.

## Contact / credits
Christopher Maddox (organizer and report author, X @maddox_lglp), with Nathan Kropp (@MrAzSports) and Sandi Van Lieu (@LieuSandi).
