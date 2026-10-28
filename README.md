# n8n portfolio

Seven workflows rebuilt from the n8n product team's webinar on how they use n8n to build n8n, plus an error-alert workflow and a stretch build with Claude through the n8n MCP. Each folder has the workflow export, a short demo recording and notes.

| # | Workflow | What it does | Status |
| --- | --- | --- | --- |
| [00](00-error-alerts/) | Error alerts | Posts a Slack message whenever any other workflow fails, naming the workflow, node and error. | Not started |
| [01](01-daily-reminder/) | Daily reminder email | Every morning, an AI-written two-sentence reminder lands in my inbox. | Not started |
| [02](02-urgent-email-alert/) | Urgent-email Slack alert | New emails are classified by AI as urgent or not; urgent ones are posted to Slack. | Not started |
| [03](03-webinar-feedback/) | Webinar feedback collector | A form saves feedback to a data table, posts an AI summary to Slack, and a chat agent answers questions about all responses. | Not started |
| [04](04-slack-to-notion-ideas/) | Slack-to-Notion idea saver | React to a Slack message with a link; after approval it is read, summarized, tagged and saved to Notion, with emoji progress updates. | Not started |
| [05](05-self-updating-prd/) | Self-updating PRD | Every morning, decisions from yesterday's Slack are matched to roadmap items and appended to each PRD's decision log in Notion. | Not started |
| [06](06-user-research-pipeline/) | User research pipeline | Transcripts dropped in Drive are analyzed, the interviewer gets coaching, a human writes takeaways in Slack, and a research agent answers questions. | Not started |
| [07](07-launch-pipeline/) | Automated launch pipeline | When a Notion project is completed, linked GitHub PRs become a release memo, a docs PR, an approved changelog entry and a slide. | Not started |
| [08](08-stretch-claude-mcp/) | Stretch: building with Claude via the n8n MCP | Workflow 3 rebuilt by describing it to Claude, which creates and tests it in n8n through the MCP. | Not started |

## Sample data

All data in the demos is fictional. See [`sample-data/`](sample-data/).

## Notes

- Workflow exports contain no credentials; reconnect your own after importing.
- Built on n8n Cloud.
