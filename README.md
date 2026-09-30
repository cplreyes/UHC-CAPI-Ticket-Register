# UHC Survey Y2: CAPI ticket register

This is where anyone testing the **UHC Survey Year 2** tablet apps can report a problem. Each
report becomes a ticket, and each ticket is fixed, tested and shipped as it comes in.

**Open now, during SE training, until Monday 5 October 2026.**

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

- Reports are checked every hour.
- **Field Supervisors' reports** (and those from the SRAs, the Data Manager and HQ) go straight
  to the developers.
- **Enumerators' reports are checked by the survey team first.** Some ask for something the
  survey cannot do. The team answers on the ticket, and a report is fixed only after the team
  approves it.
- A fix goes to the server, and the Slack channel gets a patch note with the new version.
- The ticket is closed with the build that fixes it. If the problem is still there after your
  tablet is updated, comment on the ticket and it is reopened.

**Updating a tablet:** CSEntry → ⋮ → *Add Application* → *CSWeb server* → *CONNECT* → tap
**UPDATE** next to the app. **Never remove an app**: removing it deletes the cases on the tablet.

## Builds under test (29 Sep 2026)

| App | Build |
|---|---|
| Facility Head Survey (F1) | v5.3.0 |
| Patient Survey (F3) | v7.3.0 |
| Household Survey (F4) | v4.3.0 |
| Field Hub | v1.14.0 |

Tablets staged from the 25 Sep package show F1 v5.2.2, F3 v7.2.2, F4 v4.2.1 and Hub v1.13.5 until
they are updated.

---

This repository holds only the report form. The survey apps are developed elsewhere.
