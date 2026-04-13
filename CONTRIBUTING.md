# Contributing an article

Articles are foundation/reference content for The Builder Weekly. Unlike tutorials (which teach how to build something), articles define terms, explain concepts, and serve as canonical references.

## Article structure

Every article must have:
- A canonical question as the title ("What is AI building?", "Who is an AI builder?")
- A one-paragraph summary (50-300 characters)
- An editorial pillar assignment (building, economics, or trust)
- Foundation-level depth - assumes no prior knowledge
- 1500-3000 words
- Citations for non-trivial factual claims
- Cross-links to relevant weeklies, monthlies, and tutorials

## File structure

Each article lives in `entries/{slug}/` with:
- `metadata.json` - validates against `schema/article.schema.json`
- `article.mdx` - the article body in MDX format
- `README.md` - brief description of the article
- Any SVG or image assets referenced in the MDX

## The review process

1. Open a PR touching `entries/` paths
2. tbw-ai reviews the PR automatically - structural checks, content checks, SEO audit, factual review
3. tbw-ai may propose auto-fixes for SEO and technical issues
4. A human editor reviews for editorial quality
5. On approval, the article is merged and deployed
6. The article is re-reviewed on a monthly cadence to check for freshness and accuracy
7. If updates are proposed later (by the original author, an editor, or tbw-ai), the review process runs again

## License

All articles are published under CC BY 4.0. Attribution is required, but articles can be freely forked, reused, and adapted.
