# Handing work over

Every piece of work that leaves the user's hands goes out as a page we can measure, and finished client work goes out as something the client owns. This file is the method behind the router's step 5. Read it when a skill is about to produce something for a client, a prospect, a partner or a designer.

## What gets published

Publish it when someone other than the user is meant to read it: a proposal, an audit, a preview built for a prospect, a case study, a monthly report, an ad pack for a designer, an onboarding pack, a finished project handover, a claims or policy report.

Keep it in the chat when it is working material for the user alone: a shortlist they will paste into a spreadsheet, a draft they are still editing, a private walk-away note, a brief for their own eyes.

**A list the user will work on goes out as a file.** Lead lists, contact lists, keyword lists and anything else with more than a handful of rows: where you can write files, save it as a CSV in the working folder, one row per item, and say in the chat where it is. The chat then shows the top few rows as a preview, not the whole list. Where there is no file system, give the rows in the chat and offer them as CSV text to paste.

Never publish anything without an explicit yes on that exact text. Show the user the page content first, then publish on their word.

## What a page carries, every time

1. **A title in the reader's own words.** The client's business name and what the page answers, not our power's name.
2. **A password** when the page names a third party, carries prices or carries anything the reader would not want found.
3. **An expiry set from the job**, with the reason in one line on the page.
4. **What we checked and what we could not**, in the four words below.
5. **The date and the run link** for every number on the page.

### Expiry from the job

| What the page is | Expiry | Why to say |
|---|---|---|
| Proposal or quote | the day the offer stops being valid | the price on the page is only good until then |
| Prospect preview | 14 days | it was built for one conversation |
| Audit or report a client keeps | no expiry | they paid for it, they keep it |
| A baseline, or version 1 of anything | no expiry | the next report compares against it |
| A pack for a designer or a partner | the end of the job | nothing of the client's stays up afterwards |

### The four words for what is missing

Never interchangeable, on every page:

- **Nothing found** means the check ran and came back empty.
- **Could not look** means the source failed or we have no access to it.
- **Did not check** means it was out of scope, with the reason.
- **Partial** means it ran and is incomplete, with how much of it ran.

A check that did not run scores nothing. It is never a pass and never a fail.

## Versions and baselines

- **Version 1 is the baseline and is never edited.** `publish` keeps the same link and raises the version, so a change is always version 2 or later.
- A baseline carries the exact inputs needed to repeat it: the business, the place id, the keywords as typed, the grid size and spacing, the devices, the review sites, and the hour of day where that matters.
- A rerun with changed inputs is a new baseline, not a comparison. Say so rather than reporting an improvement.
- A page built to win work is not a baseline. The baseline is taken after they say yes and before any work starts.

## Reading the page back

list_pages gives, per page, the link, the version, whether it has a password, the expiry, and views, visitors, first opened, last opened and average seconds. Read it before deciding what to do next.

Check the page yourself through the `owner_url` that `publish` and `list_pages` return, never through the link you hand the client: owner opens are not counted, so the view numbers below stay the client's. Never send `owner_url` to anyone else.

| What the page list shows | What to do |
|---|---|
| No views after two days | one short message on the channel they wrote on, naming the single strongest finding rather than the document |
| Opened once, under about half a minute | the headline missed. Send that one finding as plain text with no link |
| Opened twice or more, or over about five minutes | call them, and say why: they read it twice |
| Opened, then nothing for a week | one question about the ideas in it. Never a meeting request |
| Expired with no views | say plainly that it is dead, and ask whether to rebuild it or drop it |
| A monthly report unopened two months running | the earliest sign a client is leaving. It goes in the user's private note, not in a client email |

Two rules around it. The email that carries the link is never open tracked: across 31M emails, replies ran 7.4% with email tracking off and 4.4% with it on, so the page carries the tracking and the email carries none. And after three nudges on the same page, drop it for good.

## Hand it to your client

For finished work the user did for their own client (a built site, an academy, a book, a set of pages, a campaign), the page is the handover. Four blocks, in the client's words, under the heading they use themselves: "how do I hand it over to the client".

**1. What you now own.** Every piece by name, where it lives, and who the account is in the name of. Anything the user keeps on the client's behalf is named here too, with the date it transfers.

**2. How to get in.** The route to each account or page, step by step, through the client's own sign-in or an invite sent to their email. Never ask a client for a password, never ask the user for the client's password, and never put a password or key in the page. Where something is still in the user's name, say what has to happen for it to move and who does it.

**3. How to use it.** The five things they will actually do, each in a few lines they could follow without the user: publish a post, add a page, change a price, answer a review, send the monthly email. Written for someone who has never seen the tool.

**4. What happens next and when.** The next dates, each with who acts: the first report, the next review, when a domain or licence renews, when support ends and what happens after. Dates only, never "soon".

Then the last line on the page: what the user is still responsible for, and what the client is responsible for from today.

## Checks before a page goes out

1. The page exists and the handover message gives the link. No link, not delivered.
2. It was published before the reader asked for it.
3. Expiry set from the job, with the reason stated. Password set where the page names a third party or carries prices.
4. Every number on the page resolves to a tool result in this conversation or to the user, with its date and run link.
5. What we could not check is on the page, in the four words.
6. Version 1 is marked as the baseline, with its inputs to reuse.
7. The user said yes to that exact text.
8. For a client handover, all four blocks are filled, and no password was asked for, stored or shown.
