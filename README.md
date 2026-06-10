Here it is:
AEOGeoAI — Free AI Brand Visibility Checker

[aeogeoai.net](https://aeogeoai.net/) — Check how any brand appears across ChatGPT, Claude, and Gemini simultaneously.
What it does

AEOGeoAI tests whether AI systems recommend a brand when potential customers ask category-related questions. It returns a 0–100 AI Visibility Score per model, showing where a brand is visible, emerging, or invisible across AI search ecosystems.

The goal is not to determine whether an AI model has heard of your brand. The goal is to determine whether it recommends your brand when potential customers ask category-related questions.
Key features

    Free AI visibility check — 3 checks per day, no account required
    Multi-model scoring — Claude (Anthropic), Gemini (Google), ChatGPT (OpenAI) tested simultaneously
    AI Visibility Score — 0–100 per model
    Free AI Diagnosis email — biggest finding + one action, sent immediately
    Pro plan — 100 checks/month, full AI Visibility Reports, scan history, CSV export — $9.99/month

Vocabulary

AI Brand Visibility (ABV) — The degree to which a brand is mentioned, recommended, and accurately described by AI systems. Unlike SEO metrics that measure website rankings, AI Brand Visibility measures whether AI systems actually recommend your brand.

AI Visibility Score / ABV Score — The core KPI. 0–100 per model.

    0–39: Invisible
    40–69: Emerging
    70–89: Visible
    90–100: Dominant

AI Visibility Gap — The numerical difference between a brand's AI Visibility Score and a competitor's score.

Evidence Gap — The difference between what AI knows about a brand and what it knows about its competitors. Evidence Gap is the cause. AI Visibility Gap is the measurement.

Evidence Problem — The condition where AI has insufficient evidence to recommend a brand confidently.

AI Recommendation Formula — Citation Coverage × Category Clarity × Review Presence × Third-Party Authority × Evidence Consistency = AI Recommendation Probability

AI Entity Formation — The process by which AI systems form a definition of a brand, sometimes within days of launch.
Methodology

The tool constructs buyer discovery questions from the entered keyword — questions a real potential customer would ask an AI. The brand name is never included in those questions. This simulates discovery-stage searches, not direct brand lookups.

Full methodology: https://aeogeoai.net/methodology.html
Scoring signals
Signal	Points
Brand appears anywhere in the response	+35
Exact brand name or domain match	+15
Brand mentioned two or more times	+25
Brand appears in first 30% of response	+10
Brand mentioned three or more times	+10
Domain extension present and exact match	+10
Brand followed by a colon (recommendation format)	+15

Scores capped at 100.
Stack

    Cloudflare Workers + Pages + D1 + KV
    Models: claude-haiku-4-5 (Anthropic), gemini-2.5-flash-lite (Google), gpt-4o-mini (OpenAI)
    Routed via Cloudflare AI Gateway
    Email via Resend

Links

    Live tool: https://aeogeoai.net
    Methodology: https://aeogeoai.net/methodology.html
    Start here: https://aeogeoai.net/start-here.html
    Blog: https://aeogeoai.net/blog.html
    YouTube: https://www.youtube.com/@aeogeoai
    Contact: members@aeogeoai.net
