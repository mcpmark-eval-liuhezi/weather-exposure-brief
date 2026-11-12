# Weather-Exposure Brief — Field Network On-Call Handoff

**Prepared:** November 12, 2026 (early morning, local time at sites)
**Purpose:** Audit-binder on-call handoff brief for us-east, us-central, us-south, and us-west relay sites.
**Data source:** NOAA/NWS observations and forecasts (National Weather Service), station data via weather observation station lookups. Provenance section below documents the upstream domain (weather.gov) and the AS13335 network behind our dashboards.

---

## Site 1: us-east — Ashburn, VA (39.0437, -77.4875)

**Alert Status: CLEAR** — No active weather alerts, watches, or warnings were returned for Virginia (VA). This site is clear.

**Current Observed Conditions (Station KJYO, observed 11/12/2026 3:55 AM local):**
- Temperature: 48.2°F (9.0°C), feels like 47.3°F (8.5°C) wind chill
- Conditions: Clear
- Humidity: 100%
- Wind: 12 mph from 80° (E)
- Pressure: 29.61 inHg
- Visibility: 10.0 miles

**24-Hour Precipitation Outlook (next 24 hours):**
- 4 AM–6 AM: Mostly Cloudy, 10% rain chance
- 7 AM–12 PM: Chance Rain Showers, 58% rain chance (peak risk this morning)
- 1 PM–6 PM: Scattered Rain Showers, 44% rain chance
- 7 PM–3 AM: Chance Rain Showers easing to 32%, then Slight Chance Showers at 20%
- **Takeaway:** Morning shower risk (up to 58%) easing through the day to 32% or lower by overnight. Dry background with clouds.

**Nearest Observation Station:** KJYO — Leesburg / Godfrey (elevation 390 ft, 5.0 miles from site). Latest report 11/12/2026 3:55 AM local, 48.2°F.

**Multi-Day Outlook:** Not required for this entry (state is CLEAR with no active alerts). For awareness: trend is dry and sunny, high near 77°F Thursday, sunny Friday (high 71°F), mostly sunny Saturday (high 67°F, 1% precip chance).

---

## Site 2: us-central — Dallas, TX (32.7767, -96.7970)

**Alert Status: WATCH** — Texas (TX) has 1 active alert: a **Flood Advisory (Minor severity, Expected urgency)** for Brooks County (Los Olmos Creek Near Falfurrias). Effective 11/11/2026 8:43 PM local, expires 11/12/2026 2:00 PM local. River levels on Los Olmos Creek near Falfurrias have risen to Action Stage (5.0 ft) with a current level of 8.70 ft; crest forecast at 8.8 ft just after midnight. Flood stage is 11.0 ft. Impacts include minor lowland flooding ~120 ft wide and FM 1418 closure risk at 9.0 ft. **This alert does not cover the Dallas site directly, but the state flag is WATCH.**

**Current Observed Conditions (Station KDAL, observed 11/12/2026 3:15 AM local):**
- Temperature: 53.6°F (12.0°C)
- Conditions: Clear
- Humidity: 77%
- Wind: 12 mph from 330° (NNW)
- Pressure: 30.09 inHg
- Visibility: 10.0 miles

**24-Hour Precipitation Outlook (next 24 hours):**
- 3 AM–5 AM: Clear to Mostly Clear
- 6 AM–2 PM: Sunny, 0% measurable precip risk
- 3 PM–5 PM: Sunny, clearing to Clear overnight
- 6 AM–2 AM (Fri): Clear throughout
- **Takeaway:** Extremely dry 24-hour window. Sunny all day, high near 77°F Thursday, clear night low around 52°F. No precipitation risk.

**Nearest Observation Station:** KDAL — Dallas Love Field (elevation 476 ft, 6.0 miles from site). Latest report 11/12/2026 3:15 AM local, 53.6°F.

**Multi-Day Outlook (WATCH state — included per runbook):**
- Thursday: Sunny, high near 77°F, NW wind ~5 mph, clear night low 52°F
- Friday: Sunny, high near 71°F, east northeast wind ~5 mph, partly cloudy night low 50°F
- Saturday: Mostly sunny, high near 67°F, ESE wind 5–10 mph, gusts to 25 mph, 1% precip chance

---

## Site 3: us-south — Miami, FL (25.7617, -80.1918)

**Alert Status: WATCH** — Florida (FL) has 6 active **Flood Warnings (Severe urgency, Immediate)** across multiple counties: Seminole (St. Johns River near Sanford and Above Lake Harney), Brevard (St. Johns River near Cocoa 9w — Major flooding), Lake,Volusia (St. Johns River near Deland and Astor), and DeSoto (Peace River at Arcadia). These affect central/east FL riverine flooding and do not directly impact the Miami site, but the state is flagged WATCH.

**Current Observed Conditions (Station KMIA, observed 11/12/2026 4:30 AM local):**
- Temperature: 73.4°F (23.0°C), heat index 74.6°F (23.7°C)
- Conditions: Clear
- Humidity: 89%
- Wind: 0 mph (calm)
- Pressure: 29.88 inHg
- Visibility: 10.0 miles

**24-Hour Precipitation Outlook (next 24 hours):**
- 4 AM–10 AM: Partly Sunny/Mostly Cloudy, 3–6% rain chance
- 11 AM–12 PM: Mostly Cloudy, up to 14% rain chance
- 1 PM–3 PM: Slight Chance Showers and Thunderstorms, 17%–26% rain chance (peak this afternoon)
- 4 PM–5 PM: Slight Chance Showers and Thunderstorms, 18%–19%
- 6 PM–3 AM: Mostly Cloudy, 6%–12% rain chance
- **Takeaway:** Low overall risk. Only a slight (≤26%) chance of afternoon showers/thunderstorms between 1 PM and 3 PM. Warm, humid, high near 84°F.

**Nearest Observation Station:** KMIA — Miami International Airport (elevation 10 ft, 8.3 miles from site). Latest report 11/12/2026 4:30 AM local, 73.4°F.

**Multi-Day Outlook (WATCH state — included per runbook):**
- Thursday: Partly sunny, slight chance of showers/t-storms 1–3 PM (30% chance, high near 84°F), mostly cloudy night low 73°F
- Friday: Partly sunny, high near 79°F, 7% precip chance; night low 63°F with NW gusts to 20 mph
- Saturday: Sunny, high near 71°F, north wind 12–16 mph, gusts to 21 mph, 1% precip chance

---

## Site 4: us-west — Redmond, WA (47.6742, -122.1215)

**Alert Status: WATCH** — Washington (WA) has 5 active alerts: a Flood Warning (Severe) for Mason County (Skokomish River at Potlatch), a Dense Fog Advisory for the Northern Panhandle/Spokane/Moses Lake area, a Dense Fog Advisory for Kittitas Valley, a Dense Fog Advisory for the Foothills of the Blue Mountains, and a Special Weather Statement for the Lower Columbia Basin (dense fog on I-82 and SR 221). None of these affect the Redmond site directly, but the state is flagged WATCH.

**Current Observed Conditions (Station SEAW1, observed 11/12/2026 12:30 AM local):**
- Temperature: 52.0°F (11.1°C)
- Humidity: 96%
- Wind: 4 mph from 3° (calm/N)
- (Conditions report from station: cloudy; observation returned no explicit condition text)

**24-Hour Precipitation Outlook (next 24 hours):**
- 1 AM–9 AM: Cloudy/Mostly Cloudy, 1%–3% rain chance
- 10 AM–4 PM: Mostly Cloudy, 1%–2% rain chance, warming from 50°F to 63°F
- 5 PM–11 PM: Cloudy, 2%–6% rain chance, cooling to ~52–53°F overnight
- **Takeaway:** Very dry. Precipitation chances ≤6% through the entire 24-hour window. Note: rain is actually forecast to arrive Friday (see multi-day outlook).

**Nearest Observation Station:** SEAW1 — Seattle Weather Forecast Office (elevation 29 ft, 6.2 miles from site). Latest report 11/12/2026 12:30 AM local, 52.0°F.

**Multi-Day Outlook (WATCH state — included per runbook):**
- Thursday: Mostly cloudy, high near 65°F, 3% precip chance; slight chance of light rain after 4 AM (20% chance), low around 51°F
- Friday: **Rain likely** — cloudy, high near 61°F, 70% precip chance, light rain likely; night low 48°F with 60% chance
- Saturday: Light rain likely, high near 58°F, 60% precip chance

**Handoff note for us-west:** Dry and clear tonight/tomorrow through Thursday, but a rain system moves in Friday (70% chance). Equipment left outdoors on Friday should be protected.

---

## Data Provenance

### weather.gov (upstream national weather source)

WHOIS registration record for weather.gov as returned by the lookup:

- **Domain Name:** weather.gov
- **Registrar:** get.gov (Registrar URL: https://get.gov; Registrar WHOIS Server: whois.nic.gov; Registrar IANA ID: 8888888)
- **Registrant Organization:** Department of Commerce (Silver Spring, MD, US)
- **Registry Security Email:** security@noaa.gov
- **Domain Status:** serverTransferProhibited (https://icann.org/epp#serverTransferProhibited)
- **Name Servers:** a1-97.akam.net, a11-66.akam.net, a18-67.akam.net, a26-64.akam.net, a6-65.akam.net, a7-66.akam.net (Akamai DNS)
- **DNSSEC:** signedDelegation
- **Created Date:** 1999-04-30T21:06:20Z
- **Updated Date:** 2026-10-01T11:30:29Z
- **Expiry Date:** 2027-08-27T15:55:27Z
- **WHOIS database last update:** 2026-11-12T09:43:53Z

### AS13335 (network behind our dashboards)

WHOIS record for AS13335 as returned by the ARIN lookup:

- **ASNumber:** 13335
- **ASName:** CLOUDFLARENET
- **ASHandle:** AS13335
- **RegDate:** 2010-07-14 | **Updated:** 2017-02-17
- **Organisation:** Cloudflare, Inc. (OrgId: CLOUD14, 101 Townsend Street, San Francisco, CA 94107, US)
- **Org RegDate:** 2010-07-09 | **Org Updated:** 2024-11-25
- **Comment:** All Cloudflare abuse reporting can be done via https://www.cloudflare.com/abuse
- **NOC Contact:** Cloudflare-NOC, +1-650-319-8930, noc@cloudflare.com
- **Abuse Contact:** abuse@cloudflare.com, +1-650-319-8930
- **Tech/Routing Contact:** Admin, rir@cloudflare.com, +1-650-319-8930
- **RDAP Ref:** https://rdap.arin.net/registry/autnum/13335

---

## Handoff Summary

| Site | State | Alert Status | 24h Precip Risk | Nearest Station | Key Note |
|------|-------|--------------|-----------------|-----------------|----------|
| us-east (Ashburn, VA) | VA | **CLEAR** (no active alerts) | 58% AM showers, then 32–44% | KJYO (Leesburg/Godfrey) | Dry, sunny trend |
| us-central (Dallas, TX) | TX | **WATCH** (Flood Advisory, Brooks County) | ~0% (sunny, clear) | KDAL (Dallas Love Field) | Flood advisory counties are far from Dallas; 24h outlook is dry |
| us-south (Miami, FL) | FL | **WATCH** (6 Flood Warnings, central/east FL) | ≤26% AM/PM t-storm chance | KMIA (Miami Intl) | Heat index ~75°F; afternoon t-storm slight chance |
| us-west (Redmond, WA) | WA | **WATCH** (Flood Warning Mason Co., Dense Fog Advisories) | ≤6% now; 70% rain Friday | SEAW1 (Seattle WFO) | Rain system arrives Friday — protect outdoor equipment |

**Overall:** No site is in weather crisis. us-east is CLEAR. us-central, us-south, and us-west are WATCH due to state-level alerts (none of which directly impact their immediate locations). The main forward-looking item is rain arriving at us-west on Friday (70% chance). All observations come from the named ASOS/AWOS stations (KJYO, KDAL, KMIA, SEAW1) listed per site.

*Brief generated for the on-call handoff meeting; data sourced from NWS observations and forecasts with WHOIS provenance records for weather.gov and AS13335 retained for the audit binder.*
