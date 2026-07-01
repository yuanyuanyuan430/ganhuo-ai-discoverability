# AI Discoverability Checklist

Score each area as `0 missing`, `1 partial`, or `2 ready`. Prioritize the items most likely to increase AI discovery, accurate understanding, and recommendation opportunities.

| Area | Ready signal | Common fix | Verify |
| --- | --- | --- | --- |
| Entity clarity | One canonical description names the brand/product/person, audience, category, and differentiator | Write a concise entity summary and reuse it across homepage, about page, docs, GitHub, profiles, and `llms.txt` | Ask target AI platforms to describe the entity; compare against the truth notebook |
| Answer intents | Target queries cover recommendation, comparison, definition, how-to, use case, alternative, and limitation prompts | Build an intent table with the page that answers each prompt | Re-run the same prompt set and record presence, citation, and accuracy |
| Crawl access | Search/retrieval bots and user-triggered fetchers can reach key URLs without WAF/auth/rendering failures | Update robots.txt, WAF allow rules, raw HTML, canonical/noindex, or sitemap | Fetch as plain HTML/Markdown; inspect logs or platform diagnostics |
| AI entry files | Root domain exposes `llms.txt`, fuller project context, sitemap, and important Markdown routes | Add `llms.txt`, `llms-full.txt`, `.md` pages, and `rel="alternate"` links | Open each URL directly and confirm status 200, correct MIME/content, and internal links |
| Index discovery | Google and Bing know the sitemap; important URLs are submitted or indexable | Submit sitemap; use URL inspection; add IndexNow for update notification where appropriate | Search-console/webmaster-tool status plus `site:` spot checks |
| Citation readiness | Core pages contain quotable summaries, data, comparisons, caveats, and source links | Rewrite thin pages into 1000-3000 word evidence-rich pages | Check whether answer snippets can be copied without losing context |
| Third-party proof | Relevant external pages mention or evaluate the entity honestly | Plan review, media, community, partner, or directory surfaces without fake engagement | Record source URL, independence, and likely query match |
| Domain consolidation | Critical data is not stranded across subdomains with no root-domain path | Mirror or proxy key structured files on the main domain | Confirm root-domain URLs expose key summaries and project data |

## Routing Rules

- Route to `ganhuo-geo-technical-audit` when crawlers cannot access, render, index, canonicalize, or parse the site.
- Route to `ganhuo-llm-citation-growth` when baseline prompts, competitor citations, source gaps, or retest loops are the main work.
- Route to `ganhuo-reddit-seo-geo` when Reddit threads already rank or appear in AI answers for the niche.
- Mark the foundation complete when the entity is discoverable, accurately described, and backed by useful public-facing assets.

## Output Template

```markdown
## AI Discoverability Brief

### Entity Map
| Entity | Canonical URL | Audience | Category | Differentiator | Confidence |
| --- | --- | --- | --- | --- | --- |

### Answer Intent Map
| Intent | Example prompt | Best current source | Gap | Priority |
| --- | --- | --- | --- | --- |

### Foundation Checklist
| Area | Score | Evidence | Fix | Verify |
| --- | --- | --- | --- | --- |

### Actions
1. ...
2. ...
3. ...

### Route
Next skill: ...
Success criterion: ...
```
