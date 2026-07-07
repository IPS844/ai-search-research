# How ChatGPT Selects Sources

## Objective

To understand what types of sources ChatGPT prefers when answering brand, product, service, and recommendation-based queries.

## Research Question

When ChatGPT answers a search-like query, what signals appear to influence which websites, brands, or sources are mentioned?

## Hypothesis

ChatGPT is more likely to mention or cite sources that show strong trust signals, clear entity relevance, topical authority, community validation, and consistent brand presence across the open web.

## Platforms Tested

- ChatGPT
- Gemini
- Perplexity
- Claude
- Google AI Overviews

## Test Categories

- Brand recommendation queries
- Product comparison queries
- Service provider queries
- Local business queries
- SaaS recommendation queries
- Educational queries

## Methodology

1. Select a group of brands or websites from the same category.
2. Create a fixed prompt set for each category.
3. Run the same prompts across multiple AI platforms.
4. Record which brands and sources are mentioned.
5. Check whether cited or mentioned brands have stronger trust signals.
6. Compare results with Google SERP visibility, Reddit visibility, reviews, authority signals, and content depth.

## Data Points to Track

- Prompt used
- AI platform
- Brand mentioned
- Source cited
- Citation URL
- Ranking position in Google
- Reddit or forum presence
- Review presence
- Brand search volume
- Content depth
- Entity clarity
- Observation notes

## Early Observations

This section will be updated after running the first test batch.

## Limitations

- AI responses may change across sessions.
- Some platforms provide citations while others may not.
- Personalization, location, and time may affect results.
- This research is observational and not a confirmed explanation of model behavior.

## Next Steps

- Build the first prompt dataset.
- Run initial tests across 20 to 50 prompts.
- Record citation and mention patterns.
- Summarize findings in the `findings/` directory.
