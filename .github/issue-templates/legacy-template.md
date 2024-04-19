<!-- 
./.github/issue-templates/legacy-template.md

Template markdown for creating issues,
for the legacy auto-issue actions.
-->
---
title: Issue created on {{ date | date ('MMM Do at HH:mm:ss') }}
assignees: KemingHe
labels: bug, enhancement
---

- Workflow: {{ tools.context.workflow }}
- Author: {{ tools.context.actor }}

The full `tools.context.payload` content is listed below:

{{ tools.context.payload }}

{{ payload.sender }}

{{ payload.sender.login }}
