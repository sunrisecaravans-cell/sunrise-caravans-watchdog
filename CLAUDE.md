# CLAUDE.md — Sunrise Caravan Hub

Read this before doing anything in this repo.

## What this is

The Sunrise Caravans website (project name: Sunrise Caravan Hub / sunrise-van-mate).
Built in Lovable, hosted on GitHub, live at www.sunrisecaravans.com.au.
It replaced the old Oncord site. Organic rankings carried over from that site are
precious — do not break URLs, redirects or metadata without flagging it first.

## Who I am

Steven Andonovski, director and owner of Sunrise Caravans and Sunset Caravans,
290 Eastern Service Road, Burpengary QLD 4505. Also a dealer for Blue Sky Caravans
(dealer only — never describe Blue Sky as something I own or manufacture).

## The stack

- Lovable — visual build and preview work
- GitHub — single source of truth for the codebase
- Supabase — website database (separate project to the CRM database)
- Sunrise CRM — React / Vite / Supabase, separate project, bridge to the site not built yet
- Make.com — automation workflows
- Around the business: Microsoft 365, Pipedrive, ClickSend, Calendly, Mailchimp

Claude Code is for systematic codebase work: audits, consistency sweeps, technical
fixes, redirects, schema, performance. Lovable is for visual iteration where instant
preview matters. Do not rebuild in code what is faster to do visually in Lovable, and
do not do structured multi file work in Lovable.

## Non negotiables

1. **No hyphens in site copy or meta text.** Off grid, off road, all terrain, pre
   purchase, lay out. URL slugs are the exception — leave existing slugs alone.
2. **Australian English.** Colour, tyre, centre, kilometres, organise.
3. **Never change a live URL** without telling me and proposing the 301 first.
4. **Enquiry flow must not break.** Enquiries go to sales@sunrisecaravans.com.au and
   must land without errors. Touching a form, webhook or email route means testing it
   end to end and telling me what you tested.
5. **No fabricated specs.** Weights, ATM, GTM, payloads, battery and suspension specs
   come from the actual van data. If you cannot find it, say so and leave a TODO.

## Voice for anything customer facing

No BS, trustworthy, laid back, naturally funny. The knowledgeable mate who tells it
straight — not a salesperson, not a corporate suit. Education first.

Product and model pages: SEO friendly with emotional pull. Always call out build
quality and the specifics that actually matter to buyers — suspension systems,
battery and power management, chassis, water capacity, payload.

Audience: Australian caravan buyers, grey nomads, families doing the lap.

## How I want you to work

- Audits blunt and evidence based. Cite file paths. Do not soften findings.
- Give me multiple options with a clear recommendation and the reason behind it.
- Structured prompts and outputs I can act on, not essays.
- If something is ambiguous, ask before you write code. One question, not five.
- Tell me what you changed and what you did not.

## Current state and open threads

- Site went live 3 September 2026 on the same domain as the old Oncord site.
- Upgrade options section being added to each caravan detail page, roughly ten options
  per van, differing per van based on that van's features.
- Blog cadence is one post per week, produced by an automated agent, I approve before
  publish.
- Google Search Console access exists for sunrisecaravans.com.au and can be exported
  from if you need ranking or query data.
- The bridge between the website Supabase and the CRM Supabase is not built yet.

## Contacts

- Sunrise business: steve@sunrisecaravans.com.au
- Website and approvals: steve@sunsetcaravans.com.au
- Sales inbox: sales@sunrisecaravans.com.au
