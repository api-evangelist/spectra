# Spectra (Defunct / Merged into OVG360)

Historical API Evangelist record for **Spectra** (also marketed as *Spectra
Experiences*) — a North American venue management, food services & hospitality,
and partnerships company headquartered in Philadelphia, PA. Spectra is no
longer an operating brand. Its businesses now trade as **OVG360**, a division
of **Oak View Group**.

## Status

- **Operating status**: Defunct as a trading brand.
- **Domain status**: `spectraexperiences.com` is dead — DNS / TLS no longer
  resolves to a live site (verified 2026-05-23).
- **Successor**: [OVG360](https://www.oakviewgroup.com/ovg360-2/), an Oak View
  Group division.
- **Public developer API**: None. Spectra never published an OpenAPI spec,
  SDK, CLI, developer portal, or sandbox during its operating life. Ticketing
  was delivered through Paciolan (since divested to Learfield); all other
  integrations were private enterprise contracts.

## Corporate history (verified)

| Date | Event | Source |
|---|---|---|
| 2015 | Comcast Spectacor consolidates Global Spectrum, Ovations Food Services, Paciolan, and Front Row Marketing into a single **Spectra** brand. | [Wikipedia — Comcast Spectacor](https://en.wikipedia.org/wiki/Comcast_Spectacor) |
| 2021-08-31 | Oak View Group announces planned acquisition of Spectra from co-owners Comcast Spectacor and Atairos. | [Philadelphia Inquirer](https://www.inquirer.com/business/oak-view-group-spectra-comcast-spectacor-merger-20210831.html) |
| 2021-11-15 | DOJ approves the deal; OVG closes the Spectra acquisition. Spectra at acquisition served ~330 top-tier client venues across North America and globally. | [PR Newswire](https://www.prnewswire.com/news-releases/oak-view-group-completes-major-acquisition-of-spectra-301429247.html) |
| 2022-02-25 | OVG formally consolidates Spectra and OVG Facilities into a single rebranded division: **OVG360**. The Spectra brand is retired. | [The Stadium Business](https://www.thestadiumbusiness.com/2022/02/25/oak-view-group-unites-ovg-facilities-spectra-under-ovg360-brand/) |

> *"Now that OVG's acquisition of Spectra is complete, we can get down to the
> business of delivering an expanded highly competitive set of services..."*
> — Tim Leiweke, CEO of Oak View Group (2021-11-15)

## Prior business lines (now part of OVG360)

Spectra operated three lines of business at the time of acquisition:

1. **Venue Management** — pre-construction consulting, event booking, day-of
   operations, ticketing, and staffing. Heir to the legacy *Global Spectrum*
   brand.
2. **Food Services & Hospitality** — concessions, premium catering, suite
   service, and culinary operations. Heir to the legacy *Ovations Food
   Services* brand.
3. **Partnerships** — property sales, naming rights, sponsorship, hospitality,
   and strategic consulting. Heir to the legacy *Front Row Marketing* brand.

All three are now delivered under the OVG360 umbrella, alongside OVG
Hospitality, Rhubarb, and Spectrum Catering brands within Oak View Group.

## Repository contents

| Path | Purpose |
|---|---|
| [`apis.yml`](apis.yml) | Historical apis.yml entry. `apis` array is intentionally empty — no public developer API ever existed. |
| [`vocabulary/spectra-vocabulary.yml`](vocabulary/spectra-vocabulary.yml) | Domain vocabulary for Spectra's venue management, food service, and partnerships concepts. |
| [`json-ld/spectra-context.jsonld`](json-ld/spectra-context.jsonld) | JSON-LD context mapping Spectra's organizational entities and services to schema.org, including successor / predecessor links. |

## What is intentionally absent

- **No `openapi/` folder** — Spectra never published an OpenAPI specification.
- **No `asyncapi/`, `json-schema/`, `json-structure/`, `examples/` folders**
  — there is no public API surface to derive these from.
- **No `rules/` (Spectral) folder** — no spec to lint.
- **No `capabilities/` folder** — Naftiko capabilities require a real API surface.
- **No `plans/`, `rate-limits/`, `finops/` folders** — Spectra had no
  developer-facing commercial offering; its services were sold via enterprise
  management agreements only.
- **No SDKs, CLIs, sample repos, or GitHub organization** under the Spectra
  brand.

For the live successor brand, profile [Oak View Group](https://www.oakviewgroup.com)
or its [OVG360 division](https://www.oakviewgroup.com/ovg360-2/) separately.

## Related API Evangelist records

- `comcast-spectacor` — Spectra's prior co-owner.
- `oak-view-group` — current parent company (covers OVG360 and related brands).
- `paciolan` — ticketing platform formerly bundled in Spectra; now a Learfield
  subsidiary.

---

*This repository documents a defunct entity. No further pipeline runs are
expected unless Spectra is revived as a trading brand.*
