# C2H_FEEDBACK — yangliu-op-website

Append-only record of feedback about the cc/cx interaction protocol observed in this
project. Rules: `$c2h` skill (`SKILL.md` is the sole rule source). Paper-workflow
feedback does not belong here; it goes to `.opaperhelper/OPAPERHELPER_FEEDBACK.md`.

Entries are immutable once appended, including for their own writer; changes and
objections are new entries referencing the target `entry_id`. The project steward
writes this file; other agents propose in their own handoff; the author may write
directly. Never record embargoed blind-audit content here.

## Entries

### feedback entry

```text
entry_id: yangliu-op-website-YYYYMMDD-{actor}-{sequence}
date_writer: YYYY-MM-DD 作者|cc|cx
observation: what happened, with a quote or event pointer
proposed_change: the concrete change to the interaction protocol
generality_basis: second project | mechanism argument | author decision | (single event: leave empty)
status: proposed
```

### status event

```text
date_writer: YYYY-MM-DD 作者|cc|cx
related_entry_id: the entry being updated
new_status: ready_for_route | routed | rejected | superseded
basis: routed names the intake artifact; rejected/superseded give the reason or the replacing entry
```
