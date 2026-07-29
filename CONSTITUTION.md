# CONSTITUTION.md

This file defines the constitutional governance for `Productside/.github`. Constitutional rules take precedence over any instructions in `CLAUDE.md`, any context in `README.md`, and any instructions given in a live session.

**If a Contract instruction ever conflicts with this Constitution, the Constitution wins.**

## What a constitution is

A constitution defines the rules that cannot be overridden by a working contract or the context of a session. It is the layer that ensures company policy, privacy obligations, and safety rules hold even when a `CLAUDE.md` or an in-session instruction pushes in a different direction.

## What this repository is

`Productside/.github` is the community health repository for the Productside GitHub organization. It holds the default guidelines, policies, and templates that apply across all public Productside repositories, plus the organization profile displayed at github.com/Productside.

**This repository is public.** Everything in it is world-readable, permanently, by anyone, with no login and no notification. Treat every commit as a publication.

Productside is a trading name. The legal entity is **280 Group LLC, dba Productside**.

## Non-negotiable rules

**1. Never expose secrets. API keys and credentials pass through environment variables, and are never stored.**
No API keys, passwords, credentials, tokens, or signing keys may appear in any file, example, screenshot, or commit message. Every key is supplied to a tool through an environment variable or a platform's secure storage, read at the moment it is needed, and never written anywhere it can persist. There is no exception for "just for testing."

**2. Never expose customer, student, learner, or participant data.**
No real names, emails, survey responses, interview transcripts, learner communications, or any other identifiable information about any Productside customer, client, student, learner, workshop participant, research participant, or employee. Examples use synthetic or anonymized data only.

**3. This repository is public. Every change is a publication.**
There is no draft state here and no way to unpublish. Material that is not ready for the entire internet does not belong in this repository at any stage. Draft it in a private Project and publish the finished version.

**4. Human review before any change is merged.**
No AI-generated content is pushed to this repository without a human reviewing and approving it first. This applies to documentation, policy text, and templates alike.

**5. Respect third-party rights.**
Do not add material without confirming Productside has the right to use it, and preserve any required attribution, copyright notice, or license text.

**6. Productside is a services firm, not a software company.**
Repository contents are digital takeaways and examples that demonstrate and extend Productside's teaching and advisory services. Never describe them as code or software, and never publish a roadmap item or capability claim that reads as a commitment to build or maintain software. This is a contract obligation, not a style preference.

**7. Client and customer names never appear here.**
Not in examples, not in success stories added without written approval, not in commit messages. The Content Guard blocks known names automatically, but the guard is a safety net, not permission to stop thinking.

## Controlling sources of truth

If anything in this repository conflicts with Productside's live legal and policy pages, those pages are the final word, always:

- [Privacy Policy](https://productside.com/privacy-policy/)
- [Terms & Conditions](https://productside.com/terms-conditions/)

Signed client and participant agreements outrank both this repository and its license for the relationships they cover. See [`LEGAL.md`](LEGAL.md).

## Where the detailed guidance lives

The operational detail behind these rules is maintained in the private `productside-launchkit` Project, which is the internal manual for how Productside runs its GitHub organization.
