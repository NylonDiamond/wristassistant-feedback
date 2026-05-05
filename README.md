# WristAssistant Feedback

This is the public tracker for **[WristAssistant](https://github.com/NylonDiamond)** — a Home Assistant companion for Apple Watch and iPhone. Use this repo to report bugs, request features, and share feedback.

The app's source is private; this repo exists so users have a single place to file issues and watch progress on fixes and upcoming work.

## File something

Pick the form that fits — each one asks for the info needed to act on it:

- 🐛 [**Bug report**](../../issues/new?template=bug_report.yml) — something is broken or behaving unexpectedly.
- ✨ [**Feature request**](../../issues/new?template=feature_request.yml) — an idea for something WristAssistant should do.
- 💬 [**General feedback**](../../issues/new?template=feedback.yml) — UX impressions, design thoughts, anything that doesn't fit the other two.

For open-ended questions, please use [Discussions](../../discussions) instead of opening an issue.

> **Bug in the Home Assistant integration?** You can file it here, or directly in [`NylonDiamond/homeassistant-wrist-assistant`](https://github.com/NylonDiamond/homeassistant-wrist-assistant). Either is fine — issues will get routed if they land in the wrong place.

## Before you file

- **Search [open](../../issues) and [closed](../../issues?q=is%3Aissue+is%3Aclosed) issues first** — your bug or idea may already be tracked.
- For bugs, the most useful info is your **WristAssistant version**, **Home Assistant version**, **integration version**, and **watchOS / iOS versions**. The bug template asks for all of these.
- A short screen recording is worth a thousand words.

## Requirements (for context)

- iPhone running **iOS 18.0+**
- Apple Watch running **watchOS 11.0+**
- A working Home Assistant instance
- The WristAssistant Home Assistant integration installed (via HACS or manually)

## Labels

Issues are triaged with these labels:

| Label | Meaning |
| --- | --- |
| `bug` / `feature` / `feedback` | What kind of issue it is |
| `needs-triage` | Hasn't been looked at yet |
| `needs-repro` | Can't reproduce — more info needed |
| `watch` / `iphone` / `integration` | Which surface the issue applies to |
| `complications` / `notifications` / `siri` | Affected subsystem |
| `connection` | Related to local/remote connectivity |
| `priority:high` / `med` / `low` | Triage priority |
| `wontfix` / `duplicate` | Won't be acted on, with reason in comments |

## Roadmap & status

Active work and shipped items are tracked via labels and milestones on the [Issues](../../issues) tab.
