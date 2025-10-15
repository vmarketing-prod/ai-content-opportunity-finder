# ai-content-opportunity-finder
### Identify high-ROI SEO and AEO content opportunities using AI-based intent and semantic clustering.

## Overview

The AI content opportunity finder helps B2B SaaS marketers and content strategists analyze keyword data to uncover high-value topics that align with both SEO and AEO (Answer Engine Optimization) principles.

It uses a lightweight LLM classification workflow to automatically categorize search queries by:
- search intent — Awareness, Consideration, Decision  
- AEO opportunity — High / Medium / Low  
- recommended content action — Create new / Refresh / Consolidate / Ignore  
- AI reasoning — short rationale to justify prioritization

This project demonstrates how AI can accelerate strategic content planning — turning raw data into actionable GTM intelligence.

## Quick start

1. Open `ai-content-opportunity-finder.ipynb` in Google Colab.
2. Upload `keywords_sample.csv`.
3. Enter your OpenAI API key when prompted.
4. Run the cells and download `output_results.csv`.

## Example input

Columns expected in the input CSV:
keyword,search_volume,difficulty,ctr,current_url

## Example output

Each row in the output contains:
keyword,search_intent,aeo_opportunity,content_action,ai_reasoning

## Prompts

See `/prompts/classification_prompt.txt` for the exact prompt used.

## Requirements

pandas
openai
matplotlib
plotly

## License

MIT

## Author

[Your name] — B2B content strategist focused on AI-driven GTM and content systems
