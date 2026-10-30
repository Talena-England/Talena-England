### Talena England

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="2026-stats-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="2026-stats-light.svg">
  <img alt="2026 in numbers: 463 commits, 247 deployments, 17 repos touched, 170 tickets closed" src="2026-stats-light.svg">
</picture>

#### Projects I'm proud of

<details>
<summary><b>Watchdog</b> · Otto's internal home for automated test results</summary>
<br>

Every automated test suite at Otto reports its runs in from CI, and Watchdog turns them into one place to see what's passing, what's flaky and what actually broke. I led its rebrand and built most of what it does today: automatic failure triage, lane-only failure callouts, flaky and broken tests that file their own tickets (which retired our Slack failure alerts), starting runs from the UI, feature coverage, test documentation, a redesigned run detail page and dark mode.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/watchdog/history-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/watchdog/history-light.png">
  <img alt="Watchdog test history: recent E2E runs with their lane, author, ClickUp ticket and status" src="assets/watchdog/history-light.png">
</picture>

<details>
<summary>More screenshots</summary>
<br>

<table>
  <tr>
    <td colspan="2"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/watchdog/detail-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/watchdog/detail-light.png">
  <img alt="Test run detail page: pass and fail counts, an automatic Flaky Test tag with its reason, and failures only seen on this lane" src="assets/watchdog/detail-light.png">
</picture><br><sub>Run detail: auto failure reason and lane-only failures</sub></td>
  </tr>
  <tr>
    <td width="50%"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/watchdog/filtered-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/watchdog/filtered-light.png">
  <img alt="Test history filtered to auto-tagged runs that nobody has confirmed yet" src="assets/watchdog/filtered-light.png">
</picture><br><sub>Test history, filtered to auto-tagged runs</sub></td>
    <td width="50%"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/watchdog/reports-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/watchdog/reports-light.png">
  <img alt="Reports tab charting test runs by status and failed runs by reason" src="assets/watchdog/reports-light.png">
</picture><br><sub>Reports: runs by status, failures by reason</sub></td>
  </tr>
  <tr>
    <td width="50%"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/watchdog/coverage-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/watchdog/coverage-light.png">
  <img alt="Feature coverage tab showing covered, partial and missing feature areas" src="assets/watchdog/coverage-light.png">
</picture><br><sub>Feature coverage and gaps</sub></td>
    <td width="50%"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/watchdog/docs-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/watchdog/docs-light.png">
  <img alt="Documentation tab listing documented tests by feature with their tags" src="assets/watchdog/docs-light.png">
</picture><br><sub>Test documentation by feature</sub></td>
  </tr>
</table>

</details>

<sub>Screenshots run on made-up demo data. Watchdog is internal, so its code and data stay private.</sub>

</details>

<details>
<summary><b>QA skills for Claude Code</b> · AI workflows that help Otto's QA team test faster</summary>
<br>

Otto's engineering team shares a workspace of Claude Code skills. I built most of its QA side: four skills I created and two I extended. Together they take a ticket from the first read through to a verified fix.

| Skill | What it does | My part |
|---|---|---|
| **Write QA notes** | Drafts a ticket's testing steps in the team's QA format | Created |
| **QA task research** | Finds every branch, PR and code change behind a ticket and explains it before testing starts | Created |
| **Fix E2E tests** | Traces a failing CI run or Playwright trace to its root cause and a fix, then checks the fix on fresh runs instead of retries | Created |
| **Write E2E test** | Writes new Playwright tests that follow each suite's own patterns | Created |
| **Manual verification** | Runs a QA plan step by step and records pass/fail with screenshots | Added a Flow browser driver (including two-user scenarios), a blind QA pass, and an approval gate for test data |
| **Verify test coverage** | Compares a ticket's changes against unit and E2E tests and names the gaps | Connected it to Watchdog's feature coverage |

I also made all of them work with both of Otto's E2E suites, and I keep their docs in step with how the suites actually run.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/qa-skills/manual-verification-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/qa-skills/manual-verification-light.png">
  <img alt="Manual verification run record: seven scenarios with expected and actual results, one failed double-submit check, and a verdict with the blind-pass agreement" src="assets/qa-skills/manual-verification-light.png">
</picture>

<sub>A manual verification run record, on made-up demo data. The workspace is internal, so its code stays private.</sub>

</details>
