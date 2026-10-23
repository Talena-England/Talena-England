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
