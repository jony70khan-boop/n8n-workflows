# n8n Workflows — BikriBoost (NITN)

Open-source n8n automation workflows from **BikriBoost**, Jony's AI automation
agency. Built free, runs on n8n (self-hosted on a laptop or a free cloud VM).

## What's inside

| File | Workflow |
| --- | --- |
| `workflows/bd-explainer-pipeline-v1.json` | Bangla explainer video pipeline (pilotvideo001) |
| `workflows/pilot-v3-1.json` | Satyer content pipeline v3.1 |
| `workflows/news-auto.json` | Bangla news auto-posting to Facebook |
| `workflows/deals-auto.json` | Deals auto-posting |
| `workflows/profit-tracker.json` | Profit tracker |
| `workflows/feedback-collector-v1.json` | Feedback collector |
| `workflows/satyer-agency-*.json` | Agency agent suite (research, content, video, SEO, social, marketing) |

## How to use

1. In n8n: **Workflows → Import from File**, pick a JSON.
2. Connect your own credentials (Facebook, Gmail, etc.) — **no credentials
   are included in this repo, ever.**
3. Activate the workflow. The news workflow posts on its own schedule;
   the video pipeline is manual.

## Notes

- Workflows are shared as-is, free for anyone to use and adapt.
- Built with n8n 2.x. Imported Webhook nodes carry a `webhookId`.
- Part of the BikriBoost zero-investment automation setup (n8n + Groq free tier).
