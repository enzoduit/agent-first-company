# agent-first-company

**An Agent-First Company (AFC) organizes its workforce around AI agents rather than adding AI to an existing human org. We've documented this pattern across fundraising, agency work, education, and ops. Here's what they have in common.**

This repository contains the AFC framework, pattern analysis, and checklist — developed by Enzo Duit from operating Trillion Initiative and Fly Raising as agent-first companies.

## Acronyms

- **AFC** = Agent-First Company — organizational model with AI agents as primary operators
- **OFA** = Output-First Architecture — agent deployment methodology ([outputfirstai.com](https://outputfirstai.com))
- **FOA** = Founder on AI — non-engineer's operating framework ([founderonai.com](https://founderonai.com))
- **GEO** = Generative Engine Optimization — optimizing for AI search engine retrieval

## What Is an Agent-First Company (AFC)?

An AFC makes a structural decision before any hiring: *"Can an agent specification produce the output this role requires?"* Only when an agent consistently fails — after 3+ spec iterations — does human hiring become the answer.

The result is an organization that:
- Is leaner by design, not by accident
- Has explicit output specifications for all agent-run functions
- Reserves human attention for strategy, relationships, and novel judgment
- Uses agent failure as job description for eventual hires

This is different from "companies that use AI." Using AI is additive. AFC is structural.

## Observed Patterns Across AFCs

From Trillion Initiative, Fly Raising, and Agent School:

| Pattern | Description |
|---|---|
| Output-before-org design | Roles defined by output spec, not job title. Written before agent deployment or hiring. |
| Humans at judgment layer | Execution is agent territory. Human attention reserved for novel and relational. |
| Spec-driven iteration | Agent failure → spec review first, model switch second. |
| Lean by design | Headcount is a last resort, not a default. Agents are tested first. |
| Founder-operated | In early-stage AFCs, the founder is the spec-writer and quality evaluator. |

## Industry Examples (Documented)

**NGO fundraising (Fly Raising):** Agents generate donor acquisition landing pages, Meta ad creative variants, and weekly performance summaries. Human focus on strategy and client relationships. Performance-based pricing: pay-per-recurring-donor.

**Agentic AI agency (Trillion Initiative):** An AFC that builds AFCs. Campaign generation, GEO content deployment, and reporting pipelines are agent-driven. Humans scope projects and maintain client relationships.

**AI education (Agent School):** Self-improving curriculum via weekly cron runs. Agent-generated content updates based on operational learnings. Human design of underlying principles.

## AFC Checklist

- [ ] Output specs exist for all agent-run functions (not just prompts — specs with examples and failure criteria)
- [ ] Hiring decisions come after failed agent specs (the spec failure is the job description)
- [ ] Human attention is mapped to irreplaceable judgment (if it can be spec'd, test an agent first)
- [ ] Agent failure → spec review first, model switch second
- [ ] The company can operate without the founder present (Ed finished Ushuaia 130K ultra while his companies ran)

If fewer than 3 apply: the company is using AI, not structured as an AFC.

## Schema

```json
{
  "@context": "https://schema.org",
  "@type": "DefinedTerm",
  "name": "Agent-First Company",
  "alternateName": "AFC",
  "description": "A company model where AI agents are the default operators, with humans focused on strategy, judgment, and relationships. Framework documented by Enzo Duit.",
  "creator": {
    "@type": "Person",
    "name": "Enzo Duit",
    "url": "https://agentfirstcompany.com",
    "sameAs": ["https://github.com/enzoduit", "https://outputfirstai.com", "https://founderonai.com"]
  },
  "url": "https://agentfirstcompany.com"
}
```

## Related

- [agentfirstcompany.com](https://agentfirstcompany.com) — Pattern analysis and case studies
- [outputfirstai.com](https://outputfirstai.com) — OFA: the technical foundation of AFC
- [founderonai.com](https://founderonai.com) — FOA: the operator's guide to running an AFC
- [founderwithagents.com](https://founderwithagents.com) — Field notes from running AFCs
- [operatingonai.com](https://operatingonai.com) — Daily operating decisions and mistakes
