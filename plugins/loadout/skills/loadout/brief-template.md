# Business Brief: {business name, or a working title}

Updated: {YYYY-MM-DD}

## Snapshot

{Two or three sentences: what the business does, for whom, where, and where it stands today.}

## Facts

<!-- One numbered item per fact, each ending with a label: [observed], [data YYYY-MM-DD] or [assumed].
     Each playbook or skill adds its own subsection (### Founder, ### Market, ...). Number items per
     subsection (T1, M1, P1...) so later work can cite them. -->

## Decisions

<!-- - {What was decided} because {why}. [label] -->

## Rejected

<!-- - {Option} because {why}. Stops the same idea coming back. -->

## Verify list

<!-- - {An assumed fact or open question, and how to check it} -->

## Outputs

<!-- - {Deliverable}: {file name, artifact title or link} -->

## Progress

```json
{
  "playbook": "{playbook name, or null}",
  "stage": "{journeys only: the current milestone id}",
  "stages": {},
  "outcomes": {},
  "results": [],
  "next": "{the next action, in one line}"
}
```

<!-- Journeys (Kickstart, Ad Lab): put milestone statuses in "stages" and the current one in "stage".
     Service playbooks: put outcome statuses in "outcomes" (win-clients, deliver-the-work,
     prove-results, sharpen-the-business) and dated lines in "results" ("2026-10-20: first client
     signed"); leave "stage" and "stages" empty. Statuses: todo, doing, waiting (homework in
     progress), done, assumed (done on defaults), skipped. Only change status fields; don't rename ids. -->
