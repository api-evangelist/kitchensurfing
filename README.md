# Kitchensurfing

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

**Status: defunct — shut down April 15, 2016. No API surface. Do not re-run the artifact pipeline.**

Kitchensurfing was a New York City marketplace that booked professional chefs to shop for, cook, and serve
meals in customers' own kitchens. Founded in 2012, it raised roughly $20M from Union Square Ventures, Spark
Capital, and Tiger Global. It began as an advance-booking platform for private dinner parties and pivoted in
2015 to a flat-rate on-demand model. Neither model produced sustainable demand against better-capitalized
meal-kit and delivery competitors, and the company discontinued service on April 15, 2016.

Backed by: union-square-ventures, spark-capital, tiger-global

## Enrichment findings (2026-07-19)

- **No public API was ever published** — no developer portal, documentation, API reference, SDK, CLI,
  webhook, or event surface exists in the archive or anywhere else.
- **No API subdomains resolve** — `api.`, `developer.`, and `docs.kitchensurfing.com` all return no DNS records.
- **The live domain is not this company.** `https://kitchensurfing.com` returns 200 but redirects to
  `https://www.kitchensurfing.com/`, an unrelated WordPress cooking-products affiliate/review site
  ("KitchenSurfing.com is a worldwide resource built by cooks, for cooks"), last updated 2022. The domain
  was re-registered after the shutdown. It is recorded in `apis.yml` with an explicit disclaimer.
- **The GitHub organization is genuine and survives** — [github.com/kitchensurfing](https://github.com/kitchensurfing),
  created 2012-01-12, 11 public repositories, all forks of open-source Ruby/Rails gems
  (`gon`, `resque_mailer`, `sunspot_mongo`, `heroku-buildpack-ruby`, `filepicker-rails`) plus internal
  hackathon projects (`food_tinder`, `food_tinder_RoR`). Last push 2016-03-09. **No client library and no
  API definition.**
- **Original site preserved** at the [Internet Archive (2016-04-01 snapshot)](http://web.archive.org/web/20160401035206/https://www.kitchensurfing.com/).

No artifacts (`packages/`, `well-known/`, `mcp/`, `llms/`, `openapi/`, `security/`, `conventions/`, `skills/`)
were generated. Their absence is the verified, correct result — nothing was fabricated to fill them.
