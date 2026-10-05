# UHC Survey Y2: CAPI ticket register

This is where anyone working on the **UHC Survey Year 2** can report a problem with the tablet
apps or the HCW survey (F2). Each report becomes a ticket, and the survey team reviews every
ticket before anything is changed.

> **Open for the whole survey.** Report any problem you meet in the field. Put the build you are using in the form's Build box (the first screen of a new case shows it; the Field Hub's name ends with it).

*It was open during SE training (29 September to 5 October 2026) and for the bench test on 5 October. Tickets #1 to #41 from those rounds are closed and kept here for the record.*

## Report a problem

1. You need a free GitHub account. Sign in first.
2. Go to **[Issues → New issue](../../issues/new/choose)** and pick **CAPI finding**.
3. Fill in the form. One form per problem.
4. Say who you are and type your FS or SE number (e.g. *FS 07*, *SE 045*). SRAs, the Data
   Manager and HQ type *SRA*, *DM* or *HQ*.

Can't use GitHub? Tell your SRA, or post in the team's Slack channel. Those reports are filed
here for you.

## What to put in a report

- **The app and its build.** The first screen of a new case shows it, e.g. *Build: F3 v7.3.0*.
- **Where:** the question number (e.g. Q96) or the name of the screen.
- **What happened**, and **what should have happened**. Type any error message exactly.
- **A screenshot or a short screen recording**, if you can, following the rules below.

## This page is public: keep it free of personal data

Anyone on the internet can read this page. Before you post a screenshot, crop or cover:

- names of respondents, patients or household members;
- **facility names**;
- addresses, phone numbers and GPS coordinates;
- photos of people;
- passwords (**never** post one) and anyone else's username. Your own FS or SE number goes only
  in the form's box for it;
- the full questionnaire number. If we need it, we will ask for it privately.

Describe the problem by question number instead. If you posted something by mistake, say so in
Slack and it will be taken down.

## What happens next

- Reports are checked three times a day, at about 6:00, 12:00 and 18:00 (Manila time).
- Every ticket is labelled with its app and how serious it is, and answered on the ticket with
  what it is. Some ask for something the survey cannot do.
- **The survey team reviews every ticket and decides what happens next.** Nothing is changed
  until the team approves it; serious problems are raised with the team at once.
- An approved fix goes to the server, and the Slack channel gets a patch note with the new version.
- The ticket is closed with the build that fixes it. If the problem is still there after your
  tablet is updated, comment on the ticket and it is reopened.

**Updating a tablet:** CSEntry → ⋮ → *Add Application* → *CSWeb server* → *CONNECT* → tap
**UPDATE** next to the app. **Never remove an app**: removing it deletes the cases on the tablet.

## Current builds (5 Oct 2026)

| App | Build |
|---|---|
| Facility Head Survey (F1) | v5.8.0 |
| Patient Survey (F3) | v7.10.0 |
| Household Survey (F4) | v4.10.0 |
| Field Hub | v1.15.4 |
| HCW Survey (F2, in the browser) | v3.1.0 · spec 2026-10-05-m6 |

A tablet shows an older build until it is updated (see above). The HCW survey updates with one
page reload.

---

This repository holds only the report form. The survey apps are developed elsewhere.
