# CLAUDE.md

This is the working contract for AI assistance in `Productside/.github`.

`CONSTITUTION.md` outranks this file. If the two conflict, the Constitution wins.

## What this repository is

The community health repository for the Productside GitHub organization. It holds the defaults that apply across all public Productside repositories: contribution rules, conduct, security reporting, support expectations, licensing, trademarks, and the organization profile shown at github.com/Productside.

**It is public.** Every file is world-readable by anyone, permanently. There is no draft state.

## Who reads it

Two audiences at once, and both matter:

- **Outside visitors** — prospects, clients, learners, journalists, competitors, and future hires who land on github.com/Productside. Many are product managers, not programmers. Several are evaluating whether to buy from Productside.
- **Productside teammates** — instructors, marketing, and customer success staff who may never have created a repository.

Write for people who are smart but not technical. Explain before you require.

## Non-negotiable: Productside is a services firm, not a software company

Productside's client agreements are written for **services**. Describing published materials as "code" or "software" invites counterparties to treat Productside as a software vendor, which attaches software security questionnaires and warranty terms to a training agreement.

Describe repository contents as **digital takeaways and examples that demonstrate and extend Productside's teaching and advisory services**: classes, workshops, webinars, consulting, advisory engagements, and lead generation.

| Term not to use | Term to use instead |
|---|---|
| code, codebase | materials, resources, digital takeaways, files |
| software | *(omit; say "the platform" when you mean GitHub itself)* |
| scripts | prompts, skills, templates |
| your developer | whoever set up the tool, your technical contact |
| app, application | tool |
| deliverable, product | takeaway, example, material |

Three exceptions: GitHub-mandated filenames (`CODE_OF_CONDUCT.md`, `CODEOWNERS`), vendor product names ("Claude Code"), and prohibitions that name code ("never put a secret in code"), which describe what Productside forbids rather than what Productside builds.

**Never add a roadmap item, feature promise, or capability claim that reads as a commitment to build or maintain software.** A crawler was once advertised in a public README this way. It came out.

## Naming the people Productside serves

*Students*, *participants*, and *learners* all refer to the people in a class, workshop, or webinar. When a rule enumerates whose data is protected, include **learners** alongside students and participants. A partial list is how someone decides a rule does not cover the group in front of them.

## Legal entity

**280 Group LLC, dba Productside.** Copyright lines and formal legal notices name the entity. Body text may say Productside.

## Voice

- plain English over jargon
- analogies over abstraction
- explain the consequence alongside the rule, so people can act on it
- professional and practical, never hype
- **no em dashes as clause separators in prose.** Use periods, commas, colons, or parentheses. Em dashes are acceptable only in the `**Term** — definition` list format

## Structure

| File | Purpose |
|---|---|
| `LEGAL.md` | Index of licensing, trademark, privacy, and terms. The entry point for legal questions |
| `LICENSE` | CC BY-NC-ND 4.0 with a plain-language as-is disclaimer |
| `TRADEMARKS.md` | Brand usage. A content license grants no trademark rights |
| `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, `SUPPORT.md` | Community health defaults inherited by every public Project |
| `profile/README.md` | The org landing page at github.com/Productside |
| `.github/workflows/content-guard.yml` | Blocks client names, SharePoint file types, oversized files, credentials |

## When making changes

1. **Assume it is permanent.** Deleting a file does not remove it from history.
2. **Check the live legal pages still control.** Nothing here may modify, extend, or replace productside.com's Privacy Policy or Terms & Conditions.
3. **Keep `LEGAL.md` current.** If a legal or policy file is added, renamed, or removed, update the index and the `README.md` table in the same change.
4. **Do not duplicate legal text from the website.** Two copies drift, and then nobody can say which governs. Link, do not copy.
5. **Human review before merge.** Always.

## Detailed guidance

The full internal manual lives in the private `productside-launchkit` Project. Chapter `02-09 Positioning, Licensing, and Terms` covers the reasoning behind the vocabulary and licensing rules above.
