# 5DollarFootballAPI (5dollarfootballapi)

A read-only REST football (soccer) data API — live scores, fixtures, standings, league and team
surfaces, match events, and corner and card statistics, plus a bookmakers endpoint and a status
check. Fifteen operations across seven tags, bearer-token or API-key authentication.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/5dollarfootballapi/refs/heads/main/apis.yml)

- **Website:** https://5dollarfootballapi.com
- **Documentation:** https://5dollarfootballapi.com/docs
- **OpenAPI:** https://5dollarfootballapi.com/openapi.json
- **llms.txt:** https://5dollarfootballapi.com/llms.txt
- **API base:** `https://api.5dollarfootballapi.com/v1`

Part of the [API Evangelist](https://apievangelist.com) network.

## How this entry came to exist

Submitted through the apis.io Add-API form on 2026-08-19 — twice, three hours apart, and **parked
both times**. Both gate dossiers reported the domain "unreachable on every request" with "zero web
footprint".

That was no longer true when a human checked it. The homepage, all seven declared pointers, the
apis.json, the llms.txt and a valid 169KB OpenAPI 3.1.0 all returned 200, and a nonsense control
path returned a real 404. The site was most likely not yet live at submission time, and the
resubmission three hours later was probably an attempt to get it re-read.

Admitted by hand rather than dropped. Everything in `apis.yml` is harvested from the live surface,
not from either submission record — both were thin, carrying a single pointer each. The full
evidence is in `apis.yml` under `x-evidence`.
