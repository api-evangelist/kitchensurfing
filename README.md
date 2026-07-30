# Kitchensurfing

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
