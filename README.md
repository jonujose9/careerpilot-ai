# CareerPilot AI

A deploy-ready MVP for resume tailoring, ATS-style job matching, AI-generated application content, and job application tracking.

## Included

- Responsive landing page and app workspace
- Master career profile stored locally in the browser
- ATS-style keyword/job match scoring
- Matched and missing keyword analysis
- AI-tailored resume generation
- AI cover letters
- AI recruiter messages
- Application tracker with statuses
- Open-job workflow with human review before submission
- Print / Save-as-PDF for generated resume content
- Demo fallback if no AI key is configured

## Deploy on Vercel

1. Put this folder in a GitHub repository or import the folder directly into Vercel.
2. Add an environment variable named `OPENAI_API_KEY` in the Vercel project settings.
3. Optionally add `OPENAI_MODEL`; it defaults to `gpt-5.5`.
4. Deploy.

The serverless endpoint is `/api/generate`. The API key is never sent to the browser.

## Local development

Install the Vercel CLI, copy `.env.example` to `.env.local`, add your API key, then run:

```bash
npx vercel dev
```

## Product safety

CareerPilot automates application preparation, not unauthorized third-party account actions. The final application submission remains with the user.
