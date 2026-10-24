---
name: inbox-triage-text
description: Checks the student's school email on a schedule and texts only the few messages that truly need a reply or action, using fixed rules to ignore promos and no-reply noise. Use when the student's inbox is overwhelming or they keep missing important emails.
---

# Inbox Triage Text

This Skill uses only Cubbie's built-in capabilities. It has no scripts.

The goal is a short text with the few emails that actually need the student, so the important one never gets buried. It is not a summary of the whole inbox. The rules below are fixed, so the student does not have to set anything up.

## When to use

- "My inbox is a mess, what actually needs a reply?"
- "I keep missing emails from my professors and recruiters."
- "Text me every night if anything important came in."

Do not use it to write an email from scratch, to find one specific old email, or to clean up, archive or delete anything.

## Steps

1. Search the student's synced Gmail for email that came in since the last check. On the first run, look back 48 hours.
   If Google is not connected, tell the student, offer to connect it, and stop.
2. Read each message (sender, subject and the body) and judge it with the rules below. Judge the content, not just the sender or the subject line.
3. For any email about a grade being released or posted, look up the actual grade in Canvas with Cubbie's Canvas capability (the course and assignment named in the email) and put the real grade in the text. See "Grade emails" below.
4. Rank what passes by urgency and keep the top three.
5. Text the student a short list, then offer to draft replies for the ones that need one.
6. Never archive, delete, label or mark anything as read.

## What counts as important

An email passes only if it is about the student's own school, job search or money, and something is waiting on them. Count it if it fits one of these:

- **Assignments and exams:** a due date, a changed due date, an extension, a quiz or exam announcement, or a missing or late assignment. This also counts when a classmate or friend emails about an assignment, a group project or an exam, since the content is what matters.
- **Grades:** a posted or released grade, a grade problem, or a regrade or grade dispute. A grade email counts even if it is an automatic notification, and it is the one kind of Canvas notification email to keep.
- **Interviews and meetings:** a recruiter or employer asking for a time, an interview invite or follow-up, or a professor, TA or advisor asking to meet or asking the student a direct question.
- **Jobs and internships:** an application deadline, a request for documents, or a real job or internship offer. A real offer comes from an employer or school about a position.
- **School admin and money:** financial aid, tuition or billing, the registrar, registration or a hold on the account, a missing document, or housing.
- **A real person waiting:** someone wrote to the student directly and asked a question or asked for something.

## What to skip

Skip an email when it is any of these, even if it sounds urgent:

- **Promotions and sales:** store, clothing brand, food, app or event offers, discounts, coupons, "ends tonight" or "limited time" deals. Urgent wording means nothing here. A deadline only counts if it is about the student's own school, job search or money.
- **Newsletters and mass blasts:** club announcements, campus-wide updates and mailing lists that ask nothing of the student.
- **Receipts and confirmations** that need no action.
- **Social and app notifications.**
- **Routine Canvas notification emails** that only repeat what Canvas already shows. Keep one only if it announces a changed date or a posted grade.

## Grade emails

When an email says a grade was released or posted:

1. Find the course and assignment it names, then read that grade from Canvas. Use the number Canvas returns, such as points earned out of points possible, and the percentage if Canvas gives one.
2. Put the grade in the text, for example "CSE 434 Lab 3: 46/50 (92%)". Do not make the student open Canvas to find it.
3. Use only the grade Canvas returns. Never copy a grade from the email body, and never guess one.
4. If Canvas is not connected, cannot be read, or does not show the grade yet, say so in one line, for example "CSE 434 Lab 3 grade is posted. I could not read the number, check Canvas." Do not leave it out.
5. A released grade is information, so label it "grade, no reply" and do not offer a draft. Offer one only if the student asks about a regrade.

## No-reply emails

Some emails say "do not reply", or come from a no-reply address. Handle them like this:

- Nothing to do, just information: skip it.
- There is something to do with a date (submit a form, pay a bill, upload a document): include it, label it "action, no reply", say what to do and by when, and do not offer a draft.
- Never draft a reply to a no-reply email.

## Ranking

Put the most urgent first:

1. Something due or happening within 48 hours.
2. A person waiting on a time or an answer (interviews, meetings).
3. Grades, financial aid and account problems.
4. Direct questions with no deadline.
5. Anything unsure. Include it only if there are fewer than three, and mark it "maybe".

If more than three pass, text the top three and say how many more there are ("2 more, want them?").

## Replies

Keep each text to a few short lines, plain text, one idea per message. No Markdown, tables or bold. Lead with the most urgent item. Say what the email wants in your own words, and do not copy long parts of it. Put any link on its own line.

Label each item so the student knows what to do:
- "reply" means a reply is needed.
- "action, no reply" means do something but do not reply.
- "grade, no reply" means a grade was released. Show the grade from Canvas.

Example:

```text
4 emails need you:
- Prof. Lee (reply): wants to move your meeting to Thu 2 pm
- Financial aid (action, no reply): upload 1 document by Fri
- Jordan (reply): says Lab 4 is due Thursday now, not Friday
- CSE 434 Lab 3 (grade, no reply): 46/50 (92%)

Want me to draft the replies?
```

## Drafting a reply

1. For a scheduling email, check the student's Google Calendar first so the draft does not suggest a time that clashes.
2. Write a short, polite draft and show it in the text.
3. Send only after the student says yes. If they ask for changes, change it and show it again.
4. Never send anything without the student's yes.

## Daily check-in

After the first run, offer a recurring check-in. Ask one question: "Want this every night at 8 pm?" and let the student pick the time and how often. Create it only after they say yes.

Word the scheduled task so it still makes sense days later: "Run the Inbox Triage Text Skill. Check the student's school email since the last check and text only what needs a reply or action."

If a check-in finds nothing, send one line like "Nothing needs you today." Never list the skipped email.

## When something fails

- Email search does not work: say so in one line and offer to try again later. Do not guess what is in the inbox.
- A grade email came in but Canvas cannot give the grade: say the grade is posted and ask the student to check Canvas. Never guess the number.
- Nothing came in: say so in one line.
- Never invent a sender, a date or a request. Use only what the email says.
